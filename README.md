# Sensor Ultrassônico

### Descrição do Projeto

Este sistema utiliza um ESP32 e um sensor HC-SR04 para medir distâncias e detectar a presença de objetos. O projeto integra hardware e software para monitorar o ambiente em tempo real, fornecendo um alerta visual via LED sempre que um obstáculo é identificado dentro de um limite de proximidade pré-estabelecido.

---

### Funcionamento

O dispositivo opera via ecolocalização, onde o ESP32 comanda o sensor para emitir ondas ultrassônicas que refletem em superfícies próximas. O tempo de retorno do sinal é captado e convertido pelo microcontrolador em centímetros. Caso a distância medida seja inferior a 10 cm, o sistema ativa automaticamente um LED de alerta, desligando-o assim que o objeto se afasta do raio de detecção.

---

### Componentes Utilizados

1x ESP32

1x Sensor HC-SR04

1x LED e Resistor

1x Protoboard e Jumpers

---

### Autor
Rebeca Gomes.
