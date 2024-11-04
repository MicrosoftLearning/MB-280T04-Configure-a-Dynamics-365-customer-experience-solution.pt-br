---
lab:
  title: 'Exercício 1: Personalizar o processo de vendas'
---

# Exercício 1: Personalizar o processo de vendas

## Cenário: Contoso Home Security 
A Contoso Home Security é uma empresa de monitoramento e equipamentos de segurança doméstica direta ao consumidor. Seus produtos incluem campainhas inteligentes, termostatos inteligentes, sistemas de segurança, sensores de umidade, entre outros. Por serem diretos ao consumidor, seus produtos são vendidos online ou em suas lojas de varejo em 11 grandes cidades dos EUA. É atribuído aos clientes online um representante de conta. A função do representante de conta é acompanhar o cliente e tentar fornecer produtos e serviços adicionais. 

### O processo de vendas da Contoso
Os representantes de conta são atribuídos a todas as contas corporativas em busca de soluções de segurança. As vendas corporativas geralmente demoram mais e incluem vários estágios e tarefas diferentes.

Um exemplo de processo de vendas pode incluir os seguintes estágios:

-   **Qualificar:** é aqui que o executivo de contas tenta determinar se seríamos uma boa opção para um cliente.
-   **Desenvolver:** é aqui que o executivo de contas trabalha com outros membros da equipe de vendas para criar uma solução que melhor se adapte ao cliente. Durante esse estágio, os executivos de conta devem incluir produtos relevantes do catálogo de produtos da Contoso.
-   **Cotar:** é aqui que o executivo criará e entregará uma cotação ao cliente. Uma cotação pode passar por várias iterações antes que o cliente assine.
-   **Verificação técnica:** esta etapa se aplica apenas a negócios avaliados em mais de 20.000,00 dólares. A solução precisa ser verificada por um consultor técnico antes de ser fechada.
-   **Fechar:** é aqui que o executivo de conta analisa o negócio mais uma vez e garante que o cliente esteja pronto para assinar.

### Incentivo a clientes potenciais 
A Contoso também tem um programa de nutrição de clientes potenciais que eles usam para maximizar as possibilidades de fechar um negócio. O programa de nutrição de clientes potenciais consiste no seguinte:

1.  **Telefonema de introdução:** o executivo de conta liga para o cliente para apresentar a Contoso e os produtos que vendemos.
2.  **Email informativo:** um dia após o telefonema inicial, o executivo de conta enviará um email ao cliente. O email incluirá detalhes sobre a Contoso Home Security e os produtos que eles vendem.
3.  **Email de checagem:** três dias após o email de apresentação, outro email é enviado ao cliente para saber se ficou alguma dúvida que possamos responder.
4.  **Agendar telefonema de compromisso:** dois dias após o email de checagem, o cliente recebe outro telefonema em que o executivo de conta tenta marcar uma reunião com o cliente para qualificá-lo ou desqualificá-lo.

### Detalhes importantes
-   O processo de nutrição de clientes potenciais só deve ser aplicado a clientes rotulados como contas corporativas.
-   A Contoso Home Security não se refere às suas oportunidades como oportunidades: eles as chamam de **Negócios**.
-   Negócios que valem mais de \$20.00,00 demandam verificações técnicas. Esta etapa é necessária e o negócio não pode avançar se isso não tiver sido realizado.
    -   A verificação técnica e seus detalhes precisam ser anotados e registrados no negócio. Eles precisam identificar qual membro da equipe fez isso, a data em que foi feito e quaisquer outros detalhes relevantes. Se estiver tudo certo, isso também precisa ser anotado.
-   Nem todas as vendas da Contoso são registradas em seu sistema CRM.
    -   As transações das lojas de varejo são armazenadas em um sistema de ponto de venda separado.
    -   As transações online são armazenadas em um site de comércio eletrônico separado.
-   A Contoso também tem um programa de fidelidade no qual os clientes podem se inscrever. Essas informações também são armazenadas em um site separado.

Como a Contoso tem informações do cliente em vários lugares, eles costumam ter dificuldade para manter uma compreensão completa de quem é o cliente em toda a organização. Eles querem uma maneira de consolidar todos esses dados em uma exibição singular.

As fontes de dados podem ser encontradas nos seguintes caminhos de arquivo CSV:
- **Clientes:**https://aka.ms/CI-ILT/Contacts
- **Transações de varejo em PDV:**https://aka.ms/CI-ILT/POSPurchases
- **Transações online:**https://aka.ms/CI-ILT/OnlinePurchases
- **Clientes do Programa de fidelidade:**https://aka.ms/CI-ILT/LoyaltySchemeCustomers

