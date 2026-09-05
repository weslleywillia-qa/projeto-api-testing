# API-003 - Atualizar usuário

**Método:** PUT  
**Endpoint:** `https://jsonplaceholder.typicode.com/users/1`

## Objetivo

Validar se a API permite atualizar os dados de um usuário existente por meio de uma requisição PUT.

## Dados enviados

```json
{
  "id": 1,
  "name": "Weslley Willian Atualizado",
  "username": "weslleyqa",
  "email": "weslleyqa@email.com"
}
```

## Resultado esperado

- Requisição processada com sucesso
- Status HTTP `200 OK`
- Resposta em formato JSON
- Retorno dos dados atualizados
- Manutenção do identificador `id: 1`

## Resultado obtido

A API processou com sucesso a atualização do usuário e retornou os dados atualizados.

Status HTTP retornado: `200 OK`.

O identificador `id: 1` foi mantido.

## Status

✅ PASS

## Evidência

Evidência da execução realizada no Postman.
