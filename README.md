# Coffe Shop Sales Software

### Ferramentas do Projeto:

<p>
  Repositório: GitHub<br>
  Comunicação: Discord e WhatsApp<br>
  Metodologia aplicada: <a href="https://www.notion.so/3017a548d79547968404dce96924ae1f?v=64667978a28c4eebbc316c552e049f75&pvs=4">Notion</a> e reuniões semanais<br>
</p>


### Sistema Coffe Shop

Um café oferece diversos serviços aos seus clientes, como venda de café, chás, bolos e sanduíches, além de proporcionar um ambiente agradável para refeições rápidas e encontros sociais. Com o objetivo de melhorar o atendimento e a experiência dos clientes, o café deseja desenvolver um software que permita realizar pedidos de forma digital, seja por meio de um aplicativo móvel ou terminal na própria cafeteria.

O software deve incluir um sistema de gestão de pedidos para a equipe do café, facilitando o acompanhamento e preparo dos itens solicitados. Além disso, deve ser integrado com o sistema de pagamento da cafeteria, permitindo transações rápidas e seguras. Os clientes terão a possibilidade de personalizar seus pedidos, escolhendo opções de ingredientes e especificações adicionais.

Para incentivar a fidelidade dos clientes, o software deve incluir um sistema de fidelidade com recompensas e descontos para clientes frequentes. Os preços dos produtos serão definidos de acordo com suas características específicas, como tipo de café, tamanho da porção e ingredientes adicionais.

Os requisitos não funcionais incluem a garantia de desempenho do sistema, capaz de lidar com um grande volume de pedidos, segurança das transações financeiras, usabilidade da interface do usuário e disponibilidade do sistema 24 horas por dia, 7 dias por semana.

Com a implementação deste software, o café espera otimizar seu processo de atendimento, melhorar a experiência dos clientes e aumentar sua fidelidade, proporcionando um serviço de qualidade e eficiente.


### 1. Entendimento do Problema e Definição de Escopo:

*Problema:*
A cafeteria deseja otimizar o processo de atendimento aos clientes, melhorando a eficiência do pedido, preparo e entrega de alimentos e bebidas, além de oferecer um ambiente mais interativo e tecnológico para os clientes.

*Escopo do Projeto (Inclusões):*
- Desenvolver um software que permita aos clientes realizar pedidos de forma digital, seja por meio de um aplicativo ou terminal na própria cafeteria.
- Implementar um sistema de gestão de pedidos para a equipe da cafeteria, facilitando o acompanhamento e a preparação dos itens solicitados.
- Integrar o software com o sistema de pagamento da cafeteria, permitindo transações rápidas e seguras.
- Oferecer aos clientes a possibilidade de personalização de seus pedidos, incluindo opções de ingredientes e especificações adicionais.
- Desenvolver um sistema de fidelidade para os clientes frequentes, com recompensas e descontos.

*Escopo do Projeto (Exclusões):*
- A reforma física da cafeteria não está incluída no escopo deste projeto.
- A compra de novos equipamentos físicos não está incluída no escopo deste projeto.
- A contratação de pessoal adicional não está incluída no escopo deste projeto.

*Stakeholders Externos:*
- Clientes da cafeteria.
- Funcionários da cafeteria.
- Fornecedores de alimentos e bebidas.
- Empresas de tecnologia responsáveis pelo desenvolvimento do software.

Organizaremos essas definições em um documento para referência e revisão contínua durante o projeto.

### 2. Levantamento de Requisitos:

Para coletar os requisitos dos stakeholders, utilizaremos uma combinação de entrevistas e workshops. As entrevistas serão conduzidas com os clientes e funcionários da cafeteria para entender suas necessidades e expectativas em relação ao software. Os workshops serão realizados com a equipe de desenvolvimento e os stakeholders principais para identificar requisitos técnicos e operacionais.

### 3. Documentação de Requisitos:

Selecionaremos a técnica de descrição de requisitos "Histórias de Usuário com Critérios de Aceitação" devido à sua capacidade de capturar as necessidades dos usuários de forma sucinta e clara, além de fornecer critérios objetivos para validar a implementação.

Documentaremos os requisitos funcionais e não funcionais de forma precisa, incluindo detalhes sobre a interação do usuário com o sistema, requisitos de desempenho, segurança e usabilidade.

Organizaremos essa documentação em um formato estruturado para facilitar a compreensão e a revisão por parte da equipe de desenvolvimento.

Com base nessas etapas, estamos prontos para prosseguir com o projeto de desenvolvimento do software da cafeteria, garantindo que todos os requisitos sejam compreendidos e documentados de maneira adequada.

### Requisitos Funcionais:

1. *Registro de Clientes:*
   - O sistema deve permitir que novos clientes se registrem, fornecendo informações básicas como nome, e-mail e telefone.

2. *Realização de Pedidos:*
   - Os clientes devem poder visualizar o menu completo da cafeteria no aplicativo ou terminal.
   - Deve ser possível adicionar itens ao carrinho de compras, especificando opções de personalização (por exemplo, tamanho, ingredientes extras).
   - Os clientes devem ter a opção de revisar e editar seus pedidos antes de finalizá-los.

3. *Gestão de Pedidos:*
   - Os funcionários devem receber notificações instantâneas de novos pedidos feitos pelos clientes.
   - Deve existir uma interface para os funcionários acompanharem o status dos pedidos em preparação, prontos para entrega e entregues.

4. *Sistema de Pagamento:*
   - O software deve suportar diferentes métodos de pagamento, como cartão de crédito, débito e pagamento móvel.
   - Deve ser possível integrar o sistema com dispositivos de pagamento existentes na cafeteria.

5. *Programa de Fidelidade:*
   - O sistema deve registrar as compras dos clientes e atribuir pontos de fidelidade com base nos valores gastos.
   - Os clientes devem poder resgatar pontos por descontos em futuras compras ou por itens gratuitos.

6. *Gestão de Estoque:*
   - O sistema deve atualizar automaticamente o estoque de itens disponíveis sempre que um pedido for feito e concluído.
   - Os funcionários devem receber alertas quando os níveis de estoque estiverem baixos, facilitando a reposição de produtos.

### Requisitos Não Funcionais:

1. *Desempenho:*
   - O sistema deve ser capaz de lidar com um grande volume de pedidos simultâneos durante os horários de pico, garantindo tempos de resposta rápidos.

2. *Segurança:*
   - Todas as transações financeiras devem ser protegidas por criptografia para garantir a segurança dos dados do cliente.
   - O acesso ao sistema deve ser protegido por autenticação de usuário, com diferentes níveis de permissões para funcionários e administradores.

3. *Usabilidade:*
   - A interface do usuário deve ser intuitiva e fácil de usar, tanto para clientes quanto para funcionários da cafeteria.
   - O sistema deve ser responsivo e compatível com dispositivos móveis, garantindo uma experiência consistente em diferentes plataformas.

4. *Disponibilidade:*
   - O sistema deve estar disponível 24 horas por dia, 7 dias por semana, para que os clientes possam fazer pedidos a qualquer momento.

### Histórias de Usuário:

#### Registro de Clientes:
1. Como um novo cliente, desejo me registrar no sistema da cafeteria, fornecendo informações básicas como nome, e-mail e telefone, para poder fazer pedidos e participar do programa de fidelidade.

#### Realização de Pedidos:
2. Como cliente, desejo visualizar o menu completo da cafeteria no aplicativo ou terminal, para poder escolher os itens que desejo comprar.
3. Como cliente, desejo adicionar itens ao meu carrinho de compras, especificando opções de personalização, como tamanho e ingredientes extras, para que meu pedido seja preparado de acordo com minhas preferências.
4. Como cliente, desejo revisar e editar meus pedidos antes de finalizá-los, para garantir que tudo esteja correto antes de confirmar a compra.

#### Gestão de Pedidos:
5. Como funcionário, desejo receber notificações instantâneas de novos pedidos feitos pelos clientes, para que eu possa começar a prepará-los imediatamente.
6. Como funcionário, desejo ter uma interface onde possa acompanhar o status dos pedidos, desde o momento em que são feitos até serem entregues aos clientes, para garantir uma gestão eficiente do fluxo de trabalho na cafeteria.

#### Sistema de Pagamento:
7. Como cliente, desejo ter a opção de pagar minha compra utilizando diferentes métodos, como cartão de crédito, débito e pagamento móvel, para escolher a forma mais conveniente para mim.
8. Como proprietário da cafeteria, desejo integrar o sistema de pagamento com dispositivos existentes na cafeteria, para facilitar e agilizar o processo de pagamento para os clientes.

#### Programa de Fidelidade:
9. Como cliente, desejo que minhas compras sejam registradas no sistema e que pontos de fidelidade sejam atribuídos com base nos valores gastos, para poder receber descontos ou itens gratuitos no futuro.
10. Como cliente, desejo poder resgatar os pontos acumulados por descontos em futuras compras ou por itens gratuitos, como forma de recompensa pela minha fidelidade à cafeteria.

#### Gestão de Estoque:
11. Como funcionário, desejo que o sistema atualize automaticamente o estoque de itens disponíveis sempre que um pedido for feito e concluído, para garantir que sempre tenhamos os produtos necessários em estoque.
12. Como funcionário, desejo receber alertas quando os níveis de estoque estiverem baixos, para facilitar a reposição de produtos e evitar a falta de itens essenciais na cafeteria.

### Requisitos Não Funcionais:
#### Desempenho:
1. Como cliente, espero que o sistema seja capaz de lidar com um grande volume de pedidos simultâneos durante os horários de pico, garantindo tempos de resposta rápidos para que minha experiência de compra não seja afetada.

#### Segurança:
2. Como cliente, espero que todas as transações financeiras sejam protegidas por criptografia, garantindo a segurança dos meus dados pessoais e financeiros.

#### Usabilidade:
3. Como cliente e funcionário, espero que a interface do usuário seja intuitiva e fácil de usar, independentemente do dispositivo que estou utilizando, para uma experiência consistente e agradável.

#### Disponibilidade:
4. Como cliente, espero que o sistema esteja disponível 24 horas por dia, 7 dias por semana, para que eu possa fazer pedidos a qualquer momento, sem restrições de horário.

### Autores:

Aluno | Matrícula
--------------------------------|---------------------------
Brenda Mendes Araujo | 202209150008
Ian Esteves Amaral Francisco | 202302937314
