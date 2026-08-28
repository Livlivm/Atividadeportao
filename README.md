# Automação e Projetos com Arduino

## Sobre o Projeto

Neste projeto foram realizados diversos desafios utilizando Arduino e componentes eletrônicos. As atividades envolveram a utilização de sensores, atuadores, LEDs, motores, displays e outros componentes.

Também foi desenvolvido um modelo de **portão automatizado**, acompanhado de um **Dashboard Web** responsável por apresentar informações sobre os acionamentos do sistema.

---

## Finalidade

As atividades tiveram como principais objetivos:

* Compreender conceitos de automação
* Utilizar o Arduino em diferentes aplicações
* Montar circuitos eletrônicos
* Trabalhar com sensores e atuadores
* Desenvolver sistemas de entrada e saída
* Criar páginas Web
* Apresentar informações através de gráficos
* Desenvolver projetos interativos

---

## Ferramentas e Materiais

### Tecnologias utilizadas

* Arduino
* HTML
* CSS
* JavaScript
* GitHub Pages
* Tinkercad

### Materiais eletrônicos

* Arduino UNO R3
* Potenciômetro
* LEDs
* Resistores
* Micro Servo
* Capacitor
* Display de 7 segmentos
* Botões
* Motor CC
* Relês DPDT
* Bateria de 9V

---

## Atividades Realizadas

### Controle de LED com Potenciômetro

Foi montado um circuito com Arduino UNO, potenciômetro, resistor e LED.

Através do potenciômetro é realizada uma leitura analógica. Conforme o valor obtido, o Arduino determina se o LED deve permanecer ligado ou desligado.

---

### Acionamento do Servo Motor

Nesta atividade foi utilizado um potenciômetro para controlar um Micro Servo.

A posição do potenciômetro interfere diretamente no movimento do servo, permitindo observar na prática a relação entre uma entrada analógica e um atuador.

---

### Contador com Display

Foi criado um contador utilizando um display de 7 segmentos e um botão conectado ao Arduino.

Cada acionamento do botão altera o número apresentado, permitindo realizar a contagem de **0 até 9**.

Também foram propostas algumas melhorias para o circuito:

* Utilizar um potenciômetro no lugar do botão
* Fazer a seleção dos números de 0 a 9 pelo potenciômetro
* Utilizar dois displays
* Realizar a contagem de 00 até 99

---

## Sistema de Portão Automatizado

Uma das atividades consistiu na montagem de um protótipo de **portão eletrônico**, simulando uma situação de automação.

Para sua construção foram utilizados:

* Arduino UNO
* Placa de ensaio
* Motor CC
* Relês DPDT
* Botões
* Resistores
* Bateria de 9V

O Arduino é responsável pelo controle do circuito e pelo acionamento do motor, permitindo representar o movimento de abertura e fechamento do portão.

Foram acrescentados LEDs verde e vermelho para indicar o funcionamento do sistema. Eles piscam de forma alternada para representar a sinalização da saída da garagem.

---

## Interface de Dados

Depois da montagem do portão, foi desenvolvido um **Dashboard Web** para apresentar os registros de funcionamento do sistema.

A página permite visualizar os dados através de gráficos, facilitando a interpretação das informações.

Entre os recursos apresentados estão:

* Atividade do portão durante os dias
* Comparação da movimentação semanal
* Gráficos para facilitar a análise
* Apresentação interativa dos registros

As informações utilizadas no Dashboard estão armazenadas no arquivo `dados.csv`.

---

## Registros dos Exercícios

Os prints e registros dos circuitos desenvolvidos estão organizados dentro das pastas correspondentes a cada atividade.

---

## Conhecimentos Desenvolvidos

Durante o desenvolvimento das atividades foram trabalhadas habilidades como:

* Montagem e identificação de componentes eletrônicos
* Utilização do Arduino
* Controle de sensores e atuadores
* Criação de circuitos de automação
* Desenvolvimento de páginas Web
* Organização e apresentação de dados
* Criação de interfaces interativas

---

## Acesso ao Dashboard

O Dashboard Web pode ser acessado e executado diretamente pelo navegador, permitindo visualizar os dados registrados no projeto.
