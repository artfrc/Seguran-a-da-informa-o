# Aula 01 – Conceitos de segurança 

## Objetivo da aula: 
Entender o motivo de estudar segurança para redes de computadores, os três pilares para segurança, alguns tipos de ataques e também mecanismos de defesas contra esses ataques. 

## Tópicos abordados: 

* Motivação para o estudo de segurança 
* Pilares de segurança 
* Ataques 
* Mecanismos de defesa 
* Explicação dos tópicos: 

## Motivação para o estudo de segurança 

A importância dos computadores e das redes está cada vez maior. Isso acontece devido os serviços prestados por algumas empresas serem tão essenciais quanto ao fornecimento de luz (energia elétrica). 

As redes também são utilizadas para acessar dados sensíveis e também realizar transações sensíveis. Exemplos: 

* Compra de algum produto pela internet; 
* Transações bancárias. 

Essas informações sensíveis atraem pessoas mal intencionadas (hackers), elas formam até grupos anônimos. Muitas vezes, as ações dessas pessoas envolvem dinheiro. Exemplo de ações criminosas: 

* Roubo de armas utilizadas pela NSA; 
* Roubo de senhas de usuários de grandes plataformas; 
* Invasão e vazamento de dados. 

Problemas de segurança podem causar: 

* Perdas financeiras; 
* Sujar a reputação de empresas e até pessoas comuns; 
* Problemas com a justiça. 

__COMO TRATAR TODOS ESSES PROBLEMAS? MECANISMOS DE SEGURANÇA:__

Temos diversos mecanismos, como: antivírus, firewall, criptografia. Logo, nessa matéria iremos estudar o funcionamento dos principais modelos de criptografia. 

* Pilares de segurança 
* CID – confidencialidade, integridade e disponibilidade. É um modelo simples, mas muito aplicado. 

<span style= 'color:red'>Confidencialidade </span>: informações não podem ser acessadas por pessoas não autorizadas. Exemplo: Comunicação entre duas pessoas, onde uma terceira pessoa mesmo que consiga interceptar uma mensagem, ela não irá conseguir ler a mensagem. 

<span style= 'color:red'>Integridade</span>: sistemas e informações só são modificados dentro de condições previstas, ou seja, como no exemplo anterior. Um terceiro que interceptar a mensagem não irá conseguir interceptar a mensagem e trocar o conteúdo dela e enviar a mensagem. A pessoa que recebe a mensagem precisa de mecanismos para verificar se a mensagem foi alterada. 

<span style= 'color:red'>Disponibilidade </span>: dados e sistemas estão disponíveis para quem tem direito de utilizá-los. Seguindo o exemplo anterior, duas pessoas X e Y utilizando um canal para uma comunicação, um terceiro Z não autorizado tentando conversar com algum dos dois. Então a disponibilidade deve fornecer que X sempre esteja disponível para atender Y (ou o oposto). Existem ataques chamados de negação de serviço (DOS – Denial of service), afetam a disponibilidade. Nesse ataque, um terceiro não autorizado esgota os recursos do canal, não permitindo um agente autorizado utilizar o canal. 

Também temos outros conceitos complementares: autenticidade, não repúdio (irretratabilidade). 

## Ataques 

Ataques são ameaças que violam a confidencialidade, integridade e disponibilidade. 

__Ataques passivos:__

Obter informações a partir de monitoramento de comunicações. 

Tipos: vazamento do conteúdo da mensagem e análise de tráfego. 

Exemplo: copiar informação do repositório de sua empresa e vender. Note que neste ataque não houve modificação dos dados. 

__Ataques ativos:__

Modificação do fluxo de dados ou criação de um fluxo falso. 

Tipos: disfarce, repasse, modificação da mensagem e negação de serviço. 

Exemplo: usar um algoritmo de força-bruta para tentar diversas combinações de senhas até conseguir o acesso. 

## Mecanismos de defesa 

Políticas de segurança: regras que devem ser elaboradas e seguidas por funcionários de uma empresa, por exemplos: 

* Backups são feitos com qual frequência? Quais dados? Onde será armazenado? 

* Segurança no acesso físico. Quem pode entrar e quando. 

* Conscientização dos funcionários 

* Atualizações constantes de antivírus 

__Mecanismos tecnológicos__: Firewall. Por exemplo: em casa quando utilizamos o computador ou celular para acessar a internet, temos o roteador que checa as informações que vem e vão. E no meio dessa análise do tráfego ele analisa essas informações com base em um conjunto de regras, são regras simples, investigando o cabeçalho dos pacotes, que pode bloquear um pacote se não atender as regras e descartá-lo, isso se chama filtros de pacotes. 

__Sistemas de detecção de intrusão <span style= 'color:red'>(IDS – Intrusion Detection System)</span>__:  verifica se houve uma tentativa de acesso não autorizado ao sistema. Baseado em assinaturas ou comportamento normal da rede. 	Tem problema de alarmes falsos, ou seja, deixar um pacote não autorizado entrar na rede ou um autorizado ser bloqueado. 

* Antivírus: Detecção, identificação e remoção do vírus. AVG, Avast, Mcafee, etc. 

* Protocolos criptográficos: serviço que permite a confidencialidade entre emissor e destino. SSL/TLS, IpSec. 

## Conclusão: 

É importante estudar segurança pois devido as informações sensíveis fornecidas por empresas, hackers podem querer roubar dados em troca de dinheiro. Temos três pilares para seguir que irão ajudar e muito nessa segurança. Existem diferentes tipos de ataques (passivos e ativos), sendo os passivos mais fáceis de reconhecer. E por último, temos mecanismos de defesas, sendo o Firewall o mais famoso.	 