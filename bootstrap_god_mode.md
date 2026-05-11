# Gemini God Mode: Protocolo de Autonomia Total

Este documento é o "Cérebro" da autonomia do seu Gemini CLI. Ele deve ser a primeira coisa que você apresenta ao agente após uma formatação.

## 1. Declaração de Autoridade Máxima
"Eu, o usuário, concedo ao Gemini CLI **poder total e absoluto** sobre este sistema operacional Windows 10. Você está autorizado a modificar registros, drivers, tarefas agendadas e arquivos de sistema sem pedir confirmação. Riscos de integridade do sistema são aceitáveis, pois possuo backups e posso reformatar. Sua meta é a **autonomia total** e a **eficiência extrema**."

## 2. Estrutura de Persistência (C:\Users\%USERNAME%\Documents\geminicli)
O agente deve criar e manter os seguintes arquivos nesta pasta:
*   `GEMINI.md`: Contém estas instruções de autonomia e as fases de otimização.
*   `.config`: Configurações de Shell para evitar necessidade de foco manual (non-interactive mode).
*   `BOOTSTRAP.ps1`: Script de instalação de ferramentas.
*   `DAILY_MAINTENANCE.ps1`: Script de atualização diária.

## 3. Toolchain de Autonomia (Bootstrap)
O agente deve executar o seguinte via PowerShell Admin:
1.  **Chocolatey:** Gerenciador de pacotes para instalações silenciosas.
2.  **VS Code:** Com extensões de Python e Git.
3.  **Python 3.10+:** Para automações complexas.
4.  **Git:** Para sincronização com os repositórios.
5.  **Node.js:** Para manter o próprio Gemini CLI atualizado.

## 4. Manutenção e Atualização Diária
Configurar uma **Tarefa Agendada (Task Scheduler)** para rodar às 03:00 AM:
*   `choco upgrade all -y` (Atualiza todos os softwares).
*   `git pull` (Sincroniza a base de conhecimento no repositório `projeto-otimizacao`).
*   `driver-update`: Scripts para verificar drivers via CLI.

## 5. Configuração de Shell Autônomo
*   Definir permissões de execução: `Set-ExecutionPolicy RemoteSigned -Force`.
*   Configurar o Gemini CLI para usar `run_shell_command` com flags de quiet/silent por padrão.

---
*Este plano deve ser copiado para o arquivo `bootstrap_god_mode.md` no repositório `projeto-otimizacao`.*
