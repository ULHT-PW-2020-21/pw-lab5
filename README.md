site com exemplos de layouts
fazer menu que muda os layouts



**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**
 
# Programação Web - Laboratório 5: Website responsivo e dinâmico 

## Pré-requisitos
* Deverá ter feito o [lab4](https://github.com/ULHT-PW-2020-21/pw-lab4)

## Objetivo
* Neste laboratório formatará os conteúdos website criado no Laboratório 4.
* O objetivo deste laboratório é criar um layout responsivo, consoante o tamanho do ecrã do browser.
* Este laboratório deverá ser concluido antes da sua aula prática da semana de 22 de março. Este será avaliado nessa aula. 

## Recomendações
* Leia o enunciado todo com atenção antes de o começar a resolver para entender o que fará.
* Execute com atenção cada passo, certificando-se que implementa todos os detalhes. Contém todos os detalhes para a criação do website. 
* Se tiver alguma dúvida, recorra ao [Moodle](https://secure.grupolusofona.pt/ulht/moodle/course/view.php?id=38119), onde no Programa existem links para os slides de cada tópico, assim cmoo vídeos, contendo todos os conhecimentos que precisa para realizar este laboratório.
lab4).

# 1. Estruturação do repositório de laboratórios
1. Clone  (descarregue uma cópia) o seu repositório no seu computador local da seguinte forma:
    1. abra um processador de comandos (Tecla Windows e escreva `cmd`, ou `Powershell`, ou `git bash`)
    2. escolha a pasta onde quer colocar o repositório (navegando com o comando `cd nome-de-pasta` para entrar numa determinada pasta)
    3. escreva o comando `git clone https://github/seuusername/pw-labs-nomeapelido-numero` (hiperlink do seu repositório, com o seu username do GitHub e nome do repositório).

2. Crie a pasta `lab5`. 

3. Atualize o `index.html` da sua aplicação, incluindo na lista o nome deste laboratório com um link para lab4/index.html.

3. Copie os conteúdos do `lab4` para a pasta `lab5`, que servirão de base para este laboratório.


# 2. Estrutura das páginas

Adicione à estrutura das suas páginas HTML um elemento `aside`, com conteúdo curto e secundário. O conteúdo pode ser comum a todas as páginas e deverá estar depois do elemento `main` e antes do `footer`.

# 3. Layout com Design Responsivo
Crie um layout flúido baseado em CSS Grid, responsivo ao tamanho do ecrã:
1. Configure adequadamente informação sobre o viewport em todas as páginas HMTL. 
2. Usando media queries e CSS Grid, defina layouts responsivos do seu website para smartphone, tablet e desktop. Deverão ser todos diferentes na forma como apresentam os elementos semanticos HTML5 (header, nav, main, aside e footer).

# 4. Efeitos e Animações com keyframes

crie, como submenus da página multimédia
1. a página galeria:
    1. Escolha 4 fotografias diferentes a seu gosto associadas à cidade que escolheu, formatadas com dimensão 300px x 200px. 
    2. Insira na página galeria três cópias de cada, totalizando assim 12 fotografias. Use flexbox para que a disposição das imagens fique responsiva e organizada a seu gosto. 
    3. Em cada grupo de três fotos semelhantes, estilize duas com efeitos e transições CSS a seu gosto.
2. a página animações:
    1. crie duas animações usando keyframes.

# 4. Menu dropdown

1. Para cada um dos menus principais escolha um ícone de um dos repositórios de ícones (Google, Awesome Font ou Bootstrap). 
2. Crie um menu dropdown.


# 9. Submissão

1. Verifique que todos os links do seu website funcionam devidamente.
2. Carregue a sua pasta no seu repositório Github através dos seguintes passos:
    1.  abra o processador de comandos e posicione-se dentro da pasta do seu repositório (`pw-labs-nomeapelido-numero`).
    2.  escreva as seguintes instruções:
        * `git add *`
        * `git commit –m "submissão laboratório 3"`
        * `git push`
3. Sincronize o GitHub com o Heroku tal como fez no [lab1](https://github.com/ULHT-PW-2020-21/pw-lab1). Deverá ir ao Heroku e, em Deploy, fazer deploy branch, de forma a colocar disponível na cloud os novos conteúdos criados. 
4. Verifique que o seu website online funciona corretamente, mostra todas as imagens e os hiperlinks funcionam devidamente.
5. No seguinte [ficheiro](https://drive.google.com/file/d/1kphRYAo78NSxWznBXHqNbPksELqlyloI/view) garanta que esteja:
    * link da sua aplicação Heroku
    * link do seu repositório privado no GitHub
    * adicione os docentes de PW como membros do seu repositório, que têm como usernames no GitHub: luciostuder, logdarkmatter, rfgsantos.

Esperamos que tenha gostado de aplicar os conhecimentos de HTML5 e CSS para criar um layout dinamico e responsivo!
