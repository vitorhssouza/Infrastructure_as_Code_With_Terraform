<h1 align="center"> Projeto 1 - Automatização de Infraestrutura de Processamento de Dados com AWS EMR e Apache Flink </h1>

#### Visão Geral

O Projeto 1 tem como objetivo desenvolver uma solução robusta e escalável para processamento de dados, utilizando o AWS EMR (Elastic MapReduce) e o framework Apache Flink. O foco principal é a automação da configuração e do gerenciamento da infraestrutura necessária para executar pipelines de processamento de dados em lote e em streaming, garantindo alta eficiência no tratamento de grandes volumes de dados com baixa latência.

#### Tecnologias Utilizadas

* AWS EMR (Elastic MapReduce): Plataforma gerenciada para big data na AWS.

* Apache Flink: Framework de processamento de dados em tempo real e em lote.

* Terraform: Ferramenta de Infraestrutura como Código (IaC) para provisionamento automatizado.

* AWS S3: Armazenamento escalável de dados.

* AWS IAM: Controle de acesso e permissões.

* AWS CloudWatch: Monitoramento e logs.

#### Objetivos

* Automatizar a infraestrutura necessária para processamento de dados usando Terraform.

* Provisionar e gerenciar clusters EMR otimizados para execução de workloads Apache Flink.

* Criar pipelines de processamento de dados em lote e em streaming.

* Garantir escalabilidade e baixa latência para lidar com grandes volumes de dados.

* Monitorar e otimizar o desempenho das cargas de trabalho.

#### Estrutura do Projeto

```plaintext
Projeto 1 AWS EMR E Apache Flink
│── IaC/                      # Pasta que contém todos os script para implantação de IaC
│── Dockerfile                # Script para execução no Docker
│── LEIAME.txt               # Passo a passo para execução.
│── README.md                 # Documentação principal
```


#### Como Usar

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