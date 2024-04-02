# `Monitor de Vagas de Estacionamento`
# `Parking Lots Monitor`

## Apresentação

O presente projeto foi originado no contexto das atividades da disciplina de graduação *EA075 - Introdução ao Projeto de Sistemas Embarcados*, 
oferecida no primeiro semestre de 2024, na Unicamp, sob supervisão da Profa. Dra. Paula Dornhofer Paro Costa, do Departamento de Engenharia de Computação e Automação (DCA) da Faculdade de Engenharia Elétrica e de Computação (FEEC).

> Incluir nome RA e foco de especialização de cada membro do grupo. Os projetos devem ser desenvolvidos em duplas.
> |Nome  | RA | Curso|
> |--|--|--|
> | Eduardo Pereira Tejada  | 183451  | Eng. Elétrica|
> | Gabriel Dias Vasconcelos  | 248134  | Eng. Elétrica|


## Descrição do Projeto
O projeto visa solucionar o problema de encontrar espaços de estacionamento disponíveis. Oferecendo uma solução automatizada e inteligente para melhorar a experiência dos usuários, bem como a eficiência no uso das vagas. Podem se beneficiar dessa ideia diversos estabelecimentos comerciais como shoppings e supermercados e ainda leva vantagens aos motoristas individuais. O monitor de vagas agrega valor econômico às empresas aumentando o fluxo de clientes, que perderão menos tempo presos no estacionamento procurando um lugar vago e portanto ficarão mais propensos à retornarem ao estabelecimento futuramente, além poder vir a ser útil para a segurança e extração de dados sobre o padrão de uso do estacionamento.


## Descrição Funcional
> A descrição funcional do projeto é a principal entrega do E1 e pode ser realizada neste próprio arquivo Markdown,
> com links para diagramas ou outros arquivos que estejam no próprio repositório.

### Funcionalidades
O sistema deve ser capaz de identificar quais vagas estão ocupadas, reportar esses resultados para os usuários do estacionamento e salvar em uma base de dados com uma certa periodicidade.

### Configurabilidade
> Detalhe, se houver, todas as possíveis configurações do circuito e todos os pontos de alteração da configuração.

### Eventos
Evento 1: novo carro solicitar um lugar pra estacionar;
Evento 2: carro desocupar uma vaga do estacionamento;
Evento 3: estacionamento lotado;
Evento 4: estacionamento deixa de estar lotado.

### Tratamento de Eventos
Evento 1: buscar quais locais estão liberadas, computar qual é a mais próxima do carro solicitante, reportar o resultado e marcar a vaga como ocupada;
Evento 2: registrar vaga como liberada no sistema;
Evento 3: na entrada, reportar que o estacionamento está lotado direcionando para um estacionamento na rua ou indicando um tempo estimado para próxima vaga;
Evento 4: reportar a liberação de vagas na entrada.

## Descrição Estrutural do Sistema
> Junto com a descrição do comportamento do sistema, deve-se especificar, em nível de bloco ou sistema, a estrutura necessária 
> para captar os eventos do mundo externo, para alojar e processar o programa de tratamento de eventos, e para atuar sobre o mundo externo.
>
> Para essa descrição recomenda-se a criação de diagramas de blocos.
> Nesse diagrama, devem ser destacados os blocos funcionais que compõem o sistema, incluindo uma síntese das funcionalidades de cada bloco.
> Além disso, deve-se esclarecer também o relacionamento entre estes blocos, incluindo os principais sinais de comunicação entre
> os blocos de forma a assegurar a execução de todas as tarefas que o sistema deve realizar.
> 
> Você sabia? Ferramentas como o `draw.io` permitem integração com o Github.
> 

## Referências
> Seção obrigatória. Inclua aqui referências utilizadas no projeto.