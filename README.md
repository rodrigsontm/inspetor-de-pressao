# inspetor-de-pressao
O projeto visa a criação de um sistema de regulação dos encanamentos. O sistema faz o monitoramento dos níveis de pressão dos encanamentos de determinadas áreas da cidade, com o intuito de detectar se o encanamento de uma área possui um vazamento ou alguma obstrução, fechando então o registro para aquela área, avisando o departamento responsável para realizar a manutenção e encaminhar um aviso para os moradores daquela área.


# Requisitos Funcionais
  - RF1: Verificação de anomalia.
     - O registrador verifica a pressão dos canos frequentemente, e quando identificar alguma anomalia, avisa ao sistema.
  - RF2: Alerta de anomalia.
     - Após identificada uma anomalia na pressão, o registrador emite um alerta no sistema para que a companhia de água possa solucionar o problema.
  - RF3: Cortar fornecimento de água.
     - Ocorre o bloqueio do registro de água.
  - RF4: Liberar registro de água.
     - Ocorre a liberação do registro de água.
  - RF5: Alterar circulação de água.
     - Emite sinal para alteração do registro de água.

# Requisitos Não Funcionais
  - Apenas a companhia de água poderá acessar o sistema.
  - Os registradores irão se comunicar com o sistema através de WI-FI.
  - Os registradores serão instalados nas válvulas pré-existentes nas cidades.
  - O sistema terá uma representação visual das áreas monitoradas por cada registrador, representando se a pressão está anormal ou não.
