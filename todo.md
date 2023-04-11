## app

### Preparando ambiente

- configure as variáveis de ambiente
- clone o repositório do web dentro da pasta www
- acesse o shell da instancia php e rode o comando
  ```bash
      chmod -R 777 ./web
  ```

### Resolução de problemas

```txt
The stream or file "/var/www/html/web/src/helper/../../log/logs_execucao_eventos.log" could not be opened in append mode: failed to open stream: Permission denied
The stream or file "/var/www/html/web/src/helper/../../log/logs_requisicoes_iugu.log" could not be opened in append mode: failed to open stream: Permission denied
```

erros relacionados a permissao de arquivo execute

```bash
chmod 777 <nome do arquivo>
```
