# INTRODUÇÃO AO DESENVOLVIMENTO E LÓGICA DE PROGRAMAÇÃO

## 1.1	O que é programação

   O objetivo da programação é de desenvolver software para outras pessoas. Desenvolver software é resolver problemas usando programação como ferramenta.
   
   <i>Toda empresa hoje ou é ou ainda não percebeu que é digital</i>.
   
   Então, existe uma necessidade de desenvolver sites, apps e soluções para essas empresas. O programador precisa entender a necessidade de um usuário e transformar essa necessidade em uma aplicação, em um software, em um sistema. 
  
   <strong>O software só é software se ajuda alguém. Caso contrário, só é um amontado de instruções.</strong>
  
   As ferramentas necessárias para desenvolver essas aplicações são: 
  
   <ul>
   <li>linguagens de programação (para conversar no idioma do computador);</li>
   <li>banco de dados (para armazenar a informação);</li>
   <li>WWW (para comunicação);</li>
   <li>apresentação de informação - front-end (identidade visual, interface, interação, intuitivo).</li>
   </ul>
   

## 1.2	Dados do mercado

   Em março de 2021, tínhamos 20 mil vagas de desenvolvimento abertas em SP, desde júniores a arquitetos de sistema. 
   
   <strong>O mercado está muito aquecido e temos uma defasagem em relação à demanda, visto que muitas empresas precisam de soluções digitais.</strong>
   
   O mercado de desenvolvimento de aplicações pode atender empresas tradicionais, que estão migrando as operações para o digital (ex: Itau), e também as empresas que já nasceram digitais (ex: Nubank). 
   
   <i>É possível atender desde micro até as grandes empresas.</i>
   
   Algumas áreas no mercado de programação:
   
   <ul>
   <li>Desenvolvedores,;</li>
   <li>Analistas de infraestrutura;</li>
   <li>Analistas de Requisitos;</li>
   <li>Testadores;</li>
   <li>Profissionais de UI/UX;</li>
   <li>Profissionais de Telecomunicações;</li>
   <li>Profissionais de DevOps.</li>
   </ul>
   
   Também é possível trabalhar com empresas nacionais e até internacionais de forma remota.

## 1.3	Como é a carreira de desenvolvimento

   <strong>Hard skills</strong> (habilidades aprendidas por meio de cursos, treinamentos):
   <ul>
   <li>Back-end: softwares que fazem a manipulação de dados do sistema (ex de ecommerce: selecionar o produto, efetuar o pedido, gravar o endereço na base de dados, enviar o pedido para a equipe de logística);</li>
   <li>Front-end: está relacionado com a interação com o usuário (navegação, interface, apresentação da informação, facilidade de uso, intuitividade para chegar na informação);</li>
   <li>Aplicativos: aplicativos nativos ou não;</li>
   <li>Base de dados: armazenamento e recuperação de informação;</li>
   <li>GIT e versinamento;</li>
   <li>Framework de desenvolvimento ágil.</li>
   </ul>
   
   <strong>Soft skills</strong> (habilidades sociocomportamentais, ligadas às aptidões mentais e à capacidade de lidar com fatores emocionais):
   <ul>
   <li>Trabalhar em grupo: os projetos estão cada vez maiores e com prazos curtos;</li>
   <li>Liderança: para influenciar as equipes;</li>
   </ul>
   
   <strong>Carreira em T</strong> (o profissional tem uma visão generalista de desenvolvimento e se aprofunda em uma área específica):
   <ul>
   <li>Júnior: sabe um pouco de front, back, fez um site simples, não fez integração de sistemas, trabalhou um pouco com GIT e agile;</li>
   <li>Pleno: começa a se envolver em problemas mais complexos e evoluem suas skills técnicas em uma competência;</li>
   </ul>

## 1.4	Linguagens, frameworks e bibliotecas

  <ul>
   <li><strong>Linguagem de programação</strong>: idioma em que eu quero conversar com o computador – ex: Java, PHP, Javascript, C+, Phyton;</li>
   <li><strong>Linguagem de marcação</strong> – ex: HTML;</li>
   <li><strong>Linguagem de estilização</strong> – ex: CSS;</li>
   <li><strong>Bibliotecas</strong>: pequenos trechos de código que eu reaproveito – ex: estrutura de pedidos que eu utilizo no sistema de vendas, de estoques, de relatórios para o gestor / estrutura que utilizo no desktop do site e no mobile);</li>
   <li><strong>Frameworks</strong>: bibliotecas com manual de uso, que agilizam e tornam mais seguro o desenvolvimento  – ex: do front-end (Angular, ReactJs);</li>
  </ul>

## 1.5	Editores de texto
   
  <ul>
   <li>Editores de texto: <strong>Visual Studio Code</strong>;</li>
   <li>IDE (Ambientes Integrados de Desenvolvimento): toda IDE também é um editor de texto, ele já corrige o código em tempo real, melhoria – ex: <strong>Eclipse IDE</strong>;</li>
  </ul>
  
## 1.6	Algoritmos

   <strong>O que é um Algoritmo?</strong>
   <ul>
      <li>Sequência de comandos para transformar uma informação inicial em uma informação final. Ex: calcular o salário líquido de um funcionário da empresa – cria-se um algoritmo que já calcula os impostos que a empresa paga e retira do salário base;</li>
      <li>É como a receita de bolo de fubá da vó, uma sequência ordenada de passos que possibilita que qualquer um consiga fazer o bolo.  Caso mude a ordem de preparo, o bolo não ficará igual.</li>
      <li>Receita do bolo:</li>
          <ol>  
            <li>Em um liquidificador, adicione os ingredientes.
            <li>Bata tudo até a massa ficar lisa e homogênea.
            <li>Despeje a massa em uma forma untada e polvilhada.
            <li>Leve para assar em forno pré-aquecido a 180 °C.
            <li>Depois de 40 minutos, retire o bolo do forno. </li></ol> 
      <li>Exemplo de algoritmo:</li>
            Algoritmo REALIZAR CADASTRO
            var nome: inteiro
            var CPF: inteiro
            var e-mail: inteiro
            Início
            LEIA (nome)
            LEIA (CPF)
            LEIA (e-mail)
            IMPRIMIR (nome)
            IMPRIMIR (CPF)
            IMPRIMIR (e-mail)
            FIM
      <li>O algoritmo precisa respeitar a linguagem de programação para que consiga ser lido.</li> 
   </ul>
     
   <i>Todo algoritmo tem a sequência: ENTRADA -> PROCESSAMENTO -> SAÍDA</i>
   <ul>
   <li>Entrada: tudo que precisamos informar para o algoritmo – informação bruta (ex: ingredientes);</li>
   <li>Processamento: roteiro com a ordem do que será feito – regras do código (ex: modo de preparo);</li>
   <li>Saída: resultado do cálculo – nova informação gerada (ex: bolo).</li></ul>
   
   Vamos usar a ferramenta online para os exercícios de lógica de programação: <strong>Portugol</strong>
   <ul>
   <li>www.portugol-webstudio.cubos.io/ide</li>
   <li>Tudo que é texto será escrito entre aspas “ “.</li>
   <li>A quebra de linha será feita com os caracteres “\n”.</li>
   <li>Teste:</li>
      <ul>
      <li>escreva(“Oi, meu primeiro programa!\n”)</li>
      <li>escreva(“Agora vai!”)</li>
</ul></ul>

## 1.7 Variáveis e Operações


## 1.8 Decisões


## 1.9 Repetições

