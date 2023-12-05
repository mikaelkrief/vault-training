# To start the vault server

## For developpement mode

Run the server

```plain
vault server -dev -dev-listen-address="0.0.0.0:8200" -dev-root-token-id=root
```{{exec}}


## For production mode

- unseal




Inside another tab

export the env var

```plain
export VAULT_ADDR='http://0.0.0.0:8200'
```{{exec}}

Check the stutus of the Vault with the command :

```plain
vault status
```{{exec}}

[Open UI]({{TRAFFIC_HOST1_8200}})
