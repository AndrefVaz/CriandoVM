# 🚀 Implantação de Máquinas Virtuais no Microsoft Azure

Este repositório documenta a prática de **criação, configuração e gerenciamento de máquinas virtuais (VMs)** na nuvem Azure. A atividade foi realizada como parte do processo de aprendizado sobre computação em nuvem e serviços de infraestrutura como serviço (IaaS).

## ☁️ Visão Geral

O Microsoft Azure permite a criação de VMs de forma rápida, escalável e com alta disponibilidade, sendo ideal para aplicações de desenvolvimento, testes, ambientes de produção e simulações de cenários corporativos.

## 🛠️ Etapas da Implantação

Abaixo estão os principais passos executados durante a implantação:

### 1. Criação da Máquina Virtual

- Acesso ao [Portal Azure](https://portal.azure.com/)
- Seleção do tipo de sistema operacional (ex: Windows Server, Ubuntu)
- Escolha do tamanho da VM (SKU) com base em CPU, memória e custo
- Criação de grupo de recursos e definição da região (location)

### 2. Configuração de Rede

- Geração automática de uma **rede virtual (VNet)** e **sub-rede**
- Criação de um IP público
- Configuração de um **grupo de segurança de rede (NSG)** para habilitar portas como **SSH (22)** ou **RDP (3389)**

### 3. Acesso Seguro

- Escolha entre autenticação por **senha** ou **chave SSH**
- Regras de firewall aplicadas para limitar acesso externo indesejado
- Definição de credenciais de administrador

### 4. Monitoramento e Manutenção

- Ativação do **Azure Monitor** e **Log Analytics** para telemetria de uso
- Opções de backup, auto-shutdown e escalonamento vertical/horizontal
- Gerenciamento via **Azure CLI**, **PowerShell** ou **portal web**

## 💡 Benefícios Observados

- **Rápida implantação** de infraestrutura sem necessidade de hardware físico
- **Escalabilidade sob demanda**, ideal para cargas variáveis
- **Economia com modelo pay-as-you-go**
- **Ambiente controlado e seguro** para testes e simulações

## 📁 Estrutura Recomendada para o Projeto

```bash
📦azure-vm-deployment/
 ┣ 📂screenshots/
 ┃ ┗ 📸 imagens da criação da VM
 ┣ 📜README.md
 ┗ 📄vm-deployment-notes.md
```
