<!-- markdownlint-disable MD024 -->

# 📅 Cronograma de Mentoria da Cumbuca Dev

- [Semana 2: 18/11 - 24/11](#semana-2-1811---2411)
  - [Objetivo](#objetivo)
  - [Teoria](#teoria)
  - [Atividades](#atividades)
- [Semana 3: 25/11 - 01/12](#semana-3-2511---0112)
  - [Objetivo](#objetivo-1)
  - [Teoria](#teoria-1)
  - [Atividades](#atividades-1)
- [Semana 4: 02/12 - 08/12](#semana-4-0212---0812)
  - [Objetivo](#objetivo-2)
  - [Teoria](#teoria-2)
  - [Atividades](#atividades-2)
- [Semana 5: 09/12 - 15/12](#semana-5-0912---1512)
  - [Objetivo](#objetivo-3)
  - [Teoria](#teoria-3)
  - [Atividades](#atividades-3)

## Semana 2: 18/11 - 24/11

### Objetivo

Explorar qual o papel de um sistema operacional para uma pessoa que utiliza o computador no dia-a-dia, explorando a interface gráfica e como ela se relaciona com a interface via “texto” do terminal.

### Atividades

* Exploração em conjunto em ligação a ser combinada
* Exploração de comandos de terminal com base em UNIX (macOs e Linux)
* Material de suporte a definido após atividade conjunta:
    * [Terminal Mac OS X](https://youtu.be/4traeizb0ww?si=f2ekRgY8BWPEIqjX)
    * [Curso GNU Linux - Aula 12 - Comandos básicos](https://www.youtube.com/watch?v=Yvg7RAhq1Ss)
    * [Manual de comandos do Linux](https://www.freecodecamp.org/portuguese/news/o-manual-de-comandos-do-linux-aprenda-comandos-do-linux-para-iniciantes/) — é uma guia de referência, não precisa ver tudo, mas:
        * vamos usar os 10 primeiros mais ou menos (até `find`)
        * um ou outro além disso (como o `cat`) pode ser útil, mas podemos ver no próximo encontro
        * e tem uns que você já conhece agora (como o `grep` e o `du`)
    * [5 comandos bacanas para o Terminal do macOS](https://youtu.be/s14aFEcyNAE?si=lLGMj-nopJbeFafa)
    * Para você explorar por conta própria, com o `man` que você vai aprender acima: faça teu macOS falar com você com o comando `say` no Terminal

## Semana 3: 25/11 - 01/12

### Objetivo

* Exploração de automações, como fazer as tarefas no terminal serem:
    * menos repetivas
    * mais flexíveis

### Atividades

* Criação e edição de arquivos simples com comandos do Terminal
    * Abrir o programa chamado _TextEdit_ (ou _Editor de Texto_ se o computador estiver em português)
    * No menu de texto que fica no topo da tela, selecionar _Format_ e _Make Plain Text_ (também funciona com o atalho de teclado, pressionando essas três teclas ao mesmo tempo, `Shift`, `Cmd` e `T`)
    * Escrever algum código para testar, por exemplo, `echo "Oi, mundo!"`
    * Salvar o arquivio (no menu de texto que fica no topo da tela, _File_ e _Save…_) como `desafio.sh`
        * O final `.sh` é importante
        * Reparar no diretório onde você está salvado (explore a janela de salvar para encontrar um diretório que você saiba encontrar pelo Termina depois)
    * Teste no Terminal, indo até o diretório onde você salvou o arquivo e digitando o comando `sh desafio.sh` — é esperado que você veja o _Oi, mundo!_ na tela 
* Exercício: baixar o arquivo [`mentoria.zip`](https://www.dropbox.com/scl/fi/o8df9aotu1aqsxxtm7j1h/mentoria.zip?rlkey=9nl57bn366k6dzm8k5uha3yok&dl=0) e escrever um código em um arquivo `desafio.sh` que, quando executado com `sh desafio.sh`:
    * Todas as imagens em um diretório chamado `imagens`
    * Todos os arquivos maiores que 1MB em um diretório chamado `arquivos-grandes`
    * Os demais arquivos devem continuar onde estão
    * Sugestão de comandos a explorar: `du`, `mv`, `ls`, `grep`, `mkdir`
    * Desafio extra:
        * Criar uma versão da automação em que imagens maiores de 1MB vão para o diretório `arquivos-grandes`
        * Criar uma versão da automação em que imagens menores de 1MB vão para o diretório `imagens` e também para o `arquivos-grandes`

## Semana 4: 02/12 - 08/12

### Objetivo

* Ferramentas para facilitar a escrita de código
* Instalação de um editor (VS Code, por exemplo)

## Semana 5: 09/12 - 15/12

### Objetivo

* _Hello, world!_ em Python
* Materiais para o futuro próximo:
    * [Comece a estudar programação por aqui!](https://www.youtube.com/playlist?list=PLb8MLffwd1Z6yrHFL6eSYsidKwnJFByRE)
    * [Introdução ao Git e ao GitHub: colaborando com projetos de código aberto](https://escoladedados.org/tutoriais/introducao-ao-git-e-github-colaborando-com-projetos-de-codigo-aberto/)
    * [Git para programadores iniciantes](https://youtu.be/P9xXbEhqhqA)
    * [15 subáreas da engenharia de software](https://www.youtube.com/watch?v=sw3GGqjp_q0)
    * [Como pedir e receber ajuda na internet](https://escoladedados.org/tutoriais/como-pedir-e-receber-ajuda-na-internet/)
    * [Pense Python](https://penseallen.github.io/PensePython2e/)
