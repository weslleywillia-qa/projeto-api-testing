# API-002 - Criar usuário

**Método:** POST  
**Endpoint:** `https://jsonplaceholder.typicode.com/users`

## Objetivo

Validar se a API aceita a criação de um novo usuário por meio de uma requisição POST.

## Dados enviados

```json
{
  "name": "Weslley Willian",
  "username": "weslleyqa",
  "email": "weslleyqa@email.com"
}
```
## Resultado esperado

- Requisição processada com sucesso
- Status HTTP `201 Created`
- Resposta em formato JSON
- Retorno dos dados enviados
- Geração de um identificador `id`

## Resultado obtido

A API processou com sucesso a criação do usuário, retornando os dados enviados e o identificador `id: 11`.

Status HTTP retornado: `201 Created`.

## Status

✅ PASS

## Evidência

Evidência da execução realizada no Postman.


