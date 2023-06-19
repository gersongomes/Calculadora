# Calculadora
 ##Hstória
Um grupo de amigos receberam um convite de aniversário anónimo para uma casa horrorosa no meio da floresta, esse era uma pegadinha de um de seus amigos com o intuito de testar a coragem deles, ma ele sabia que o dono da casa que ele os coividou a ir era um serial killer chamado Caleb Quinn que pendurava suas vitimas e oferecia a uma entidade maligna.
Ao entrar na casa velha de madeira todos cairam em um "sótão" ali eles encontraram um mastro alto com 3 ganchos, logo eles tentaram fugir, mas era tarde demais, todas as portas para sair do sótão ue parecia mais com um labirinto estavam trancadas, para sairem dali tinham que passar em diversos enigmas, consertar os geradores e antes que o assassino os pegasse deveriam abrir a porta principal e fugir.
Enquanto ainda dentro da casa eles escutaram um barulho alto, um grito muito forte que parecia ser do amigo que os havia convidado para a festa eles olharam para cima tinha uma tela mostrando com clresa o que se passava no lado de fora, o amigo estava escondido na floresta quando de repente ouve-se um tiro, era o assassino que disparou uma lança com corrente na parte traseira atingindo as costas do amigo deles e puxandoo assim para perto dele. Quando finalmente o pegou ele o colocou nos obros e lhe pendurou em um gancho.
Agora que comece o jogo.

 ##Primeira parte
A pimeira parte deste jogo foi o frik frak que ja tinha sido enviado.
Lembrando que a versao publicada ainda esta incompleta.

 ##contextualizando
Para a fase atual da Calculadora Simples os amigos enquanto avançaram encontraram um cofre em que acreditam ter algo útil para sairem do sótão. Para desbloquear o cofre eles deveriam encontrar o valor correto realizando operações simples tipo adição, subtração, multiplicação e divisão entre números de 0 a 9.

 ##Elementos
Essa fase possui varios atores, por hora é uma fase independente. Alguns dos atores são O Graf e o Consola que ao serem clicados mudam a variável grafico para 0 ou 1 dependendo do modo que se quer jogar, ao escolher o modo temos os atores de 0 a 9, os atores del,  -, +, *, / e = que quando clicados os numeros mudarão a variavel primeiro numero ou segundo numero dependendo do current number, para o numero que foi clicado, do mesmo jeito os sinais quando clicados mudam a variável operação para a correspondente ex: + = 0 , - = 1  ,... o ator C que reinicia toda a calculadora, o ator del que apagará os numeros no modo pilha, Filo(First in Last out) em outras palavras apagará o segundo numero introduzido primeiro e só depois apagará o primero numero. No modo consola tem o botão help que te dará todas as informações. 
No canto inferior esquerdo encontra-se a presença do assassino que te informará de tudo durante o jogo no estilo bem escroto, tipo vilão.
 ##Codigos
Para os modos foi explicado anteriormente que quando clicados eles mudam o variavel grafico para 1 ou 0, porém ela tambem transmite a mensagem start para começar o jogo.
dependendo do modo que você escolher você pode clicar para escolher o numero/operação ou digitar. No modo consola ao clicar nas teclas de 0 a 9 do seu teclado ele atribuirá à variável primeiro numero ou segundo numero o valor, quanto às operações temos os nomes em ingles P(plus +), M(minus -), D(divide /), T(Times *), E(Equals =), C(Restaurar), z(erase apagar) e h para help.
Boa parte dos codigos consistem em se a operação for 0 por exemplo resultado sera primeiro numero mais segundo numero se resultado for zero, se resultado nao for igual a zero e clicar nas operaçoes é só escolher o valor do primeiro numero e dar igual que mostrará o resultado e por aí vai. o resto é se current number for zero o numero que for clicado será atribuido ao Primeiro numero, se nao, ao Segundo Numero.
Sempre que o equals é clicado ele verá a operação e a fará entre o primeiro numero e o segundo numero(*não é redundancia, esses são os nomes das variáveis).
