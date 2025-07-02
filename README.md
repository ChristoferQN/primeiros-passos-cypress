# 🧪 Cypress Automation - OrangeHRM

Automação de testes end-to-end utilizando Cypress para o sistema OrangeHRM. Este projeto tem como objetivo validar funcionalidades essenciais da aplicação, como login e atualização de informações do usuário.

## Tecnologias Utilizadas

- Cypress
- JavaScript
- Node.js

## Estrutura de Pastas

```
cypress/
├── e2e/
│ └── orangeHrm.cy.js # Arquivo principal dos testes
├── fixtures/
│ └── userData.json # Dados dos usuários (válido e inválido)
```

## Funcionalidades Testadas

- ✅ **Login com sucesso**
- ❌ **Login com falha (credenciais inválidas)**
- 🔧 **Acesso à seção de informações pessoais (My Info)**

## Como executar os testes
```
1. Clone o repositório
git clone https://github.com/seu-usuario/cypress-orangehrm-tests.git
cd cypress-orangehrm-tests 

2. Instale as dependências
npm install

3. Execute os testes em modo interativo
npx cypress open
```
## Dados de Teste
Os dados dos usuários estão no arquivo:
cypress/fixtures/userData.json
```
{
    "userSucess": {
        "username": "Admin",
        "password": "admin123"
    },
    "userFail": {
        "username": "Test",
        "password": "Test"
    }
}
```
## Aprendizados
- Criação de testes end-to-end com Cypress.
- Manipulação de elementos utilizando seletores CSS.
- Validação de URLs, elementos de interface e alertas de erro.
- Organização de dados sensíveis usando fixtures.
- Boas práticas na escrita de testes automatizados.
