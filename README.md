# BurgerRoyale - Infra RDS e VPC

Esse Terraform é responsável por criar a infraestrutura de Banco de Dados RDS e de uma VPC.

## Pré-requisitos

Antes de começar, você precisa ter os seguintes softwares instalados:

- AWS CLI
- Terraform

### Instalação do AWS CLI

Para instalar o AWS CLI, siga as instruções disponíveis na documentação oficial da AWS:

```bash
https://aws.amazon.com/cli/
```

### Instalação do Terraform

Para instalar o Terraform, visite a página de downloads do Terraform e siga as instruções específicas para o seu sistema operacional:

```bash
https://www.terraform.io/downloads.html
```

## Configuração

1. Após a instalação dos softwares necessários, configure o AWS CLI com suas credenciais. Isso permitirá que o Terraform e a AWS CLI interajam com os recursos da sua conta da AWS.

```bash
aws configure
```

2. Crie um Bucket S3 chamado `burgerroyale-s3-bucket` para que o Terraform possa armazenar o estado da sua infra.

## Uso

Para iniciar o projeto , siga os passos abaixo:

1. Inicialize o Terraform para preparar seu projeto:

```bash
terraform init
```

2. Revise o plano de execução do Terraform para entender as alterações que serão aplicadas na AWS. Preencha os dados solicitados.

```bash
terraform plan 
```

3. Aplique as configurações na AWS. Preencha os dados solicitados.

```bash
terraform apply
```