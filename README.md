\# 📚 Resumo — Versionamento de Código com Git e GitHub



Este repositório contém um resumo dos principais conceitos e comandos que aprendi no módulo de \*\*Versionamento de Código com Git e GitHub\*\*, que faz parte do curso \*\*CI\&T – Backend com Java \& AWS\*\*.



O objetivo é registrar meu aprendizado e usar este material como referência nos meus próximos projetos em Java.



---



\## 🧠 O que é Versionamento de Código?



É a prática de \*\*rastrear e gerenciar alterações\*\* em arquivos ao longo do tempo, permitindo:

\- acompanhar o histórico do projeto;

\- colaborar em equipe;

\- reverter erros;

\- organizar diferentes versões do código.



Isso é feito através de \*\*Sistemas de Controle de Versão (VCS)\*\*, como o Git.



---



\## 🗂️ Sistemas de Controle de Versão (VCS)



\### 🔹 Centralizado (CVCS)

\- Um servidor central com o repositório.

\- Depende de conexão constante.

\- Se o servidor falhar, o histórico pode ser perdido.



\### 🔹 Distribuído (DVCS)

\- Cada desenvolvedor tem uma cópia completa do repositório.

\- Permite trabalhar offline.

\- Cada clone funciona como um backup.

\- Exemplo: \*\*Git\*\*.



---



\## 🧰 O que é Git?



Git é um \*\*Sistema de Controle de Versão Distribuído (DVCS)\*\*:

\- gratuito e open source;

\- rápido e leve;

\- suporta branches e merges de forma eficiente;

\- muito usado em projetos profissionais.



---



\## ⚙️ Fluxo Básico com Git



```bash

git clone   # clonar um repositório remoto

git status  # verificar estado dos arquivos

git add     # adicionar arquivos à staging area

git commit  # salvar uma nova versão

git pull    # baixar atualizações do remoto

git push    # enviar commits para o remoto

```



\## 📂 Criando um Repositório Local



```bash

mkdir repo-local

cd repo-local

git init

```

\## 📝 Salvando Alterações no Repositório Local

```bash

git status

git add README.md

git commit -m "commit inicial"

git log

```



\## 🚫 Ignorando Arquivos com .gitignore

```bash

echo resumo/ > .gitignore

```

\## 🔄 Desfazendo Alterações

Restaurar arquivo modificado:

```bash

git restore arquivo.txt

```

Remover o controle Git da pasta:

```bash

rm -rf .git

```



\## ✏️ Alterando o Último Commit

```bash

git commit --amend -m "novo nome"

```



\## ⏪ Resetando Commits

```bash

git reset --soft     # volta commit e mantém na área de preparação 

git reset --mixed    # volta para área de trabalho

git reset --hard     # apaga tudo (cuidado!)

git reflog           # histórico de referências

```

\## 🌐 Enviando e Baixando do Repositório Remoto

```bash

git push -u origin main

git pul

```



\## 🌿 Trabalhando com Branches

\- Branches permitem desenvolver novas funcionalidades sem afetar o código principal.

\- Criar e mudar para uma branch:

```bash

git checkout -b nova-branch

```

\- Voltar para main

```bash

git checkout main

```

\- Listar branches e seus últimos commits

```bash

git branch -v

```

\- Mesclar

&nbsp;```bash

git merge nova-branch

```

\- Excluir

&nbsp;```bash

git branch -d nova-branch

```

\## 🎯 Objetivo

\- Aplicar Git e GitHub em todos os meus projetos em Java, organizando melhor meu código, histórico de alterações e colaboração em equipe.

\- Este repositório faz parte da minha jornada no curso CI\&T – Backend com Java \& AWS.

