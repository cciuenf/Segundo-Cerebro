# 🧠 Segundo Cérebro - Ciência da Computação

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)
![Obsidian](https://img.shields.io/badge/Obsidian-7A1FA2?style=flat&logo=obsidian&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

Repositório colaborativo funcionando como um "segundo cérebro" para estudantes de Ciência da Computação, utilizando o Obsidian para criar e interconectar notas de aula, resumos e materiais de estudo em um material polido e conciso para que outros alunos possam usar como fonte de estudos.

## 📚 Sobre o Projeto

Este repositório contém um Vault do Obsidian compartilhada que funciona como base de conhecimento coletiva para o curso de Ciência da Computação da UENF. Seguimos metodologias específicas para garantir o aprendizado efetivo e o alto desempenho acadêmico.

### 🎯 Objetivos

- 📈 Todas as notas **≥ 8,0**
- 📝 Manter todas as aulas em dia
- 🔄 Aplicação prática do conteúdo

### 🧩 Metodologias

#### "Aula dada, aula estudada" - Prof. Pierluigi Piazzi
Revisamos e estudamos o conteúdo de cada aula no mesmo dia em que é ministrada, reforçando as conexões neurais enquanto a memória está fresca.

#### Técnica Feynman
Agendamos encontros regulares onde cada membro ensina um tópico aos demais, seguindo o princípio de que "você só entende de verdade quando consegue explicar de forma simples".

#### Redes Mentais no Obsidian
Criamos mapas de conhecimento interconectados para cada disciplina, com sub-redes específicas para P1, P2 e P3, ajudando a visualizar como os conceitos se relacionam.

#### 🌐 **Zettelkasten (Sistema de Cartões de Notas)**  
Criamos notas interconectadas para criar um **banco de ideias dinâmico**. Cada conceito ou ideia é registrado de forma atômica (uma ideia por nota) e vinculado a outras notas relevantes, criando uma **rede de conhecimento viva**.  
Caso duas materias tenham tópicos conectados por favor conecte as notas relevantes 

## 🔌 Plugins Utilizados

- **Calendar**: Para agendar e visualizar sessões de estudo e prazos
- **Git**: Para versionamento e sincronização do vault de maneira simplicada e em dispositivos móveis
- **Excalidraw** Para desenho a mão livre e gráficos

## 📂 Estrutura de Pastas

```
Readme.md
Disciplinas/
├── MateriaExemplo/
│   ├── Material/
│   │   ├── Home.MD
│   │   ├── Capitulo1-Cinematica.md
│   ├── PastaDeAnotações/
│   │   ├── AnotaçõesDeAulaArtur.md
│   │   ├── AnotaçõesDeAulaSophia.md
│   ├── Exercícios/
│   │   ├── Trabalhos/
│   │   ├── Listas/
│   │   │   ├── Lista 1/
|   |   |   |   ├── ExplicaçãoDaListaResolvida.md
│   │   |   |   ├── SoluçõesArtur/
│   │   |   |   ├── SoluçõesSophia/
│   │   │   ├── Lista 2/...
│   ├── Duvidas/
│   ├── Resumos/
```

### Material/
Essa pasta deve conter o material polido criado a partir das anotações de aula de todos os participantes da materia, e deve ser validado pelos mesmos que não possui erros, contribuições com erros devem ser negadas e a correção sugerida ao criador da contribuição
para que o mesmo possa aprender com o que errou e quem fez a sugestão treinar explicando o erro.

Deve ser vista como um livro da materia onde Home.md é o indice do livro e os arquivos subsequentes os seus capítulos.

### PastaDeAnotações/
Essa pasta é onde cada aluno participante criar sua própria pasta para manter suas anotações de aula, usando o obsidian como seu caderno pessoal, as anotações aqui feitas não devem permanecer paradas, as mesmas devem ser revisadas pelo aluno que as criou
e integradas na pasta Material/ de maneira polida para ampliar a qualidade do material disponibilizado com mais pontos de vista.

### Exercícios/
Essa pasta possuira sub pastas como Listas/ e Trabalhos/ onde serao contidas as soluções individuais ou em grupo caso aplicável de cada participante, uma pasta especializada deve ser criada para cada aluno/grupo. Ao lado disso devem conter um arquivo de explicação que explica as soluções e metodos utilizados para resolver os problemas.

### Duvidas/
Essa pasta alunos deverao criar arquivos individuais com titulo, a duvida e um unico checkbox no topo do arquivo com o texto "Resolvida" para que seja possivel marcar a duvida como resolvida. Outro participante do grupo ajudara o criador da duvida, e o criador então deve escrever depois do texto da duvida no arquivo uma seção "Resolução" e explicar como resolver sua duvida ele mesmo, para cimentar que entendeu, dando assim mais uma possibilidade de correção e fortificação da explicação atraves de aprovações e feedback pelo github.

### Resumos/
Essa pasta deve conter resumos da materia para momentos especificos, como provas, trabalhos, etc. De preferencia resumos devem ser feitos e validados por mais de 2 alunos participantes da materia caso disponivel.

## 🤝 Como Contribuir

Leia CONTRIBUTING>md

### Configuração Inicial

### Como editar o projeto
1. Faça uma fork do repositório:
   IMG  
2. Clone o repositorio:
   IMG
   IMG
   ```bash
   git clone SEU_LINK_SSH
   ```
3. Abra o vault no Obsidian:
   - Abra o Obsidian
   - Escolha "Abrir pasta como vault"
   - Navegue até a pasta clonada
4. Siga O fluxo de trabalho para fazer edições

### Fluxo de Trabalho

1. Sempre faça `gh repo sync SEU_USUARIO/Segundo-Cerebro` e `git pull` antes de começar a trabalhar (Religiosamente)
2. Crie novas notas seguindo os templates disponíveis ou edite notas existentes
3. Commit e push regularmente:
   ```bash
   git add .
   git commit -m Titulo da Modificação"
   git push
   ```
   Sempre seja descritivo com o titulo, porem o mesmo tem limite de 50 caracteres então caso necessario use uma descrição
   ```bash
   git add .
   git commit -m "Titulo da Modificação" -m "Descrição sem limite de caracteres"
   git push
   ```
4. Sincronize suas mudanças ao repositório principal atraves de uma Pull Request
   IMG
   IMG
   Seja bem descritivo no Titulo e descrição de uma PR com tudo que você contribuiu
   
## 📅 Reuniões

- Poderemos marcar reunioes pessoalmente caso multiplos alunos desejem tirar duvidas, estudar, ou testar seu conhecimento atraves da tecnica feynman de maneira mais envolvida

## ❓ FAQ

**P: Como adicionar uma nova disciplina ao vault?**
R: Copie e cole o template pasta disponivel em `Templates/DisciplinaTemplate/` na pasta Disciplinas/ e altere o nome da pasta para o nome da disciplina e o altere o Home.md de acordo

---

> Provérbios 4:7-8: "A sabedoria é a coisa principal; adquire, pois, a sabedoria; sim, com tudo o que possuis, adquire o conhecimento. Exalta-a, e ela te exaltará"
