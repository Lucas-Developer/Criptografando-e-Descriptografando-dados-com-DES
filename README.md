O DES é um algoritmo de criptografia de bloco que utiliza uma chave simétrica de 64 bits em disco (armazenada), uma chave de 56 bits para execução quando ela for submetida (8 bits restantes são usados para paridade e depois descartados) e 16 subchaves de 48 bits. Essas 16 subchaves são derivadas da chave anterior de 56 bits através de um total de 16 iterações.

O mesmo método usado na criptografia é usado na descriptografia, sendo que a diferença está na sequencia que as subchaves são utilizadas.

Entre os problemas do DES está a chave que é relativamente pequena (56 bits), e por isso foi criado o método “Whitening” e o método de “Multiplicidade”.

O Whitening é constituído por um texto puro de 56 bits, uma chave de 56 bits, o algoritmo DES para processamento e tem como saída um texto cifrado de 64 bits. Portanto, o processo começa com a entrada de um texto puro e uma chave de 64 bits que será processada pelo DES em conjunto com outra chave de 56 bits, que totaliza uma chave de 120 bits, no momento posterior ao processamento pelo DES temos ainda outra chave de 64 bits que não agrega força ou segurança, pois ela é derivada da primeira.

Algumas das evoluções do DES é o 2DES e o 3DES que aumentam o número de chaves no processo.
