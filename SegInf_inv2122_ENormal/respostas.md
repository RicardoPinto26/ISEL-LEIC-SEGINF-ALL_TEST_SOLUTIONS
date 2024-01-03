1:
- V
- V
- F - dimensão da chave depende da primitiva, e não do modo de operação
- V

2:
- F - É verificada com a chave pública do emissor
- F - Certificado não tem private key
- V
- F - São derivadas do master secret

3:
- F - designa o servidor que o utilizador está a aceder
- V
- F
- F - endpoint da aplicação cliente

4:

Caso a função seja utilizada para gerar uma assinatura digital, é possivel que dois certificados tenham a mesma assinatura, apesar de serem emitidos por diferentes autoridades de certificação.

5: pode tar mal, nao sei xd

client:
Alice, KsA1, Int1, Int2, CA2

server:
C2, KsC2, Int2, , CA2, CA1

6:

???

7:

Como um hash é uma operação unidirecional, é impossivel para um atacante que obtenha a informação guardada no server descobrir a password. No entanto, se usarmos uma solução por cifra simétrica/assimétrica, esta é uma operação bidirecional, o que leva a que seja sempre possivel descrifrar a password, desde que sejam conhecidos os dados necessários.

8:

Um esquema MAC necessita de menos poder computacional, mas não fornece não repúdio. Pelo contrário, um esquema de assinatura digital fornece não repúdio, mas tem um custo computacional mais elevado que o MAC.

9:

???

10.1:

TODO()

10.2:

TODO()
