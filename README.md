# RESUMO-LAB-CLOUD-COM-IA
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO
Curso XP INC – CLOUD  COM INTELIGENCIA ARTIFICAL

MÓDULO 01

COMO A COMPUTAÇÃO EM NUVEM FUNCIONA (AULA 01)

O QUE VAMOS APRENDER?
- O QUE É NUVEM (CALUDE)?
- COMO FUNCIONA?
- PORQUE E AONDE UTILIZAMOS?

O QUE É ?


Vamos simplificar.
As casas de modelo americano são pequenas, ambiente limitados e com pouca capacidade, de modo que as pessoas tem algumas coisas compiladas.
Por conta do espaço limitado , não era comum ter uma maquina de lavar em casa (é um costume brasileiro e não no resto do mundo).
Então, não é normal ter uma maquina de lavar em casa, pois tem o custo do recurso (utilização e manutenção), espaço dentro de casa e em relação a limitação de uso, pois não se justificar ter o tempo todo dentro de casa em razão do uso.
Portanto, levando em consideração a este contexto, criou-se um modelo: Lavanderias (laundry). Ao invés de gastar o valor de uma máquina, espaço  etc. é melhor dirigir-se a lavanderia e pagar pelo uso com umas simples moeda com grande economia.


Então, temo acesso  ao produto e serviço sem compra-lo. E o modelo se paga pela quantidade de pessoas usando. Vamos no ambiente compartilhando, pagando apenas pelo uso e ainda sai mais barato. 
Esta prestação de serviço chama-se (as a servisse) – modelo de negócio.

O modelo as a servisse é um modelo de negócio, onde se paga apenas pelo uso.

No caso de programação, imagine um ambiente de empresa também no seu limite físico limitado. Imagine que esta empresa é um banco que oferece vários serviços como processamento de pagamento, transações, integridade dos sistemas etc.  Então, o banco pega uma máquina e destina as suas necessidade essenciais – processamento de todos os dados e solicitações. Para manter a maquina funcionando,  tem custos, como espaço, aquisição etc.


Imagine que o negócio cresce e precisa-se de 2, 3, ou várias máquinas, imagine os custos de espaço, manutenção, aquisição etc.



Cuidado. Muitas máquinas ligadas necessitam de resfriamento! Agora temos uma nova preocupação: refrigeração
Também precisamos de um desafio de se conectar todas as máquinas, elas precisam conversar entre si, seja através de cabo ou internet – networking (cabeamento e internet.

Agora temos um outro problema, precisamos de internet de alta velocidade.
Então, precisamos de um a ambiente dedicado a esta estrutura chamado de DATACENTER – ambiente com máquinas processando solicitações a todo momento. 

Observe que caso necessitemos colocar outra(s) máquina(s) ligadas, aumenta todo o custo do projeto.

Este ambiente privado que no exemplo os bancos precisavam alugar chama-se – ON PREMISA (no local).

Imagine também a seguinte situação: a empresa ON PREMISA tem 10 máquinas e dedica 5 ao Banco X, então as outras 05 máquinas serão dedicadas a outras empresas, ou até melhor, paga-se somente pelas solicitações (pelo uso, igual a lavanderia). Portanto, a On PRIME está vendendo apenas o serviço -  as a service.

Os Bancos irao usar as maquinas através da conexao da internet. Entao, os bancos utilizam o serviço da outra empresa através da internet, fora do seu espaço físico (bancos), isto é chamdo de SERVIÇO NA NUVEM (AMBIENTE CLAUDE).

Imagine uma outra empresa C de jogos, tem a demanda de jogos online e nos mêses de Janeiro e junho tem um pico simultaneo de acesso, porém nos restantes do meses o acesso é normalizado. Entao, em tais meses pode-se alugar o serviço Coloud (Hibrido). Entao, está empresa tem 02 máquinas (premise) no local, e mais duas máquinas alugadas para os picos de janeiro e junho (Cloud). É o modelo híbrido (hybrid).

Então, são 03 modelos mais comuns:
1) ON PREMISE
2) CLAUDE
3) HYBRID

Não existe modelo ideal, depende da necessidade.
Uma desvantagem do servidor claude pode ser a latência, que é a demora que o cliente demora de acessar a máquina do servidor.

E de onde vem as máquinas para aluguel do servidor claude ? a empresa é dona e adminstra a infraestrutura. Então há uma terceirização da estutura, que é a venda do maquinário como servico ( Infra as a Service – IAAS). Significa o alugel uma estrutura de outra empresa e consome o recurso. Um bom exemplo é o aluguel de um carro através de terceiro para trabalhar de uber.

Neste contexto, temos empresas especifica com estrutura completa para alugar máquinas para outra empresa ( plataforma de nuvem), exemplos AWS (Amazon Web Service), Azure, Oracle e GCP (google).

Atentar que tais empeesas não somente vendem IAAS, podem vender, por exemplo PAAS, SAAS etc (sáo os claudes services).

Voltemos ao problema de latência, onde a distancia entre as empreas e as plataformas interfere na rapidez de transimssao de dados. Para diminuir este dilema, criama duas coisas: regions e Zones.
Imagine que as plataformas têm várias máquinas distribuidas ao redor do mundo (REGIONS), assim diminui a latência.
REGION: lugares diferenes do mundo onde vai encontrar conjunto de máquinas para alugar. Quando mais peorto da empresa for o datacentes, menor a latência.
Dentro da REGION temos a ZONE ( como se a região fosse a cidade e a Zona fosse o bairro).

Caude é consumir serviço de outras máquinas.



CRIAR CONTA NO AWS

Introdução a Computação em Nuvem (AULA02)

 
Claude é um datacenter que foi virtualizado.
 
CRIAR CONTA NO MICROSOFT AZURE

 
O que é a computação na nuvem? É o fornecimento de serviços de computação pela internet, habilitando inovações mais rápidas. Recursos flexíveis e economias de escala.

Toda empresa precisa ter um DATACENTER, que é uma sala com vários servidores e refrigerada. Cada vez mais exige-se mais máquina, ficando mais cara, É possível emular várias máquinas em uma só. Então, é a virtualização dos serviços através da internet.
A computação em nume faz sentido para empresa quando se cria recurso de maneira rápida. É necessários pessoas para administrar tais recursos no dia-dia. A empresa tem um curso por mês que é o pagamento do servidor.

NUVEM PRIVADA: É o ambiente 100% ON PREMISE. Os servidores servem apenas a determinada empresa.



NUVEM PÚBLICA:

Exemplo a Microsoft AZURE. Toda empresa tem acesso ao Datacenter.
 

NUVEM HIBRIDA: Geralmente é o melhor. Existe o ambiente ON PREMISE E CLAUDE. Há a nuvem privada que comunica com a nuvem pública.

 
MODELO MULTICLOUD: A empresa tem, por exemplo duas conta em servidores público, conta na Azure, conta na ASW e ainda o datacenter (nuvem privada).

COMPARAÇÃO DE MODELOS DE NUVEM:
NUVEM PUBLICA:
 

A nuvem privada tem orçamento, cabeamento, computador etc. Você compra o produto.

Nenhuma despesa de capital é exigida para escalar, pois não se paga na hora, apenas depois.
Os aplicativos podem ser provisionados/desprovisionados rapidamente, ou seja, podem ser criados e deletados.

Em relação as máquinas, o problema é do fornecedor.

NUVEM PRIVADA:


São os datacenters ON PROMISE.
Aqui, os produtos e máquinas é de responsabilidade da empresa contratante.

NUVEM HIBRIDA:

 
CaPex e OpEX:
São despesas financeiras.


Despesas de Capital (CaPex): 
Imagina que adquire uma nova máquina, neste caso, pode precisar formatar, cabos, espaço físico, há um custo para isto. Quando se está instalado, os custos diminuem para energia, eventual manutenção e refrigeração.

OpEX:
É o valor da operação.


Aqui se cobra em relação aos usos e produtos quando usar e/ou ficar sob disponibilidade.

MODELO BASEADO EM CONSUMO:
Paga-se pelo uso.

Quanto mais tempo o recurso fica ativo, mais gasta-se. É como se fosse a conta de luz e água.

Links úteis para estudo:


https://learn.microsoft.com/training/modules/describe-cloud-compute/2-introduction-cloud-compute

https://learn.microsoft.com/training/modules/describe-cloud-compute/3-what-cloud-compute 

https://learn.microsoft.com/training/modules/describe-cloud-compute/5-define-cloud-models 

https://learn.microsoft.com/training/modules/describe-cloud-compute/5-define-cloud-models 

BENEFÍCIOS DA NUVEM AZURE:
BENEFÍCIO DA NUVEM AZURE:
A) ALTA DISPONIBILIDADE: É um sistema que está sempre funcionando de todo lugar. Os recursos são disponíveis sempre que necessário. Está associado ao SLA, a empresa que fornece o serviço na nuvem [e responsável pela sua integridade e funcionamento.
Quando há problema no fornecimento do serviço, o usuário recebe um estorno (exemplo quando alguns softwares ou ate mesmo toda a plataforma fica indisponível).


 

Analisar o contrato e verificar se há cobertura pelo tempo que a nuvem fica offline. A porcentagem indica a disponibilidade máxima (99.9%). Se o serviço ficar fora além do tempo contratado, há o recebimento de crédito pelo cliente (Não dinheiro e sim crédito).

B) ESCALABILIDADE:

 

É adicionar mais recursos para fazer frente a demanda: HD ficou cheio, tem que acrescentar um outro, ou seja disponibilizar mais espaço.

C) ELASTICIDADE:
É como a Black Friday

 

Então no período da black Friday há um aumento da demanda, o que exige mais capacidade de atendimento. Neste caso, adquire-se serviço por temporada para atender a demanda sazonal (exemplo: se atingirmos 75% da capacidade de processamento, o contrato prevê a adição de mais um servidor).

D) CONFIABILIDADE

 

São várias regiões do globo que fornecem o serviço para ser melhor prestado e evitar a troca de informações entre as máquinas.

 

E) PREVISIBILIDADE

 

F) SEGURANÇA

 
G) GOVERNANÇA
É como vamos gerir os recursos e seguir os padrões.
Imagine que a minha empresa trabalha no ramo farmacêutico então a Claude deve se adequar as necessidades farmacêuticas, ou seja, deve guardar sintonia. A empresa não pode violar as normas de governança da Cloud.
 

H) GERENCIABILIDADE:
  
Como vamos gerencias o ambiente na nuvem e seus recursos? Por meio de um portal da web, usando uma interface de linha de comando, usando APIs, PowerShell etc.

--> AINDA CARECE DE REVISÃO.



