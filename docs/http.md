# Account Types

```js
{
  "id": "<uuid>",
  "name": "<name>"
}
```

## GET /account_types

Response:

```js
[
  <AccountType>,
  <AccountType>,
  ...
]
```

# Accounts

```js
{
  "id": "<uuid>",
  "name": "<name>",
  "account_type_id": "<uuid>",
  "parent_account_id": "<uuid>", // can be null
  "before_account_id": "<uuid>", // can be null
  "after_account_id": "<uuid>", // can be null
}
```

## GET /accounts

Response:

```js
[
  <Account>,
  <Account>,
  ...
]
```

## PUT /accounts/\<uuid\>

Request:

```js
<Account>
```

Response:

```js
[
  <Account>,
  <Account>,
  ...
]
```
