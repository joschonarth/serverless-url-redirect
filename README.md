# 🔄 Redirecionador de URL Serverless

Este repositório contém a implementação da funcionalidade de **Redirecionamento de URLs curtas**, desenvolvido em **Java** e utilizando uma arquitetura **serverless** com serviços da **AWS**.

## 📜 Visão Geral do Projeto

O **Encurtador de URL Serverless** é um sistema de encurtamento de URLs simples e eficiente, desenvolvido com uma arquitetura totalmente serverless, utilizando **AWS Lambda**, **AWS API Gateway**, **AWS S3** e **AWS IAM** para garantir escalabilidade, baixo custo e segurança. O projeto inclui tanto a funcionalidade de encurtamento de URLs quanto a configuração de um redirecionador de URLs para reverter os links curtos.


## 🛠️ Tecnologias Utilizadas

- ☕ **Java**: Linguagem de programação utilizada.
- ⚡ **AWS Lambda**: Para execução das funções serverless.
- 📂 **AWS S3**: Para armazenar as URLs originais e os códigos curtos gerados.
- 🌐 **AWS API Gateway**: Para expor as APIs do sistema.
- 🔒 **AWS IAM**: Para definição de políticas que controlam o acesso das funções Lambda.

## ⚙️ Funcionalidades

- 🌐 Receber um código curto via API.
- 🗂️ Consultar o bucket S3 para recuperar a URL original associada ao código.
- 🔄 Validar se o código existe e redirecionar o usuário para a URL original.  

## 🔗 Encurtamento de URL

Este projeto de redirecionamento de URL depende do **[Encurtador de URL Serverless](https://github.com/joschonarth/serverless-url-shortener)**, que é responsável por gerar e armazenar os códigos curtos. 

➡️ Para configurar o encurtamento de URL, consulte o repositório do **[Encurtador de URL Serverless](https://github.com/joschonarth/serverless-url-shortener)**.

## 📚 Links Úteis

- 🔧 [AWS Lambda](https://aws.amazon.com/lambda/)
- 🗄️ [AWS S3](https://aws.amazon.com/s3/)
- 🌐 [AWS API Gateway](https://aws.amazon.com/api-gateway/)
- 🛠️ [AWS Serverless Application Model (SAM)](https://aws.amazon.com/serverless/sam/)