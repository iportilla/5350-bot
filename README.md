# Contoso CareScape 

## Chatbot Demo

For details about using this service, see [chatbot.md](chatbot.md).

## Building and Publishing

**Note:** if you build your own chatbot update index.html with your chatbot URL.
Set environment variables as recommended in `horizon/envvars.sh.sample` and then:

```
make build
make docker-push
make exchange-publish
```
