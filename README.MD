    Essa ferramenta é um scan de portas que verifica se ha portas abertas em um servidor.
    ela nao é nenhum nmap, é apenas de uma ferramenta simples de portas aberta ou nao.

REQUISITOS: apenas ter o python instalado em seu ambiente independente da versao

    
    1- importe a biblioteca socket
    2- PORTS aqui temos uma lista de portas comuns em sistemas e servidores,
    voce pode usar, adicionar ou deletar de modo que preferir.
    3- HOST gera um input de entrada para o host alvo.
    4- CLIENT um ojeto que fara a conecçao, "AF_INET" aqui dizemos que vai ser um socket do tipo ip que faz referecia
    ao modelo de IPv4, "socke.SOCK_STREAM" aqui dizemos que vai de ser do metodo TCP.
    5- FOR criamos o loop pra que seja percorrido todos os valores da lista de portas.


Se desejar fazer apenas um scan em sua porta especifica  basta remover a linha 31 e retirar a indentaçao/espaços 
em branco que ficar nas demais linhas.
    
