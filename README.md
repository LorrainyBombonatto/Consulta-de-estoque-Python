produto = input('Insira o nome do produto em letra minúscula')
if produto in produtos:
    i = produtos.index(produto)
    qtde_estoque = estoque[i]
    print('Temos {} unidades de {} no estoque'.format(qtde_estoque, produto))
else:
    print('{} não existe no estoque'.format(produto))
