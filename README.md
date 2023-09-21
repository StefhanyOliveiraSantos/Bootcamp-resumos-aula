
# **Bootcamps DIO** | Resumos
## Versionameto de código com Git e GitHub

É uma maneira organizada de administrar mudanças no código. A cada alteração no código é gerada uma nova versão, pois é inserido algo que não estava lá anteriormente.

### *Sistema de controle de versão*
é o software que controla as versões de um arquivo ao longo do tempo.

- 📋 Registrando o histórico de atualizações de um arquivo
- 🗳️ Gerencia tanto as atualizações feitas, como quando e quem fez, etc.
## Tipos de sistemas de controle de versão
### 🎯 *VCS - Centralizado (CVCS)* 
Tem um *servidor central*, onde tem o acesso as versões e cada um trabalha no arquivo e salva as versões (como uma nuvem, fazendo backup), porém, é centralizado no servidor. Se o servidor "cair" não consegue acessar, alterar ou salvar versões.
### 🗂️*VCS Distribuido (DVCS)*
Possui o srvido, porém, ele *clona* o repositório completo, *inclui históricos de versões e cada clone* é como um backup completo.
Possibilita o:
* Fluxo de trabalho, 
* Trabalhar de qualquer lugar,
* E trabalhar sem conexão à rede, (servidor)
Caso o servidor "cair" não haverá interferencia.

# Git
É um sistema de controle de versão distribuido (gratuito, leve, código aberto, ramificações e fusões)
### Comandos básicos do Git
| Comando | Ação |
| :---:| :--- |
| `Git clone` | clona o repositório Git existente para um novo repositório |
| `Git commit`| grava alterações no repositório local
| `Git Pull`| "puxa" alterações do repositório remoto para o local |
| `Git push`| "empurra" as alterações do repositório local para o remoto |
| `Git config list`| mostram as alterações das configurações feitas |
| `git init defaultBranch`| altera o nome padrão da Branch |

| Variável de configuração | Ação |
| :---:|:---|
| `git global` | permite alteração no usuário |
| `git system` | referente ao sistema como um todo, abriga todos usuários |
| `git local` | refere a um repositório expecífico (repositório local onde o projeto está guardado)

# GitHub
É a paltaforma de hospedagem do código para o controle de versões com o Git.

**Git  ≠  GitHub**
- Git é um banco de versõesonde ajuda nessa organização do Versionameto de código.
- GitHub é onde os código são hosopedados (servidor)
