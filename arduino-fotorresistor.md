A3:
1) Identifique as entradas e saídas do sistema:
- Entradas:

  Fotorresistor : identifica se está claro, iluminação média ou escuro.

  Botão 1 : ao apertar, seleciona modo automático.

  Botão 2 : ao apertar, seleciona modo manual de alerta.

  Botão 3 : ao apertar, seleciona desligar o sistema.

- Saídas:

  LED RGB : exibe a cor de acordo com a iluminação ou exibe vermelho (se o botão 2 for pressionado)
    Verde : claro
    Amarelo : médio
    Vermelho : escuro ou modo alerta


2) Apresente todos os componentes do sistema e para que eles servem:

  Fotorresistor(LDR): reage a luz, lendo se está claro, média iluminação ou escuro.
  
  Botões: mudam os estados ao serem pressionados.
  
  LED RGB: muda de cor, indicando a leitura do fotorresistor.
  
  Resistor: limita o fluxo de corrente elétrica, evitando problemas no arduíno.


3) Apresente as regras de funcionamento a serem implementadas:
  O modo padrão do sistema é o modo automático, que irá ler a iluminação do ambiente.
  Ao pressionar o botão 1, mudará para o modo automático; se já estiver nesse modo, irá permanecer.
  Ao pressionar o botão 2, mudará para o modo manual, exibindo luz vermelha e ignorando a leitura do LDR.
  Ao pressionar o botão 3, desligará o LED RGB, até que o usuário pressione outro botão.
  Se dois botões forem pressionados ao mesmo tempo, o LED RGB irá apagar, e permanecerá desse modo até que o usuário pressione outro botão.



4) Explique como você utilizaria estruturas if para controlar o sistema:
   Se botao1 for pressionado: ativa modo autómatico de leitura; o LED RGB acende da cor correspondente à leitura do LDR.
   Se botao2 for pressionado: ativa modo manual, mantendo o LED na cor vermelha e ignorando a leitura do LDR.
   Se botao3 for pressionado: desliga o sistema, apagando o LED aceso.
   Se dois botões forem pressionados ao mesmo tempo: desliga o sistema, apagando o LED aceso.

