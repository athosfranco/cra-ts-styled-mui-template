# Create React App example with styled-components & TypeScript

Repo template pra iniciar um projeto frontend com Create-React-App usando TypeScript, Styled-Components e MaterialUI.

Procedimento:

### 1) Clonar repositório dentro da pasta

```git clone https://github.com/athosfranco/cra-ts-styled-mui-template.git .```

### 2) Baixar todas as dependências e inicializar projeto em localhost

```
npm install
npm start
```

### 3)  Incluir o código abaixo no tsconfig

```json
"paths": {
  "@mui/styled-engine": ["./node_modules/@mui/styled-engine-sc"]
}
```

### 4) Instalar a tipagem do styled components

```sh
npm install --save-dev @types/styled-components
```

### Opcional 
Pra pular a configuração, setar `skipLibCheck: true` no seu tsconfig. 


