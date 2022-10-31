# To install the vault server

## For developpement mode

Run the server

```plain
vault server -dev
```{{exec}}


Inside another tab

export the env var

```plain
export VAULT_ADDR='http://127.0.0.1:8200'
```{{exec}}

Check the stutus of the Vault with the command :

```plain
vault status
```{{exec}}