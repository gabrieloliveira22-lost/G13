# G13
Alunos: 
  Emiliano Rodrigues Feliciano,
  Elberty Borges de Oliveira e
  Gabriel Henrique Oliveira Silva.

INTRODUÇÃO
  Desde 2012, com a publicação da Resolução Normativa nº 482 pela ANEEL, que permitiu aos consumidores instalarem pequenos sistemas e compensarem o excedente de energia na rede, observamos um "boom" de instalações de geração de energia fotovoltaica. Normalmente o sistema é gerenciado com a visita de um técnico especializado, no local onde estiver operando. Para que o sistema não seja sobrecarregado ou fornecendo tensão abaixo do padrão (19V), é necessário o controle para que se mantenha dentro de limites pré-definidos. Neste projeto, gerenciaremos apenas a tensão no sistema simulado. 
OBJETIVOS
  Com o objetivo de facilitar este monitoramento, será implementado software e hardware para medição de tensão da geração simulada e transmissão por wireless para central de processamento. Será considerada tensão dentro do padrão, caso a mesma se mantenha entre 18V (mínimo) e 20V (máximo).

EQUIPAMENTOS, SOFTWARES E MATERIAIS
  1 - Fonte de tensão 19V,
  1 - Placa ESP32,
  1 - Roteador A930H,
  1 - Computador.
  Eclipse,
  Apache NetBens IDE 15,
  Visual Studio Code.

CRONOGRAMA
  
23/03 - Definição do cronograma;
Planejamento das etapas: leitura de tensão, transmissão de dados e visualização no servidor.

30/03 - Estrutura base do programa;
Configuração inicial no ESP32 e criação da base do código no Visual Studio Code / Eclipse / NetBeans.

06/04 - Definições de objetos e classes;
Definição das estruturas do sistema:
classe de leitura de tensão
classe de comunicação Wi-Fi
classe de envio de dados
estrutura do servidor

13/04 - Aprimoramento das características dos objetos;
ajuste da leitura 
calibração da tensão
melhoria na estrutura do código
organização das funções.

20/04 - Implementação da leitura de tensão;
leitura da fonte 19V pelo ESP32
conversão para valores reais
testes no monitor serial.

27/04 - Desenvolvimento do envio de dados (Wi-Fi);
conexão com roteador A930H
envio de dados via HTTP ou MQTT
testes de comunicação.

04/05 - Criação da lógica de monitoramento (simulação de falhas);
definir limites de tensão
detectar quedas ou valores anormais
simular falhas na fonte

11/05 - Testes de validação de fluxo e correção de bugs;
testar leitura → envio → recepção
corrigir erros de comunicação
validar estabilidade

18/05 - Formatação da saída de dados;
exibição no servidor (terminal ou interface)
organização dos dados recebidos
apresentação das tensões e alertas

25/05 - Revisão final do código e preparação dos slides da apresentação;
revisar todo o sistema
organizar código
preparar explicação do funcionamento

01/06 - Seminário
