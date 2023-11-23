
## Criação da Chave

```sh
	ssh-keygen -t rsa -b 4096 -c "nome@email.com"
```

- Indique o e-mail associado com sua conta no GitHub

## Publicação da chave pública no GitHub

```ssh
	cat ~/.ssh/id_rsa.pub
```

- Copie a chave
- Publique-a no GitHub