### CAPITULO 2 - USE NOMES QUE REVELEM SEU PROPÓSITO
#
<p align="justify">O autor do livro defende que dar bons nomes para variaveis, funções, diretórios leva-se um tempo maior no presente 
mas que esse tempo é ganho em futuras manutenções. O autor alega a pratica de alterar os nomes sempre que encontrado um melhor do que o atual
e que dessa maneira qualquer desenvolvedor quando se deparar com o trecho do código será grato, porque esse pequeno detalhe contribui para o
entendimento do mesmo.<p>
<p align="justify">Na minha pouca experiência como estudante, desenvolvedor e analista me deparei com códigos que além de sujos tinham variaveis confusas
e sendo iniciante é desafiador, alguns aprendem a regra de negócio através do código debugando e vendo os caminhos que é percorrido 
depois de uma ação. Quando nos atentamos a esses pequenos detalhes como os nomes pensamos no futuro em varios sentidos e na qualidade da aplicação.</p>

<p align="justify">O autor da dicas e exemplos. Um nome de função, variavel ou classe deve responder algumas questões, tais como: </p>
- Porque existe? <br>
- Como é usado? <br>
- O que faz? <br><br>

<p align="justify">Apenas um nome é capaz de responder as questões acima. Um nome que requer comentario não revela seu propósito.</p>

``` bash
int d;
```

<p align="justify">O nome d não nos revela nada, não responde a nenhuma das questões colocadas acima, seria necessário um comentario, mas temos que evitar.</p>

``` bash
int tempoDecorridoEmDias; 
int tempo_decorrido_em_dias;
```
<p align="justify">Os nomes acima já dão um entendimento legal sobre do que se trata, mas ainda fica algumas duvidas como, que tempo é este? Então podemos melhorar</p>

``` bash
int horasDecorridasEmDias; 
int minutos_decorridos_em_dias;
```
<p align="justify">Há como melhorar mas se comparado ao nome d já temos um avanço. Deixo a frase do autor: "<i>Esse é o poder de escolher bons nomes</i>"</p>
<p align="justify">Sempre aprendi na faculdade que um fera na programação com o código sujo se torna um mau programador. Ganhamos o respeito e se tornamos bons
quando nosso código carrega além das técnicas a empatia para os demais profissionais, seja acima ou abaixo do cargo atual.</p>



 

  
