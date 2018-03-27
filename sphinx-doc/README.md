```bash
docker build -t prozz/sphinx-doc .
docker run -u <user id> -v <some dir with docs>:/docs prozz/sphinx-doc:latest <command to execute>
```
