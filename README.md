# 🌡️ Controle Automático de Ventoinha com Termistor NTC + LCD

Projeto desenvolvido para simular o **acionamento automático de uma ventoinha** utilizando um **sensor NTC (termistor)** e um **Arduino Uno**, com **exibição da temperatura no display LCD 16x2**.

---

## ⚙️ Descrição
O sistema monitora continuamente a temperatura através de um **termistor NTC**.  
Quando a temperatura ultrapassa **30 °C**, a ventoinha é ligada automaticamente.  
A simulação foi feita no **SimulIDE**.

---

## 🧩 Componentes Utilizados
| Componente | Quantidade | Função |
|-------------|-------------|--------|
| Arduino Uno | 1 | Controlador principal |
| Termistor NTC | 1 | Sensor de temperatura |
| Resistor 10 kΩ | 1 | Divisor de tensão |
| Display LCD 16x2 | 1 | Exibição das informações |
| LED (ventoinha simulada) | 1 | Saída de controle |
| Jumpers / Protoboard | - | Ligações |

---

## 💻 Código
O código completo está no arquivo [`Ventoinha_NTC_LCD.ino`](Ventoinha_NTC_LCD.ino).

---

## 🖼️ Simulação
🧩 Projeto simulado no **SimulIDE**.  
![Simulação](Simulacao_SimulIDE.png)

---

## 🧠 Lógica de funcionamento
- Lê o valor analógico do termistor.  
- Converte a resistência em temperatura (equação de Steinhart–Hart).  
- Exibe a temperatura no LCD.  
- Liga a ventoinha (LED) ao ultrapassar 30 °C.

---

## 🏭 Aplicações
- Controle térmico em equipamentos eletrônicos.  
- Projetos de automação didática.  
- Sistemas de ventilação automatizados.

---

## 👨‍💻 Autor
**Lucas — FATEC São José dos Campos**  
🎓 Estudante de Manufatura Avançada  
💡 Foco em Automação e IoT Industrial
