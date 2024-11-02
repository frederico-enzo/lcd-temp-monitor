# lcd-temp-monitor  Criado July 10, 2022

![LCD Temp Monitor](docs/Termômetro-digital-Sensor-Temperatura.png)

## Descrição
Este projeto demonstra a construção de um termômetro digital simples e eficaz, utilizando um microcontrolador Arduino e um sensor de temperatura. O dispositivo é capaz de medir a temperatura ambiente e exibir os valores em graus Celsius e Fahrenheit em um display LCD. Além disso, o sistema incorpora um sistema de alertas visuais, indicando condições de temperatura extremas através de LEDs.

## Componentes Necessários
* **Microcontrolador:** Arduino Uno (ou compatível)
* **Sensor de Temperatura:** LM35 (ou similar)
* **Display:** LCD 16x2
* **Resistores:** Conforme a especificação do sensor
* **Fios:** Para conexões
* **Placa de Prototipagem:** Breadboard
* **LEDs:** Vermelho e verde (opcional, para os alertas)

## Funcionamento
1. **Leitura da Temperatura:** O sensor de temperatura coleta os dados da temperatura ambiente e envia um sinal analógico para o Arduino.
2. **Processamento:** O Arduino converte o sinal analógico em um valor digital representando a temperatura e realiza os cálculos necessários para exibir os valores em Celsius e Fahrenheit.
3. **Exibição:** Os valores da temperatura são exibidos no display LCD de forma clara e organizada.
4. **Alertas:** LEDs são acionados para indicar temperaturas abaixo de 0°C (vermelho) e acima de 40°C (vermelho), alertando o usuário sobre condições extremas.



## Utilização
1. Conecte o Arduino ao computador via USB.
2. Carregue o código para o Arduino.
3. Alimente o circuito.
4. A temperatura será exibida no display LCD.
