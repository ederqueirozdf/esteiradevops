<h1 align="center"> Esteira - Kubernetes | Kubespray 🐧 </h1>

- Repositório de configuração de um cluster kubernetes utilizando soluções para automatização da construção da estrutura de infra com integração e entrega contínua (Em construção)

#### 👤 Por: **Eder Queiroz**
 - 🐱 Github: [@ederqueirozdf](https://github.com/ederqueirozdf)
 - 🤙 Telegram: [@ederqueirozdf](https://t.me/ederqueirozdf)
 - Linux ❤️
<hr>

- [Cluster Kubernetes](Arquitetura-Kubespray-GCP.md#cluster-kubernetes)
      - [Pré-Requisitos:](Arquitetura-Kubespray-GCP.md#pré-requisitos)
      - [Introdução](Arquitetura-Kubespray-GCP.md#introdução)
  - [1. Download do terraform:](Arquitetura-Kubespray-GCP.md#1-download-do-terraform)
  - [2. Preparando o GCP para o Terraform](Arquitetura-Kubespray-GCP.md#2-preparando-o-gcp-para-o-terraform)
  - [3. Configuração do Terraform](Arquitetura-Kubespray-GCP.md#3-configuração-do-terraform)
    - [3.1 Configuração dos arquivos .tf](Arquitetura-Kubespray-GCP.md#31-configuração-dos-arquivos-tf)
      - [3.1.1. main.tf](Arquitetura-Kubespray-GCP.md#311-maintf)
      - [3.1.2. network.tf](Arquitetura-Kubespray-GCP.md#312-networktf)
      - [3.1.3. firewall.tf](Arquitetura-Kubespray-GCP.md#313-firewalltf)
      - [3.1.4. hosts.tf](Arquitetura-Kubespray-GCP.md#314-hoststf)
      - [3.1.4. variables.tf](Arquitetura-Kubespray-GCP.md#314-variablestf)
  - [2. Kubespray](Arquitetura-Kubespray-GCP.md#2-kubespray)
      - [2.1 Host ansible](Arquitetura-Kubespray-GCP.md#21-host-ansible)
      - [2.1.2 Instalação do git e pré-requisitos Kubespray](Arquitetura-Kubespray-GCP.md#212-instalação-do-git-e-pré-requisitos-kubespray)
      - [2.1.3 Gerando chaves ssh (ansible)](Arquitetura-Kubespray-GCP.md#213-gerando-chaves-ssh-ansible)
      - [2.1 Instalação do cluster kubernetes (kubespray)](Arquitetura-Kubespray-GCP.md#21-instalação-do-cluster-kubernetes-kubespray)
  - [3. Nginx Ingress](Arquitetura-Kubespray-GCP.md#3-nginx-ingress)
  - [4. Storage](Arquitetura-Kubespray-GCP.md#4-storage)
  - [5. JenkinsX](Arquitetura-Kubespray-GCP.md#5-jenkinsx)
  - [6. Git](Arquitetura-Kubespray-GCP.md#6-git)

- [Gerenciando Kubernetes]
  - [Octant + Jenkinsx](JenkinsX/Octante.md)
