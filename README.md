site com exemplos de layouts
fazer menu que muda os layouts



**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**
 
# Programação Web - Laboratório 5: Website responsivo e dinâmico 

## Pré-requisitos
* Deverá ter feito o [lab4](https://github.com/ULHT-PW-2020-21/pw-lab4)
* Deverá ter visto o video e slides sobre transformações e animações CSS, disponivel no Educast e Moodle respetivamente 

## Objetivo
* Neste laboratório formatará os conteúdos website criado no Laboratório 4.
* O objetivo deste laboratório é aplicar os conhecimentos adquiridos esta semana na aula teórica, criando um layout responsivo, consoante o tamanho do ecrã do browser.
* Este laboratório deverá ser concluido antes da sua aula prática da semana de 22 de março. Este será avaliado nessa aula. 

## Recomendações
* Leia o enunciado todo com atenção antes de o começar a resolver para entender o que fará.
* Execute com atenção cada passo, certificando-se que implementa todos os detalhes. Contém todos os detalhes para a criação do website. 
* Se tiver alguma dúvida, recorra ao [Moodle](https://secure.grupolusofona.pt/ulht/moodle/course/view.php?id=38119), onde no Programa existem links para os slides de cada tópico, assim como vídeos, contendo todos os conhecimentos que precisa para realizar este laboratório.

# 1. Estruturação do repositório de laboratórios
1. Clone o seu repositório no seu computador local da seguinte forma:
    1. abra um processador de comandos (Tecla Windows e escreva `cmd`, ou `Powershell`, ou `git bash`)
    2. escolha a pasta onde quer colocar o repositório (navegando com o comando `cd nome-de-pasta` para entrar numa determinada pasta)
    3. escreva o comando `git clone https://github/seuusername/pw-labs-nomeapelido-numero` (hiperlink do seu repositório, com o seu username do GitHub e nome do repositório).

2. Crie a pasta `lab5`. 

3. Atualize o `index.html` da sua aplicação, incluindo na lista o nome deste laboratório com um link para lab4/index.html.

3. Copie os conteúdos do `lab4` para a pasta `lab5`, que servirão de base para este laboratório.


# 2. Estrutura das páginas

Adicione à estrutura das suas páginas HTML dois elementos `aside`, com conteúdo curto e secundário. Um pode ser com algumas fotografias pequenas, e outro com 2-3 frases. O conteúdo será comum a todas as páginas e, no HTML, poderão estar depois do elemento `main` e antes do `footer`.

# 3. Layout com Design Responsivo
1. Conheça os layouts básicos [1](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Common_web_layouts) 
2. Veja alguns princípios de como criar um layout balanceado [2](https://www.creativebloq.com/netmag/create-balanced-page-layouts-7-pro-tips-121310009).
3. O Webdesign está em grande evolução e é uma área diferente da programação Web. Conheça as novas tendências [3](https://en.99designs.pt/blog/trends/web-design-trends/). São complexas e requerem experiência, mas talvez o inspire nalguma ideia mais simples e implementável.
4. Aplique as técnicas de CSS Grid e media queries para definir de forma imaginativa mas aplicando alguns dos princípios que leu, layouts responsivos do seu website para smartphone, tablet e desktop. Deverão ser todos diferentes na forma como apresentam os elementos semanticos HTML5 que tem atualmente:`header`, `nav`, `main`, `aside`, `aside` e `footer`. Explore de forma imaginativa formas de os apresentar.
7. Configure adequadamente informação sobre o viewport e box-sizing em todas as páginas HMTL. 
8. Use flexbox para posicionar os elementos do seu menu que agora deverão ser: Introdução, Localização, Multimédia, Informações, Quizz, Comentários, HTML5 & CSS, Home. Organize-os, recorrendo a espaços em branco, por forma a que fiquem evidentes diferentes grupos de elementos. Por exemplo: 4 (Introdução, Localização, Multimédia, Informações, Quizz) + 3 (quizz, comentarios e HTML&CSS) + 1 (Home). 

# 4. Efeitos e Animações com keyframes

Na página multimédia crie um contentor com uma galeria de fotografias:
    1. Escolha 4 fotografias diferentes a seu gosto associadas à cidade que escolheu, formatadas com dimensão 300px x 200px. 
    2. Insira na página galeria três cópias de cada, totalizando assim 12 fotografias. Use flexbox para que a disposição das imagens fique responsiva e organizada a seu gosto. 
    3. Em cada grupo de três fotos semelhantes, estilize duas com efeitos e transições CSS a seu gosto diferentes.
Crie igualmente na página de entrada uma animação usando keyframes.

# 5. Página HTML e CSS
Atualize os conteúdos desta página, reportando as propriedades que utilizou neste laboratório. Divida os conteúdos em diferentes contextos.

# 6. Submissão

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

Esperamos que tenha gostado de aplicar os conhecimentos de HTML5 e CSS para criar layouts dinâmicos e responsivos!
