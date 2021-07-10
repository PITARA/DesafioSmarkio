# DesafioSmarkio

Funcionalidade: Pesquisar e adicionar ao carrinho um item válido

Cenário 1: Pesquisar item inválido

Dado que eu acesse o site da Kabum
Quando digitar algo inválido na barra de pesquisa
E clicar no botão Buscar
Então eu verei a mensagem "Lamentamos, nenhum produto encontrado com esse critério de pesquisa"

Cenário 2: Pesquisar item válido

Dado que eu acesse o site da Kabum
Quando digitar "placa de video" na barra de pesquisa
E clicar no botão Buscar
E clicar no botão Comprar
Então eu verei a mensagem "ESTE PRODUTO FOI ADICIONADO AO CARRINHO" abaixo do produto
