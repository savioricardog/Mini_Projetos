# Mini_Projetos
projetinhos feitos em python para suprir necessidades ultra necessarias (quando da aquela preguicinha de fazer algo manualmente)

# 1° - O primeiro projeto vem de uma necessidade minha de consultar minhas ordens de compra e venda na BitcoinTrade.
Por que eu precisava consultar? 
Por que sem querer acabei excluindo todas minhas movimentações do site que uso para consulta-las que é o 'Status Invest', então por necessidade de ter que integra-las todas novamente, e com certa preguiça de fazer manualmente, decidi fazer a requisição e consultas dos meus dados na corretora por meio do request de API disponibilizado pela BitcoinTrade.
Então para deixar o 110% full ultra master blaster completo, criei essa funçãozinha para já desde o inicio (importação das libs e request de api) conseguir obter os dados, passando-os por filtros e limpezas necessarias para serem convertidos às especifições solicitadas pelo 'Status Invest', chegando até o report desses dados, onde a função já entrega um arquivo excel (.xlsx), que atende as especificações exigidas pela BitcoinTrade, podendo assim só exporta-lo do ambiente utilizado para a máquina ou cloud e importa-lo dentro do 'Status Invest', que suas ordens de compra serão integradas normalmente.
