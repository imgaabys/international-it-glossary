# 🛠️ Active Directory Administration & PowerShell Guide
> **Languages:** [English](#english) | [Português (Brasil)](#português-br) | [Português (Portugal)](#português-pt)

---

## <a name="english"></a> 🇺🇸 English: AD Management Guide

### 🔑 Essential Concepts
* **Organizational Units (OU):** Used to categorize objects (users, computers) by department or location.
* **GPO (Group Policy Objects):** Rules applied to automate configurations across the network.

### 💻 Useful PowerShell Commands
To use these, ensure you have the **Active Directory Module** installed.

1. **Check User Status:**
   `Get-ADUser -Identity "username" -Properties LockedOut, Enabled`
   *(Verifies if the account is locked or disabled.)*

2. **Unlock an Account:**
   `Unlock-ADAccount -Identity "username"`
   *(Quickly unlocks a user without browsing the GUI.)*

3. **List Members of a Security Group:**
   `Get-ADGroupMember -Identity "GroupName"`
   *(Audit who has access to specific folders/permissions.)*

---

## <a name="português-br"></a> 🇧🇷 Português (BR): Guia de Administração de AD

### 🔑 Conceitos Essenciais
* **Unidades Organizacionais (OU):** Utilizadas para categorizar objetos (usuários, computadores) por departamento ou filial.
* **GPO (Objetos de Diretiva de Grupo):** Regras aplicadas para automatizar configurações em toda a rede.

### 💻 Comandos Úteis de PowerShell
Certifique-se de ter o módulo de Active Directory instalado.

1. **Verificar Status do Usuário:**
   `Get-ADUser -Identity "nome_usuario" -Properties LockedOut, Enabled`
   *(Verifica se a conta está bloqueada ou desativada.)*

2. **Desbloquear uma Conta:**
   `Unlock-ADAccount -Identity "nome_usuario"`
   *(Desbloqueia um usuário rapidamente sem usar a interface gráfica.)*

3. **Listar Membros de um Grupo de Segurança:**
   `Get-ADGroupMember -Identity "NomeDoGrupo"`
   *(Auditoria de quem tem acesso a pastas ou permissões específicas.)*

---

## <a name="português-pt"></a> 🇵🇹 Português (PT): Guia de Gestão de AD

### 🔑 Conceitos Essenciais
* **Unidades Organizacionais (OU):** Usadas para categorizar objetos (utilizadores, computadores) por departamento ou localização geográfica.
* **GPO (Objetos de Política de Grupo):** Regras aplicadas para automatizar configurações em toda a rede.

### 💻 Comandos Úteis de PowerShell

1. **Verificar Estado do Utilizador:**
   `Get-ADUser -Identity "nome_utilizador" -Properties LockedOut, Enabled`
   *(Verifica se a conta está bloqueada ou desativada.)*

2. **Desbloquear uma Conta:**
   `Unlock-ADAccount -Identity "nome_utilizador"`
   *(Desbloqueia um utilizador rapidamente através da consola.)*

3. **Listar Membros de um Grupo de Segurança:**
   `Get-ADGroupMember -Identity "NomeDoGrupo"`
   *(Auditoria para verificar quem tem acesso a pastas partilhadas.)*
