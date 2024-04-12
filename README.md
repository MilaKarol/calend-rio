# README
 
Este trabalho foi passado na aula do curso de Desenvolvimento Web I, ultilizando css, javascript e hatml.

## Estrutura do Projeto
 
Esses são os três arquivos principais:
 
1. `index.html`: Este arquivo HTML é o principal e contém a estrutura básica da página web. Ele inclui o calendário e o formulário que permite aos usuários selecionarem uma cor e um dia para serem destacados no calendário.
 
2. `calendar.css`: Este arquivo CSS define os estilos para a página web. Ele inclui estilos para o calendário, os elementos do formulário e as divisões da página.

3. `calendar.js`:  Este arquivo JavaScript contém a lógica necessária para colorir o dia selecionado no calendário com a cor escolhida pelos usuários.
 
## HTML (index.html)
 
O arquivo HTML compõe a estrutura fundamental da página web e inclui:

-Declaração do tipo de documento (<!DOCTYPE html>).
-Definição do idioma (<html lang="en">).
-Inclusão de metadados, como codificação de caracteres e configuração da viewport.
-Links para o arquivo de estilos CSS e script JavaScript.
-Uma tabela (<table>) para exibir o calendário.
-Um formulário para seleção de cor e dia, permitindo ao usuário colorir o calendário.
-Informações sobre diferentes tipos de caminhões.
 
![](html1.png) 
![](html2.png)
![](html3.png)
![](html4.png)
 
## CSS (calendar.css)
 
O arquivo CSS define os estilos para os elementos na página web, incluindo:

-Estilos para o corpo da página, a tabela do calendário e os elementos do formulário.
-Define cores de fundo, bordas, alinhamento de texto e margens para os elementos.
 
![](css1.png)

![](css2.png)
 
## JavaScript (calendar.js)
 
O arquivo JavaScript contém a função colorirDia(), que é acionada quando o usuário clica no botão de envio no formulário. Esta função obtém o dia e a cor selecionados pelo usuário e colore o dia correspondente na tabela do calendário.


![](javascript.png)
 
---
 
Este README fornece uma visão geral do projeto e explica a estrutura do código HTML, CSS e JavaScript.
 
# Funcionalidades do Calendário: 
Representação dos Veículos
Os quatro veículos serão representados por cores distintas no calendário. Por exemplo, um caminhão pode ser azul, outro verde, outro rosa e outro roxo.

# Agendamento dos Fretes:
Cada dia do calendário corresponderá a um dia do mês. Os dias em que um veículo já tem um frete agendado serão coloridos com a cor correspondente a esse veículo. Se um veículo já realizou três fretes no mês, os dias restantes do mês para esse veículo não estarão disponíveis para agendamento.

# Regras de Agendamento:
Um veículo não pode fazer mais de um frete no mesmo dia, portanto, cada dia do calendário só pode ser agendado por um único veículo. Além disso, cada veículo pode realizar até três fretes por mês. Assim, uma vez que um veículo tenha feito três fretes, os dias restantes do mês para esse veículo não estarão disponíveis para agendamento.

# Implementação:
O JavaScript será responsável por controlar as interações do usuário com o calendário. Quando o usuário seleciona um dia e uma cor (representando um veículo) para agendar um frete, o JavaScript verifica se o veículo já realizou três fretes no mês. Se o veículo ainda tiver fretes disponíveis, o JavaScript verifica se o dia selecionado está disponível para agendamento (ou seja, se o dia já não está agendado por outro veículo). Se o dia estiver disponível, o JavaScript colore o dia com a cor do veículo selecionado e registra o agendamento. Se o veículo já realizou três fretes ou o dia já está agendado, uma mensagem de erro é exibida ao usuário, informando que o agendamento não é possível.

# Benefícios:
O calendário oferece uma visualização clara dos dias disponíveis para agendamento de fretes. As cores dos veículos facilitam a identificação e a organização dos agendamentos. Além disso, as regras de agendamento garantem uma distribuição equitativa dos fretes entre os veículos e evitam conflitos de agendamento. Com essa implementação, a equipe de agendamento da empresa Alpha terá uma ferramenta eficaz para gerenciar os agendamentos de fretes de forma organizada e eficiente.


 
![](calendario.png)
 
# Autor
* Milena Caroline de Almeida
 
<img src="mila.png" width=200 >


