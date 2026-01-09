# Introdução ao Git e GitLab

## O que é Git

O **Git** é um software de **controle de versão distribuído (DVCS)**, gratuito e de código aberto, criado por **Linus Torvalds**.  
Ele permite registrar, acompanhar e gerenciar o **histórico de alterações** em um projeto de software.

O Git funciona criando **instantâneos (commits)** das mudanças realizadas no código, o que possibilita:

- Voltar a versões anteriores do projeto  
- Comparar modificações ao longo do tempo  
- Identificar quem realizou cada alteração e quando  

---

## Diferença entre `git add` e `git commit`

### `git add`
- Adiciona arquivos ou alterações da área de trabalho para a **staging area** (área de preparação).
- Permite selecionar exatamente quais mudanças farão parte do próximo commit.

**Analogia:**  
É como escolher quais fotos você quer incluir antes de montar um álbum.

---

### `git commit`
- Salva definitivamente as alterações que estão na staging area.
- Cria um **ponto fixo no histórico do projeto**, acompanhado de uma mensagem descritiva.

**Analogia:**  
É como tirar a foto final e guardá-la no álbum.

---

## O que é um Repositório Remoto

Um **repositório remoto** é uma cópia do seu repositório Git hospedada em um servidor, como:

- GitHub  
- GitLab  
- Bitbucket  

Ele é utilizado para:

- **Backup** do código
- **Colaboração em equipe**
- Envio de alterações (`push`)
- Download de alterações (`pull`)

---

## Papel do GitLab no Ambiente Profissional

O **GitLab** é uma plataforma completa de **DevOps**, que utiliza o Git para hospedar repositórios e oferece um fluxo de trabalho integrado para desenvolvimento de software.

### Principais funcionalidades:

#### Colaboração e Gestão
- Revisão de código via *Merge Requests*
- Controle de acesso e permissões
- Gerenciamento de branches

#### CI/CD
- Automação de testes
- Integração Contínua (CI)
- Entrega Contínua (CD)

#### Gestão de Projetos
- Planejamento de tarefas
- Acompanhamento do progresso
- Gerenciamento do ciclo de vida do desenvolvimento

#### Visibilidade
- Centralização do código e histórico
- Maior transparência
- Aumento da eficiência do time e do projeto
