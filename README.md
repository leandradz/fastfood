# Tech-Challenge Fiap - Software Architecture

## Introdução
O projeto foi desenvolvido no âmbito da pós graduação em *Software Architecture* da Fiap. Dado um contexto e um problema (descritos abaixo), foi desenvolvida uma aplicação, utilizando os conteúdos aprendidos no curso.

### Contexto 
Há uma lanchonete de bairro que está expandindo devido seu grande sucesso. Porém, com a expansão e sem um sistema de controle de pedidos, o atendimento aos clientes pode ser caótico e confuso. Por exemplo, imagine que um cliente faça um pedido complexo, como um hambúrguer personalizado com ingredientes específicos, acompanhado de batatas fritas e uma bebida. O atendente pode anotar o pedido em um papel e entregá-lo à cozinha, mas não há garantia de que o pedido será preparado corretamente.

Sem um sistema de controle de pedidos, pode haver confusão entre os atendentes e a cozinha, resultando em atrasos na preparação e entrega dos pedidos. Os pedidos podem ser perdidos, mal interpretados ou esquecidos, levando à insatisfação dos clientes e a perda de negócios.

Em resumo, um sistema de controle de pedidos é essencial para garantir que a lanchonete possa atender os clientes de maneira eficiente, gerenciando seus pedidos e estoques de forma adequada. Sem ele, expandir a lanchonete pode acabar não dando certo, resultando em clientes insatisfeitos e impactando os negócios de forma negativa.

### Problema
Para solucionar o problema, a lanchonete irá investir em um sistema de autoatendimento de fast food, que é composto por uma série de dispositivos e interfaces que permitem aos clientes selecionar e fazer pedidos sem precisar interagir com um atendente, com as seguintes funcionalidades:

- **Pedido**
- **Pagamento**
- **Acompanhamento**
- **Entrega**
- **Gerenciar clientes**
- **Gerenciar produtos e categorias**

### Objetivos
#### Fase 1
 - Desenvolver uma aplicação para todo o sistema de backend (monolito), com base na **arquitetura hexagonal**, apresentando as seguintes APIs:

- **Cadastro do Cliente**
- **Identificação do Cliente via CPF**
- **Criar, editar e remover produtos**
- **Buscar produtos por categoria**
- **Fake checkout, apenas enviar os produtos escolhidos para a fila. O checkout é a finalização do pedido.**

- Desenvolver um banco de dados, utilizado para organizar a fila dos pedidos.

- Observação: A aplicação deve ser entregue com um Dockerfile configurado para executá-la corretamente, e um docker-compose.yml para subir o ambiente completo.
              
### Funcionamento

### Roadmap
- [ ]


## Como iniciar o programa
```bash
./mvnw clean install
./mvnw spring-boot:run
```

## Contatos