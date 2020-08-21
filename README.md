<h1 align="center">
    <img alt="Launchbase" src="https://i.ibb.co/d4W2x4g/trybe.png" width="400px" />
</h1>

<h3 align="center">
  Exercício 3-1: HTML & CSS - Estruturas de página - Concluído o/ o/ o/
</h3>

<blockquote align="center">“Quanto mais você estuda, mais aprende e se aproxima de realizar seu sonhos!”</blockquote>

<h1></h1>

<!-- <div>
  <img src="https://i.ibb.co/S59Z6Hg/Desafio2-2.gif" alt="demo-web" height="425">
</div> -->

<p align="center">

  <a href="https://www.linkedin.com/in/eduardosouzaprogrammer/" target="_blank">
    <img alt="Made by Eduardo Souza" src="https://img.shields.io/badge/made%20by-Edu%20Souza-%23F8952D">
  </a>&nbsp;

 <a href="https://edusouza-programmer.github.io/" target="_blank">
<img alt="Github page site " src="https://img.shields.io/badge/Github%20page-Site-orange">
</a>&nbsp;

  <a href="LICENSE" >
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23F8952D">
  </a>

</p>

<p align="center">
  <a href="#rocket-sobre-o-exercicio">Sobre o Exercício</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#calendar-entrega">Entrega</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :rocket: Sobre o Exercício

Vamos continuar com a criação do seu Portfólio Web! Agora é hora de estilizar tudo que você aprendeu!

Com este exercício, você será capaz de:

-   Estilizar seu Portfólio Web usando todo o conhecimento que você construiu hoje;

-   Atualizar seu Portfólio Web no GitHub Pages.

### Estilizando seu Portfólio Web!

Antes de começar, você deve seguir as instruções abaixo e fazer o setup para o exercício de hoje:

1. Entre no diretório que você criou no dia anterior;
2. Adicione a tag <style></style>, que é onde você vai colocar suas alterações;
3. Procure uma palheta de cores com que você mais se identifica e que você pode gerar nesse site.

### Requisitos

Seu Portfólio Web deve ser estilizado usando as informações a seguir:

-   Defina fontes diferentes para o seu nome e para a descrição que você criou;

-   Defina uma cor base de background do seu Portfólio Web;

-   Altere o estilo das tags que você usou para destacar algumas informações, como sua nacionalidade e a cidade/estado onde mora;

-   Coloque tamanhos diferentes para os elementos da lista de habilidades que você criou. Lembre-se de usar classes para cada um dos elementos;

## Questões sobre os desafios [Meus códigos]

### Minha página web estilizada o/

<p>Link para meu portfólio web: <a href="https://edusouza-programmer.github.io/" target="_blank">página</a>.</p>

#### Código HTML:

    <!DOCTYPE html>
    <html lang="pt">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Eduardo Souza</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <header>
            <div class="links">
                <a href="#">Sobre</a>
                <a href="/Exercícios_HTML/projeto_Livro-de-receitas.html" target="_blank">Projeto</a>
            </div>
        </header>
        <main>
            <div id="wrapper">
                <a href="https://avatars0.githubusercontent.com/u/23068430?s=400&u=fdf94a10158b5f9e4a694c98c48c2dd192eba4e0&v=4"
                    target="_blank">
                    <img src="https://avatars0.githubusercontent.com/u/23068430?s=400&u=fdf94a10158b5f9e4a694c98c48c2dd192eba4e0&v=4"
                    alt="A foto de um acar muito gente fina chamando:Eduardo Souza">
                </a>
                <h1>Eduardo Souza</h1>
                <h2>Estudante turma 7 - Trybe</h2>
                <p>Olá tudo bem?! Sou web developer júnior, brasileiro, morando no estado do <em>Rio de
                    janeiro</em>, estou focado nos estudos para alcançar os objetivos da profissão, apredendo com a
                    <a href="https://www.betrybe.com/" target="_blank">Trybe</a>.
                </p>
            </div>
            <div class="skill">
                <h2>Habilidades (soft skills)</h2>
                <ul>
                    <li><strong>Perseverante</strong></li>
                    <li>Proatividade</li>
                    <li><strong>Comunicação</strong></li>
                    <li>Resiliência</li>
                    <li><em>Ambição</em></li>
                    <li><strong>Adaptabilidade</strong></li>
                </ul>
            </div>
        </main>
        <section class="social">
            <div class="links">
                <a href="https://github.com/EduSouza-programmer?tab=repositories" target="_blank">GitHub</a>
                <a href="https://www.facebook.com/profile.php?id=100003755834780" target="_blank">Facebook</a>
                <a href="https://www.linkedin.com/in/eduardosouzaprogrammer/" target="_blank">Linkedin</a>
            </div>
        </section>
        <footer class="footer">
            <div class="footer-conteiner">
                <p>Feito com &hearts; por <em><a href="https://www.linkedin.com/in/eduardosouzaprogrammer/">
                Edu Souza</a></em></p>
            </div>
        </footer>
    </body>
    </html>

#### Código CSS:

    @import "https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@300;400;700&display=swap";

    :root {
        --color-green: #50fa7b;
        --color-green-hover: #248d43;
        --color-rocket: #7159c1
    }

    * {
        margin: 0;
        padding: 0;
        border: 0;
    }

    body {


        color: #f1eeee;
        /* background-color: #282a36; */
        font-family: 'Source Sans Pro', sans-serif;
        background-color: #2c2d3b;
        background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100%25' height='100%25' viewBox='0 0 1600 800'%3E%3Cg stroke='%2313141a' stroke-width='66.7' stroke-opacity='0.05' %3E%3Ccircle fill='%232c2d3b' cx='0' cy='0' r='1800'/%3E%3Ccircle fill='%232a2b39' cx='0' cy='0' r='1700'/%3E%3Ccircle fill='%23282a36' cx='0' cy='0' r='1600'/%3E%3Ccircle fill='%23272834' cx='0' cy='0' r='1500'/%3E%3Ccircle fill='%23252631' cx='0' cy='0' r='1400'/%3E%3Ccircle fill='%2323252f' cx='0' cy='0' r='1300'/%3E%3Ccircle fill='%2321232d' cx='0' cy='0' r='1200'/%3E%3Ccircle fill='%2320212a' cx='0' cy='0' r='1100'/%3E%3Ccircle fill='%231e2028' cx='0' cy='0' r='1000'/%3E%3Ccircle fill='%231c1e26' cx='0' cy='0' r='900'/%3E%3Ccircle fill='%231b1c24' cx='0' cy='0' r='800'/%3E%3Ccircle fill='%23191b21' cx='0' cy='0' r='700'/%3E%3Ccircle fill='%2318191f' cx='0' cy='0' r='600'/%3E%3Ccircle fill='%2316171d' cx='0' cy='0' r='500'/%3E%3Ccircle fill='%2315161b' cx='0' cy='0' r='400'/%3E%3Ccircle fill='%23131419' cx='0' cy='0' r='300'/%3E%3Ccircle fill='%23111216' cx='0' cy='0' r='200'/%3E%3Ccircle fill='%230f1014' cx='0' cy='0' r='100'/%3E%3C/g%3E%3C/svg%3E");
        background-attachment: fixed;
        background-size: cover;

    }

    header {

        border-bottom: 1px solid #333333;
        background-color: #0000003f;
        padding: 25px 0;
    }

    .links {

        text-align: center;

    }

    .links a {
        color: #fff;
        font-weight: bold;
        font-size: 21px;
        line-height: 28px;
        margin: 0 15px;

        text-decoration: none;

    }

    .links a:hover {
        color: var(--color-green);
        transition: color 500ms;
        text-decoration: underline;
    }

    #wrapper {

        text-align: center;
        padding: 60px;

    }

    #wrapper img {

        border-radius: 50%;
        border: 5px solid var(--color-green);
        width: 200px;
        height: 200px;
        transition: border-color 500ms;


    }

    #wrapper img:hover {
        border-color: var(--color-green-hover);
        transition: border-color 500ms;
    }

    #wrapper h1 {

        margin-top: 15px;
        font-size: 48px;
        line-height: 52px;
        font-weight: bold;
    }

    #wrapper h2 {
        font-size: 24px;
        font-weight: normal;
        line-height: 34px;
        margin-top: 8px;
        opacity: 0.9;
    }

    #wrapper p {
        font-size: 21px;
        line-height: 34px;
        max-width: 600px;
        margin: 15px auto 0;
        font-weight: lighter;

    }

    #wrapper p a {
        color: var(--color-green);
    }

    #wrapper p a:hover {
        color: var(--color-green-hover);
        transition: color 500ms;

    }

    .social {
        padding: 60px 0;
    }

    .skill {

        text-align: center;

    }

    .skill ul {
        margin-top: 10px;
    }

    .skill li {
        text-emphasis: none;
    }

    .footer {
        border-top: 1px solid #333333;
        background-color: #00000060;
        padding: 16px;
    }

    .footer-conteiner {
        text-align: center;
    }

    .footer-conteiner a {
        text-decoration: none;
        color: #50fa7b;
    }

### Adicionar imagens

3. Se você pudesse fazer a viagem perfeita, para onde você iria? Que animais você veria? Que comida você comeria? Adicione imagens à página web após cada tag de parágrafo para compartilhar sua viagem perfeita com o mundo.

#### Resposta:

    <!DOCTYPE HTML>
    <html>
        <head>
            <title>Challenge: A picture-perfect trip</title>
            <meta charset="utf-8">
        </head>
        <body>

            <h2>Desafio: Uma viagem perfeita</h2>

            <h1>The perfect trip</h1>

            <img src="https://www.kasandbox.org/programming-images/landscapes/beach-in-hawaii.png" alt="Uma ilha maravilhosa, com montanhas e aguas claras" width="400px">

            <p>I would see scenes like...</p>

            <img src="https://www.kasandbox.org/programming-images/landscapes/beach-sunset.png" alt="O por do sol maravilhoso" width="400">

            <p>And animals like...</p>

            <img src="https://www.kasandbox.org/programming-images/animals/butterfly_monarch.png" alt="Borboleta com cores lindas" width="400px">

            <p>And eat food like...</p>
            <img src="https://www.kasandbox.org/programming-images/food/sushi.png" alt="Sushi deliciosos" width="400px">

        </body>
    </html>

### Marque o texto

4. Criamos essa página com as palavras de "Você pode aprender qualquer coisa", um vídeo feito pela Khan Academy. Usando as tags <strong> e <em> que você acabou de aprender, marque o texto para mostrar o que você acha deve ser enfatizado e destacado.

#### Resposta:

    <!DOCTYPE HTML>
    <html>
        <head>
            <title>Challenge: You can learn text tags</title>
            <meta charset="utf-8">
        </head>
        <body>
            <p>
            Nobody’s <em>born</em> smart. We all start at 0. Can’t talk, can’t walk, certainly can’t do algebra.<br>
            Adding, reading, writing, riding a bike. Nobody’s good at anything at first.<br>
            There was a time when Einstein couldn’t count to 10.<br>
            And Shakespeare had to learn his ABCs just like the rest of us.<br>
            <strong>Thankfully, we are born to learn</strong>.<br>
            Slowly. Surely. You stumble, slip, crawl, fall and fail and fall.<br>
            Frustrating. Confusing. Trying. Struggling.<br>
            Until one day, you walk.<br>
            One foot in front of the other. One idea on top of the next.<br>
            Each wrong answer making your brain a little bit stronger.<br>
            Failing is just another word for growing. And you keep going.<br>
            This. is. <em>learning</em>.<br>
            It’s not that you don’t get it. <br>
            You just don’t get it, yet.
            <strong>Because the most beautiful</strong>, complex concepts in the whole universe<br>
            are built on basic ideas that anyone, anywhere can understand.<br>
            Whoever you are, wherever you are.<br>
            </p>
            <p>
            You only have to know one thing:<br>
            You can learn anything.
            </p>
        </body>
    </html>

### Adicione links internos

5. Essa é uma longa página web que descreve cangurus, e cada título de seção tem um atributo id. Descubra quais são esses atributos id, e então carregue os atributos href dos links na parte superior para que eles apontem para a seção apropriada.

#### Resposta:

    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <title>Challenge: Jump around</title>
        </head>
        <body>

        <h1 id="kangaroos">Kangaroos</h1>

        <p>Jump to sections:
            <a href="#locomotion">Locomotion</a>,
            <a href="#diet">Diet</a>
        </p>
        <p>The <strong>kangaroo</strong> is a marsupial from the family Macropodidae (macropods, meaning 'large foot'). In common use the term is used to describe the largest species from this family, especially those of the genus Macropus, red kangaroo, antilopine kangaroo, eastern grey kangaroo and western grey kangaroo. Kangaroos are endemic to Australia, and one genus, the tree-kangaroo, is also found in Papua New Guinea.</p>

        <p>Kangaroos have large, powerful hind legs, large feet adapted for leaping, a long muscular tail for balance, and a small head. Like most marsupials, female kangaroos have a pouch called a marsupium in which joeys complete postnatal development.</p>

        <p>Larger kangaroos have adapted much better than smaller macropods to land clearing for pastoral agriculture and habitat changes brought to the Australian landscape by humans. Many of the smaller species are rare and endangered, whilst the larger kangaroos are relatively plentiful.</p>


        <h3 id="locomotion">Locomotion</h3>

        <p>A Tasmanian forester (eastern grey) kangaroo in motion.

    Kangaroos are the only large animals to use hopping as a means of locomotion. The comfortable hopping speed for a red kangaroo is about 20–25 km/h (13–16 mph), but speeds of up to 70 km/h (44 mph) can be attained over short distances, while it can sustain a speed of 40 km/h (25 mph) for nearly 2 km (1.2 mi). This fast and energy-efficient method of travel has evolved because of the need to regularly cover large distances in search of food and water, rather than the need to escape predators. At slow speeds, it employs pentapedal locomotion, using its tail to form a tripod with its two forelimbs while bringing its hind feet forward. Kangaroos are adept swimmers, and often flee into waterways if threatened by a predator. If pursued into the water, a kangaroo may use its forepaws to hold the predator underwater so as to drown it.</p>

        <h3 id="diet">Diet</h3>

        <p>Kangaroos have chambered stomachs similar to those of cattle and sheep. They regurgitate the vegetation they have eaten, chew it as cud, and then swallow it again for final digestion. Different species of kangaroos have different diets, although all are strict herbivores. The eastern grey kangaroo is predominantly a grazer, eating a wide variety of grasses, whereas some other species (e.g. the red kangaroo) include significant amounts of shrubs in their diets. The smaller species of kangaroos also consume hypogeal fungi. Many species are nocturnal, and crepuscular, usually spending the days resting in shade, and the cool evenings, nights and mornings moving about and feeding.</p>

        <p>Because of its grazing habits, the kangaroo has developed specialized teeth. Its incisors are able to crop grass close to the ground, and its molars chop and grind the grass. Since the two sides of the lower jaw are not joined together, the lower incisors are farther apart, giving the kangaroo a wider bite. The silica in grass is abrasive, so kangaroo molars move forward as they are ground down, and eventually fall out, replaced by new teeth that grow in the back. This process is known as polyphyodonty and amongst other mammals, only occurs in elephants and manatees.</p>

        <p>
        <a href="#kangaroos">kangaroos</a> |
        <a href="http://en.wikipedia.org/wiki/Kangaroo">Read more on Wikipedia</a>
        </p>

        </body>

    </html>

    ### Projeto final

    6.  Crie uma página web com suas receitas favoritas! O livro de receitas deve ter uma tabela de conteúdos com links para cada receita abaixo, usando links internos. Cada receita deve ter uma tabela com os ingredientes, uma lista de detalhes, e uma lista e/ou parágrafos dos passos necessários. Se você usar receitas da internet, lembre-se de adicionar um link para o site.

    #### Resposta:

    <!DOCTYPE html>
    <html>
        <head>
            <title>Projeto: livro de receitas</title>
            <meta charset="utf-8">
            <style>
            </style>
        </head>
        <body>

            <h1>Livro de receitas do Edu</h1>
            <p></p>

            <h2>Sumário</h2>

            <ol>
                <li><a href="#recipe-1">Bolo de chocolate</a></li>
                <li><a href="#recipe-2">Pão italiano</a></li>
                <li><a href="#recipe-3">Trança de mini hot dogs</a></li>
            </ol>

            <p>Olá tudo bem?!Eu sou o Edu ^^, estou práticando meus conhecimentos em HTML, nesse exerçício maravilhoso.</p>

            <h2 id="recipe-1">Bolo de chocolate</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/Sachertorte_DSC03027.JPG" alt="Delicioso bolo de chocolate" width="300">
            <ul>
                <li>Tempo: 45min</li>
                <li>Serve: 7 (pessoas)</li>
            </ul>
            <h3>Você vai precisar de:</h3>

            <table>
                <thead>
                    <tr>
                        <th>Quantidades</th>
                        <th>Ingredientes</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>2 xíc.</td>
                        <td>de farinha de trigo</td>
                    </tr>
                    <tr>
                        <td>1 colh.(sopa)</td>
                        <td>de fermento em pó</td>
                    </tr>
                    <tr>
                        <td>1/2 xíc.</td>
                        <td>cacau em pó 32%</td>
                    </tr>
                    <tr>
                        <td>1/2 xíc.</td>
                        <td>de açucar mascavo</td>
                    </tr>
                    <tr>
                        <td>1 xíc.</td>
                        <td>de água (fervida)</td>
                    </tr>
                    <tr>
                        <td>1 xíc.</td>
                        <td>de açucar</td>
                    </tr>
                    <tr>
                        <td>3</td>
                        <td>ovos</td>
                    </tr>
                    <tr>
                        <td>1 xíc.</td>
                        <td>de manteiga (temperatura ambiente)</td>
                    </tr>
                    <tr>
                        <td>1 colh.</td>
                        <td>essência de baunilha</td>
                    </tr>
                </tbody>
            </table>
            <h3>Para Cobertura:</h3>
            <table>
                <thead>
                    <tr>
                        <th>Quantidade</th>
                        <th>Ingredientes</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>4 colh.(sopa)</td>
                        <td>de leite</td>
                    </tr>
                    <tr>
                        <td>1 colh.(sopa)</td>
                        <td>de manteiga</td>
                    </tr>
                    <tr>
                        <td>4 colh.(sopa)</td>
                        <td>de cacau em pó 50%</td>
                    </tr>
                    <tr>
                        <td>2 colh.(sopa)</td>
                        <td>de açúcar mascavo</td>
                    </tr>
                </tbody>
            </table>

            <p><strong>Preparo:</strong><br><br>Comece misturando o chocolate em pó 32% com o açúcar mascavo e a água fervendo. Quando estiver homogêneo, reserve.<br><br>
    Na batedeira, coloque a manteiga com o açúcar e bata até virar um creme branco. Depois, adicione a essência de baunilha, misture um pouco e adicione os ovos um a um, misture um pouco mais. Reserve.<br><br>
    Em outra vasilha, misture a farinha de trigo peneirada com o fermento em pó. Agora vc vai misturar as três vasilhas diferentes. Coloque um pouco da primeira vasilha (chocolate com água e açúcar), um pouco da segunda (a da manteiga e essência de baunilha) e a terceira (farinha e fermento).<br><br>
    Misture suavemente e vá acrescentando as vasilhas de pouco em pouco até acabar tudo. Coloque em uma forma untada em um forno pré aquecido em 180 graus por 40 minutos (faça o teste do palitinho pra ver se tá bom). Misture os ingredientes da cobertura tudo em uma panela até começar a ferver, sempre misturando. Quando ferver, desligue do fogo e despeje sobre o bolo já pronto.<br>
    </p>

        <p><em>Fonte:<a target="_blank"href="https://www.fleischmann.com.br/">Para mais receitas deliciosas</a></em></p>


        <h2 id="recipe-2">Pão italiano</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/1/11/Italian_Sandwich.jpeg" alt="Delicioso bolo de chocolate" width="300">
    <ul>
        <li>Tempo: 50min</li>
        <li>Serve: 4 (pessoas)</li>
    </ul>
    <h3>Você vai precisar de:</h3>

    <table>
        <thead>
            <tr>
                <th>Quantidades</th>
                <th>Ingredientes</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1 sachê</td>
                <td> de pão certo fleischmann(10g)</td>
            </tr>
                <tr>
                <td>1 sachê</td>
                <td>de fermento biológico seco</td>
            </tr>
                <tr>
                <td>7 e 1/4 xíc.(chá)</td>
                <td>de farinha de trigo(1kg)</td>
            </tr>
                <tr>
                <td>2 colheres(sopa)</td>
                <td>de chá de sal</td>
            </tr>
                <tr>
                <td>450 ml</td>
                <td>de água morna</td>
            </tr>
        </tbody>
    </table>

    <p><strong>Preparo:</strong><br><br>Comece juntando toda a farinha de trigo com o Pão Certo.<br><br>
    Você fará uma primeira fermentação: junte 150ml de água morna, retire ¾ de xicara (chá) da mistura de farinha de trigo com pão certo (120 g) e 1 sachê de fermento biológico seco (10 g). Misture e deixe em uma tigela coberta com filme plástico até dobrar de tamanho.<br><br>
    Quando essa primeira fermentação estiver pronta (ou seja, dobrou de tamanho), junte ao restante da mistura de farinha com pão certo, com o sal e a agua restante. Sove até misturar todos os ingredientes e deixe descansando por 20 minutos em um refratário coberto com filme plástico.<br><br>
    Após o descanso, sove por mais 10 minutos ou até que a massa fique lisa e uniforme. Dica: se ela estiver pegajosa, acrescente, aos poucos, mais farinha.<br><br>
    olte a massa para o refratário e deixe descansar até que dobre de tamanho novamente (cerca de duas horas).

    Massa fermentada, molde no formato que você quiser e espere duplicar de tamanho mais uma vez.

    Pré-aqueça o forno a 250ª C, coloque na grade de baixo, uma assadeira com água fervente de 5 a 10 minutos antes de colocar o pão na grade superior (tempo suficiente para aquecer o forno e umedecer).<br><br>
    Pão moldado e fermento?

    Antes de colocar o pão no forno, dê aquela pincelada com água morna e corte um “x” com uma faca bem afiada.

    Leve ao forno e deixe assar por 10 minutos na temperatura de 250ª C,

    Passados os 10 minutos iniciais de Pão no forno, diminua a temperatura para 200°C e retire a assadeira com água e asse até ficar bem dourado! (cerca de 30 minutinhos).<br><br>

    </p>

    <p><em>Fonte:<a target="_blank" href="https://www.fleischmann.com.br/">Para mais receitas deliciosas</a></em></p>

        <h2 id="recipe-3">Trança de mini hot dogs</h2>
        <img src="https://upload.wikimedia.org/wikipedia/pt/thumb/0/0b/Sausage_Party_p%C3%B4ster.jpg/240px-Sausage_Party_p%C3%B4ster.jpg" alt="Enroladinhos de salsicha" width="300" height="300">

        <ul>
            <li>Tempo: 30 min</li>
            <li>Serve: 5 (pessoas)</li>
        </ul>
        <h3>Você vai precisar de:</h3>
        <table>
            <thead>
                <tr>
                    <th>Quantidades</th>
                    <th>Ingredientes</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>1 pacote</td>
                    <td>de mistura para pão caseiro</td>
                </tr>
                <tr>
                    <td>1 pacote</td>
                    <td>de salsicha para hot dogs</td>
                </tr>
                <tr>
                    <td>500 ml</td>
                    <td>leite</td>
                </tr>
                <tr>
                    <td>4</td>
                    <td>gemas</td>
                </tr>
            </tbody>
        </table>

        <p><strong>Preparo:</strong><br><br>

    Para iniciar a receita, prepare a massa conforme as instruções da embalagem, só que trocando a água por leite.<br><br>
    Assim que ela crescer, divida ao meio. Abra metade da massa com o rolo de macarrão em um retângulo que caibam 3 salsichas enfileiradas (uns 30 cm) e que tenha, mais ou menos, 0.5 cm de espessura.

    Coloque as salsichas, dobre a massa e aperte bem para selar. Corte o excesso.<br><br>
    Agora, com uma faca afiada, corte a parte de cima da massa e a salsicha enrolada, sem cortar a base dela.

    Faça cortes, de ponta a ponta, com espaços de 0.5 cm entre eles.

    O segredo está aqui: dobre as rodelas de salsicha, intercalando a direção (direita e esquerda), para que fiquem trançadas.<br><br>
    Repita o processo com a outra metade da massa.

    Quase lá: espere a massa crescer, pincele com gema e asse lindamente até dourar.

    Quer uma sugestáo deliciosa? Experimente servir com vários acompanhamentos, como chili, guacamole, purê de batata, mostarda e ketchup.<br><br>

    </p>

        <p><em>Fonte:<a target="_blank" href="https://www.fleischmann.com.br/">Para mais receitas deliciosas</a></em></p>
        </body>

    </html>

## Licença

Este projeto está licenciado sob a Licença MIT - consulte [LICENSE](https://opensource.org/licenses/MIT) para maiores detalhes.
