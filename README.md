# Testes Manuais - Funcionalidade de Login

Este projeto tem como objetivo demonstrar habilidades em testes manuais, incluindo criação de casos de teste, execução e identificação de bugs.

## Cenário

Funcionalidade testada: Login de usuário em sistema web.

## Casos de Teste

### CT01 - Login com dados válidos
**Passos:**
1. Acessar página de login
2. Inserir usuário válido
3. Inserir senha válida
4. Clicar em "Entrar"

**Resultado esperado:**
Usuário deve acessar o sistema com sucesso.

---

### CT02 - Login com senha inválida
**Passos:**
1. Inserir usuário válido
2. Inserir senha incorreta
3. Clicar em "Entrar"

**Resultado esperado:**
Sistema deve exibir mensagem de erro.

---

### CT03 - Campos vazios
**Passos:**
1. Clicar em "Entrar" sem preencher campos

**Resultado esperado:**
Sistema deve solicitar preenchimento dos campos.

---

## Bugs Encontrados

### BUG01 - Mensagem de erro não exibida
**Descrição:**
Ao inserir senha inválida, o sistema não apresenta mensagem de erro.

**Severidade:**
Alta

---

### BUG02 - Botão permite envio com campos vazios
**Descrição:**
O sistema permite clicar em "Entrar" sem preencher os campos.

**Severidade:**
Média

---

## Ferramentas

- Testes manuais
- Postman (em aprendizado)
- JIRA (conceito)

---

## Próximos passos

- Aprender testes de API com Postman
- Evoluir para automação de testes
