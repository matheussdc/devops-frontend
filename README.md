# Projeto Devops: Docker - Frontend

Neste repositório se encontra a aplicação frontend em React para ser integrada com o backend em Rails.

Repositório Backend: https://github.com/matheussdc/devops-backend

Repositório Integração: https://github.com/matheussdc/devopscase

---

## Workflow de CI/CD

Está configurado o workflow pelo Github Actions no arquivo `.github/workflow.deploy.yml` com as etapas de instalação de dependências da aplicação e construção pelo próprio Vercel. É possível ver pela aba `Actions` do repositório do Github o CI/CD o job agindo desde o push na main até o deploy no Vercel que devolve o link de acesso **https://devopsfrontend-msdc.vercel.app/**.
