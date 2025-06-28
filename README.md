# Desafio-Prático Máquinas Virtuais na Azure
Este repositório contém a documentação completa da minha experiência prática no laboratório proposto no Bootcamp DIO + XP Inc. sobre o uso de máquinas virtuais (VMs) na plataforma Azure.

## 📚 Objetivo do Desafio

Consolidar o aprendizado teórico com a criação e gerenciamento de VMs na Azure, demonstrando domínio dos principais conceitos, ferramentas e boas práticas, além de utilizar o GitHub como meio de documentação e compartilhamento técnico.

## 🎯 Objetivos de Aprendizagem

✔️ Aplicar os conceitos aprendidos em um ambiente prático  
✔️ Documentar processos técnicos de forma clara e estruturada  
✔️ Utilizar o GitHub para compartilhar conhecimento técnico  

---

## 🛠️ Etapas Realizadas

### 1. ✅ Acesso ao Portal Azure
- Criação de uma conta gratuita
- Navegação inicial e familiarização com a interface

### 2. ☁️ Criação da Máquina Virtual

| Propriedade                      | Valor                                        |
| -------------------------------- | -------------------------------------------- |
| **Nome do computador**           | MyVM                                         |
| **Grupo de Recursos**            | MyVM\_group                                  |
| **Status**                       | Em execução                                  |
| **Sistema Operacional**          | Windows Server 2022 Datacenter Azure Edition |
| **Geração / Arquitetura**        | V2 / x64                                     |
| **Localização**                  | West US 3 – Zona de Disponibilidade 1        |
| **Tamanho da VM**                | Standard B1s (1 vCPU, 1 GiB RAM)             |
| **IP Público**                   | 20.171.25.88                                 |
| **Rede Virtual / Sub-rede**      | MyVM-vnet / default                          |
| **Nome DNS**                     | Não configurado                              |
| **Data de Criação**              | 28/06/2025, 20:43 UTC                        |
| **Assinatura Azure**             | Azure subscription 1                         |
| **ID da Assinatura**             | d7de1df4-3dee-4dfa-a2d9-c41d723f5d54         |
| **Agente de VM**                 | Pronto (Versão 2.7.41491.1149)               |
| **Inicialização Segura / vTPM**  | Habilitado                                   |
| **Monitoramento de Integridade** | Desabilitado                                 |
| **Azure Spot**                   | Não habilitado                               |
| **Extensões / Aplicativos**      | Nenhum instalado                             |


### 3. 🔐 Configuração de Acesso via SSH
- Geração de chave SSH local
- Conexão bem-sucedida utilizando terminal

### 4. 📦 Instalação de Pacotes na VM
- Atualização do sistema

### 5. 📸 Capturas de Tela
As imagens estão disponíveis na pasta [`/images`](./images) com os principais momentos do processo.


## 🧠 Aprendizados

Durante este desafio, pude reforçar:
- A importância de configurar corretamente os recursos de rede e segurança;
- Como conectar e manipular máquinas remotas com comandos básicos;
- O uso do GitHub como repositório técnico e portfólio profissional.

