# 🛡️ Política de Segurança no Windows 

Este repositório contém a documentação e os registros da **Atividade 04 - Política de Segurança no Windows**, desenvolvida como parte do curso de **Análise e Desenvolvimento de Sistemas (ADS)**.

## 📋 Sobre o Projeto

O trabalho foi dividido em duas fases estratégicas:
1.  **Definição de Políticas (Teórica):** Elaboração de um documento normativo com regras para senhas, backups, acesso remoto e criptografia.
2.  **Laboratório Prático:** Configuração manual de uma Máquina Virtual (VM) para aplicar as regras definidas utilizando ferramentas administrativas do Windows.

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **Virtualização:** Oracle VM VirtualBox
* **Sistema Operacional:** Windows 10 Pro 
* **Gerenciamento de Políticas:** Editor de Política de Grupo Local (`gpedit.msc`)
* **Segurança de Rede:** Windows Defender Firewall (`wf.msc`)
* **Controle de Arquivos:** NTFS Permissions (ACL)

## ⚙️ Implementações Realizadas

Durante o laboratório, foram configurados os seguintes controles de segurança:

* ✅ **Políticas de Senha:** Definição de complexidade, comprimento mínimo e histórico de senhas.
* ✅ **Bloqueio de Conta:** Configuração de *threshold* para mitigar ataques de força bruta (bloqueio após X tentativas falhas).
* ✅ **Firewall de Borda:** Criação de regras de entrada/saída para bloqueio de portas críticas (ex: porta 80/HTTP).
* ✅ **Controle de Acesso (ACL):** Segregação de privilégios criando pastas confidenciais e negando acesso a usuários "Visitantes".
* ✅ **Proteção de Endpoint:** Verificação e atualização do Microsoft Defender.
* ✅ **Criptografia e Backup:** Simulação de ativação do BitLocker e configuração de rotinas de backup local.

---
*Desenvolvido por Gabriella Mizrach*
