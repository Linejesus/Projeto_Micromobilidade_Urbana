# Projeto de Curso - Sistema de Micromobilidade Urbana
<br>
<h2> Descrição</h2>
Uma empresa de tecnologia deseja implantar um sistema de gestão para o compartilhamento de 
micromobilidade urbana (bicicletas e patinetes elétricos) em grandes cidades. O objetivo é oferecer uma 
plataforma onde usuários possam localizar veículos disponíveis em um mapa, realizar o desbloqueio via 
aplicativo, utilizar o transporte de forma autônoma e efetuar o pagamento pelo tempo de uso.<br><br>

O sistema deve permitir que a equipe operacional monitore a frota em tempo real, identifique veículos 
com baixa carga de bateria ou necessidade de manutenção e gerencie as "zonas de estacionamento" 
permitidas. <br>

Além disso, a empresa possui um programa de incentivo à mobilidade sustentável:<br>
• Usuários que devolvem veículos em "estações de alta demanda" recebem créditos para a próxima 
viagem.<br>
• Estudantes e professores possuem desconto de 20% no valor do minuto rodado, mediante 
comprovação de vínculo acadêmico.<br>

O sistema deve operar em conformidade com as regulamentações municipais de transporte, garantindo 
que os veículos não sejam estacionados em áreas proibidas e que a velocidade máxima seja limitada 
eletronicamente em zonas de grande circulação de pedestres.

<br><br>
<h2>Escopo </h2>
• Usuários: Poderão consultar a localização e o nível de bateria dos veículos disponíveis no mapa.<br>
• Reserva e Desbloqueio: O usuário poderá reservar um veículo por até 5 minutos ou realizar o 
desbloqueio imediato via leitura de QR Code.<br>
• Gestão de Frota: Administradores poderão cadastrar novos veículos, definir modelos (bicicleta 
ou patinete) e acompanhar o histórico de viagens.<br>
• Monitoramento em Tempo Real: O sistema deve registrar a posição GPS do veículo a cada 
minuto durante o uso.<br>
• Controle de Estados: O sistema deve gerenciar automaticamente os estados do veículo 
(Disponível, Reservado, Em Uso, Manutenção, Bateria Crítica e Recolhido).<br>
• Tarifação e Pagamento: O sistema deve calcular o valor da corrida com base em uma taxa fixa 
de desbloqueio somada ao valor por minuto utilizado. Existem três tipos de pacotes: Bronze (sem 
descontos!), Prata (50% de desconto na taxa de desbloqueio) e Ouro (100% de desconto na taxa 
de desbloqueio OU 50% de desconto na taxa de minutos, o que for mais vantajoso para o cliente). 
Os valores são diferentes por tipo de veículo e por município de operação.<br>
• Integração de Pagamento: O sistema deve integrar-se com gateways de pagamento para 
processar cartões de crédito e carteiras digitais.<br>
• Regras de Estacionamento: O sistema deve validar, via GPS, se o usuário encerrou a viagem 
dentro de uma área permitida antes de finalizar a cobrança.<br>
• Relatórios Operacionais: Geração de relatórios de utilização por região, faturamento diário e 
alertas de veículos parados há mais de 24h.<br>
• Fiscalização e Manutenção: O sistema deve gerar ordens de serviço automáticas para a equipe 
de rua recolher veículos com bateria abaixo de 10% ou reportados com defeito.<br>
• Segurança e Limites: Integração com o firmware do veículo para aplicar limites de velocidade 
em "zonas silenciosas" ou parques, conforme definido no mapa administrativo.
<br><br>
<h2> Desenvolvedores:</h2>
• Aline Rocha de Jesus RA: 22.123.106-1 <br>
• Bianca Silva Oliveira RA: 22.123.113-7 <br>
• Leonardo Souza de Castro RA: 22.123.114-5 <br>
