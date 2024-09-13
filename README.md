# Integração Intelbras solar para home assistant

Este sensor foi projetado para coletar dados de inversores Intelbras (fabricados pela Growatt), oferecendo aos usuários uma escolha de vários servidores de endpoint alternativos durante a configuração. As opções disponíveis incluem o servidor da Intelbras e mantém a compatibilidade com os servidores da Growatt, assim como na integração original.

Uma vez integrado, o sensor faz login na conta Intelbras ou Growatt do usuário e acessa a primeira "Planta". Em seguida, ele recupera os inversores associados a esta planta e gera sensores para esses inversores, bem como sensores gerais da planta.


Creditos
-------
Esta integração foi baseada na [integração original da Growatt] [original], mantida pela comunidade do home assistant.


[original] https://www.home-assistant.io/integrations/growatt_server
