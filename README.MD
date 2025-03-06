<h1 align="center">Infraestrutura como Código com Terraform</h1>
<p align="center">
  <img src="data:image/png;base64,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" alt="Terraform">
</p>

Bem-vindo ao repositório de Infraestrutura como Código (IaC) com Terraform! Aqui você encontrará diferentes projetos utilizando Terraform para gerenciar infraestrutura em provedores de cloud como AWS, Databricks e Microsoft Azure.

#### ☁️ Provedores Suportados
Atualmente, este repositório contém configurações Terraform para os seguintes provedores:

* AWS (Amazon Web Services)
* Azure (Microsoft Azure)
* Databricks

#### 🔧 Pré - requisitos
Antes de utilizar qualquer projeto, certifique-se de ter os seguintes requisitos atendidos:

1 - Terraform instalado

* Download Terraform
* Verifique a instalação:

```sh
terraform version
```
2 - Credenciais do Provedor
* AWS
* Azure
* Databricks

#### ▶️ Como Usar

1 - Entre no diretório do projeto 
```sh
cd aws/projeto1
```

2 - Inicialize o Terraform 
```sh
terraform init
```

3 - Visualize o plano de execução
```sh
terraform plan
```

4 - Aplique as mudanças
```sh
terraform apply
```

4 - Destruir infraestrutura(se necessário)
```sh
terraform destroy
```

#### 👨‍💻 Desenvolvedor do projeto
[<img src="https://avatars.githubusercontent.com/u/96426356?s=400&u=cb53042cc402d962207c7a20dfb6804a580f9526&v=4" width=115><br><sub>Vitor Souza</sub> ](https://github.com/vitorhssouza)


[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vitorhugossouza/)
[![!Currículo](https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://vitorhssouza.github.io/#home)