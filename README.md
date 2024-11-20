# 🌐 Redirecionador de URL Serverless

Este repositório contém a implementação da funcionalidade de **redirecionamento de URLs curtas** em **Java**, utilizando uma arquitetura **serverless** com serviços da **AWS**.

## 🛠️ Tecnologias Utilizadas

- ☕ **Java**: Linguagem de programação utilizada.
- ⚡ **AWS Lambda**: Para execução de funções serverless.
- 📂 **AWS S3**: Para armazenamento das URLs encurtadas e metadados.
- 🌐 **AWS API Gateway**: Para expor as APIs do sistema.
- 🔒 **AWS IAM**: Para controle de permissões e segurança.  

## ⚙️ Funcionalidades

- 🌐 Receber um código curto via API.
- 🗂️ Consultar o bucket S3 para recuperar a URL original associada ao código.
- 🔄 Validar se o código existe e redirecionar o usuário para a URL original.  

## 🔗 Encurtador de URL

O **Redirecionador de URL** complementa o **Encurtador de URL**, gerenciando o redirecionamento dos códigos gerados para suas URLs originais.

➡️ **Confira o repositório do Encurtador de URL [aqui](https://github.com/joschonarth/serverless-url-shortener)**.