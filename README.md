 🖥️ Laboratório Prático: Administração de Utilizadores e Permissões NTFS (Windows 10 Pro)

📌 Descrição do Projeto
Este projeto consiste num laboratório prático de suporte técnico e administração de sistemas desenvolvido numa máquina virtual (Oracle VM VirtualBox).

O objetivo principal foi realizar o provisionamento do sistema operativo Windows 10 Pro, a gestão de contas de utilizadores locais e a configuração de permissões de segurança NTFS num diretório corporativo.

---
 🛠️ Tecnologias e Ferramentas
Hipervisor:Oracle VM VirtualBox
Sistema Operativo: Windows 10 Pro
Gestão de Utilizadores:** Consola `lusrmgr.msc` (Utilizadores e Grupos Locais)
Segurança do Sistema de Ficheiros:** Permissões NTFS (Controle Total)

---

🚀 Passos Executados
1. Provisionamento do Ambiente
* Instalação e configuração inicial do Windows 10 Pro na máquina virtual.

2. Gestão de Utilizadores
* Acesso à consola de gestão local (`lusrmgr.msc`).
* Criação da conta de utilizador local `usuario.suporte` destinada a testes de suporte e administração.

3. Segurança e Acesso ao Sistema de Ficheiros
* Criação do diretório `C:\Projetos_TI`.
* Configuração de segurança e atribuição de permissão explícita de **Controle Total** para o utilizador `usuario.suporte`.
