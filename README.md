# EngSoftI
Bem-vindo ao projeto da disciplina EngSoftI!
## Descrição

Este repositório contém todos os materiais e projetos
relacionados à disciplina EngSoftI.
![NLCxZjim4ErvYabdNy4kieRNG09aTuKrSe2nEBOd83a6IJd9mfS9KYnIf4oJLXVBK99bRLm8nFpUl3VFTobZp8rtnhopjET0y87GKjpcxuwWTfZIcAcYr9HIdufKPmm7HsFwdcfEBA7FMqOlmTwoc778w6k7wTQu2VR_cUQoTamXqyLq6vf5vJ3G5_GQ51sHO2t-534jpUAUafDwI65](https://github.com/WillianSoaa/EngSoftl/assets/147007877/d889271d-83b6-46e6-9992-3bfcd6c8b0b1)
Descrição Detalhada do Processo de Compras em um Mercado:
Planejamento das Compras:
Antes de ir ao mercado, o cliente faz um planejamento detalhado das compras. Isso envolve
a criação de uma lista de compras que inclui todos os itens necessários, sua quantidade
estimada e até mesmo um orçamento previsto.
Deslocamento até o Mercado:
O cliente se desloca até o mercado de sua escolha, seja de carro, transporte público ou a
pé, dependendo da localização e das preferências pessoais.
Entrada no Mercado:
Ao chegar ao mercado, o cliente passa pelo ponto de entrada e pega um carrinho de
compras disponível.
Navegação pelos Corredores:
O cliente percorre os corredores do mercado, seguindo a ordem da lista de compras. Ele
busca cada item, considerando marca, tamanho, qualidade e preço.
Comparação de Preços e Marcas:
Durante a seleção dos produtos, o cliente compara os preços entre diferentes marcas e
verifica as datas de validade, ingredientes e informações nutricionais quando necessário.
Adição de Produtos ao Carrinho:
O cliente coloca os produtos selecionados no carrinho de compras. Itens frágeis, como
ovos, são manuseados com cuidado para evitar danos.
Listagem de Itens no Aplicativo:
Alguns clientes usam aplicativos de compras para escanear os produtos e manter um
registro digital do que está no carrinho e do valor total estimado.
Consulta a Ofertas e Promoções:
O cliente verifica se existem ofertas, descontos ou promoções especiais em produtos da
lista de compras.
Pausas para Tomar Decisões:
Em alguns momentos, o cliente pode pausar para fazer decisões de última hora, ajustar a
lista de compras ou reavaliar as prioridades.
Conclusão das Compras:
Após encontrar todos os itens da lista, o cliente se dirige ao caixa para concluir as compras.
Passagem pelo Caixa:
No caixa, os produtos são escaneados ou registrados pelo atendente. O cliente realiza o
pagamento usando dinheiro, cartão de crédito, débito ou outros métodos disponíveis.
Embalagem dos Produtos:
Os produtos são embalados em sacolas ou caixas adequadas, muitas vezes separando
produtos perecíveis de itens não perecíveis.
Recebimento do Comprovante:
O cliente recebe um comprovante de compra que lista os itens adquiridos, os preços
individuais e o total pago.
Saída do Mercado:
O cliente deixa o mercado com as compras realizadas, empurrando o carrinho ou
carregando as sacolas.
Retorno para Casa:
O cliente volta para casa com os produtos adquiridos, mantendo-os em boas condições,
especialmente itens perecíveis.
Desembalagem e Armazenamento:
Em casa, o cliente desembala os produtos e os armazena em locais apropriados, como
geladeira, despensa ou armários, seguindo as orientações de armazenamento.
Utilização dos Produtos:
Os produtos adquiridos são usados conforme necessário na vida cotidiana, seguindo as
datas de validade e as instruções de uso.
Codigo:
@startuml
!define HeaderStyle class
!define ProcessStyle rectangle
!define DecisionStyle diamond
!define DataStyle database
!define EndStyle rectangle
|Cliente|
start
:Planejamento das Compras;
:Deslocamento até o Mercado;
|Mercado|
:Entrada no Mercado;
:Obtenção de Carrinho de Compras;
while (Navegação pelos Corredores) is (Itens a comprar) do (sim)
:Selecionar Item;
:Comparar Preços e Marcas;
:Adicionar Produto ao Carrinho;
:Listar Item no Aplicativo;
:Consultar Ofertas e Promoções;
if (Necessário fazer decisões de última hora?) then (sim)
:Pausar para Decisões;
endif
endwhile
:Conclusão das Compras;
|Caixa|
:Passagem pelo Caixa;
:Escaneamento de Produtos;
:Pagamento;
:Embalagem dos Produtos;
:Recebimento do Comprovante;
|Mercado|
:Saída do Mercado;
end
:Retorno para Casa;
:Desembalagem e Armazenamento;
:Utilização dos Produtos;
|Cliente|
stop
@enduml
