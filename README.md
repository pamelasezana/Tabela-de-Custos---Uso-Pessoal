# Tabela de Custo e Lucro

**Descrição:**
Este é um projeto simples de tabela de custo e lucro, desenvolvido para facilitar o acompanhamento de dados financeiros relacionados a produtos. A tabela exibe informações detalhadas sobre a data, produto, quantidade, custo, preço de venda, lucro, e oferece a capacidade de adicionar, excluir e atualizar produtos de forma dinâmica.

## Estrutura da Tabela
A tabela é composta por diversas colunas que fornecem detalhes específicos sobre cada produto. As principais colunas incluem:

- **Data:** A data em que as informações foram registradas.
- **Produto:** O nome do produto (editável).
- **Quantidade:** A quantidade de unidades do produto.
- **Custo (R$):** O custo unitário do produto em reais (editável).
- **Preço de Venda (R$):** O preço de venda unitário do produto em reais (editável).
- **Lucro (R$):** O lucro total obtido com o produto.

A tabela também conta com botões de ação, como "Adicionar Produto", "Atualizar", e "Excluir", para facilitar a interação do usuário.

## Estilo
A interface é projetada para ser responsiva, proporcionando uma experiência de usuário agradável em dispositivos de diferentes tamanhos. O esquema de cores adotado contribui para uma aparência limpa e profissional.

## Funcionalidades
- **Adição de Produto:** O botão "Adicionar Produto" permite a inserção fácil de novos produtos na tabela.
- **Exclusão de Produto:** O botão "Excluir" em cada linha possibilita a remoção rápida de produtos.
- **Atualização Dinâmica:** Os totais de custo e lucro são calculados automaticamente à medida que os dados são modificados.
- **Persistência de Dados:** Os dados são armazenados localmente, permitindo que o usuário mantenha o progresso mesmo ao recarregar a página.

## Gráfico
Uma representação visual dos totais de custo e lucro é exibida em um gráfico de barras, facilitando a análise rápida e intuitiva.

## Como Usar
1. Adicione produtos clicando no botão "Adicionar Produto".
2. Edite as informações diretamente na tabela.
3. Exclua produtos indesejados utilizando o botão "Excluir".
4. Os totais de custo e lucro são atualizados automaticamente.

## Tecnologias Utilizadas
- **HTML:** Estruturação do conteúdo.
- **CSS:** Estilização da interface.
- **JavaScript (Chart.js):** Manipulação dinâmica de dados e criação do gráfico.

*Nota: Este projeto utiliza a biblioteca Chart.js para a criação do gráfico. Certifique-se de incluir a biblioteca na sua página para garantir o funcionamento adequado.*