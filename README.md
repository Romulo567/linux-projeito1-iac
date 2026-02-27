# Automação de Infraestrutura de Usuários no Linux 🐧

Este é um projeto prático desenvolvido durante meus estudos de Linux. O objetivo é automatizar a criação e configuração de um ambiente simulado de uma empresa, provisionando usuários, grupos, diretórios e definindo políticas de permissões estritas.

##  Sobre o Projeto

O projeto consiste em um script (Shell Script) onde toda a infraestrutura básica de permissões do sistema operacional é criada de forma automática. Ele elimina a necessidade de comandos manuais repetitivos, garantindo que o ambiente seja configurado de forma rápida e segura.

##  O que foi implementado

- **Provisionamento Automático:** Criação automatizada de usuários, grupos de departamentos e diretórios correspondentes.
- **Permissões de Grupo (Controle Total):** Os usuários de cada grupo possuem **permissão total** (leitura, escrita e execução) apenas dentro do diretório do seu respectivo departamento.
- **Segurança e Isolamento:** Usuários **não possuem** permissões de leitura, escrita ou execução em diretórios de departamentos aos quais não pertencem.

## 🛠️ Tecnologias Utilizadas

- **Linux**
- **Bash Scripting** (Shell Script)
  
##  Como executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/Romulo567/linux-projeto1-iac.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd linux-projeto1-iac
   ```
3. Dê permissão de execução ao script (substitua `script.sh` pelo nome exato do seu arquivo):
   ```bash
   chmod +x iacl.sh
   ```
4. Execute o script (é necessário rodar como superusuário/root para criação de usuários e pastas na raiz):
   ```bash
   sudo ./iac1.sh
   ```
