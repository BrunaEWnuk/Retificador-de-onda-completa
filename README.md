# ⚡Retificador de onda completa 
Utilizado para converter corrente alternada (AC) em corrente contínua (DC) estabilizada em 5V.
  -  Converter tensão AC para DC utilizando uma ponte retificadora.
  -  Filtrar a tensão retificada para reduzir ondulações.
  -  Regular a tensão para um valor constante de 5V usando o regulador 7805.
  -  Fornecer energia estabilizada para cargas eletrônicas, garantindo um funcionamento adequado.

## 🔌 Principais componentes e suas funções: 
**Transformador (TR1 - TRAN-2P3S)**
- Reduz a tensão da rede elétrica para um nível adequado para o circuito. 
- Possui enrolamentos primário e secundário. 
- O primário recebe a tensão alternada (AC) da rede elétrica, e o secundário fornece uma tensão reduzida que será retificada.

**Ponte Retificadora (BR1 - 2W04G)**
- Converte a tensão alternada (AC) do transformador em uma tensão pulsante contínua (DC).
-Formada por quatro diodos que conduzem alternadamente, assim garantindo que a corrente corra sempre na mesma direção na carga.

**Capacitor de Filtro (C1 - 1µF)**
- Reduz a tensão pulsante da ponte retificadora, reduzindo a variação da tensão de saída (ripple).
- Atua como um filtro que armazena energia e libera quando há quedas momentâneas de tensão.

**Capacitor Cerâmico (C2 - 22nF)**
- Reduz ruídos de alta frequência na alimentação.
- Auxilia na estabilidade do regulador de tensão.

**Regulador de Tensão (U1 - 7805)**
- Mantém a saída do circuito estabilizada em 5V DC.
- O pino de entrada (VI) recebe a tensão filtrada, o pino saída (VO) fornece os 5V regulados, e o pino GND é o aterramento.

**Capacitor de Estabilização (C3 - 22nF)**
- Melhora a resposta do regulador 7805, reduzindo ruídos e oscilações na saída.
- E mantém a estabilidade da tensão regulada.

**Resistor (R1 - 220Ω)**
- Serve para limitar a corrente que chega ao LED.
- Preserva o LED contra corrente excessiva.

**LED (D1 - LED-RED)**
- Indica visualmente que há tensão de saída no circuito.
- Acende quando o circuito fornece tensão regulada.

## ⚙️ Funcionamento do Retificador de Onda Completa:

**Transformação da Tensão:**
- O transformador reduz a tensão da rede elétrica para um nível adequado ao circuito.

**Retificação da Onda Completa:**
- A ponte retificadora converte a tensão alternada (AC) em tensão pulsante contínua (DC).
- Durante um semiciclo da entrada, dois diodos conduzem a corrente em uma direção.
- No semiciclo seguinte, os outros dois diodos conduzem, mantendo o fluxo na mesma direção.

**Filtragem:**
- O capacitor C1 suaviza as oscilações da tensão retificada, reduzindo o ripple.

**Regulação da Tensão:**
- O regulador 7805 ajusta a tensão para um valor estável de 5V DC.

**Proteção e Indicação:**
- Os capacitores C2 e C3 eliminam ruídos.
- O resistor R1 protege o LED.
- O LED D1 indica a presença de tensão de saída.

## Esquemático
![image](https://github.com/user-attachments/assets/2d5c50f7-4ca3-4e8b-8ec4-bd8be05c51ed)

## Prática
![image](https://github.com/user-attachments/assets/18677fed-70df-4453-b2a8-278e4ed0c4e9)
![image](https://github.com/user-attachments/assets/756b40cf-7bc9-427d-b816-64dfdf535977)
![image](https://github.com/user-attachments/assets/2d22d07e-e4e5-47e7-a40e-6424dfedf281)
![image](https://github.com/user-attachments/assets/9a72403c-82c8-4750-809f-95ff014f0e68)
![image](https://github.com/user-attachments/assets/3a0d890d-a4ad-49ef-a6a2-12a425891511)
[Assista ao vídeo aqui](https://github.com/user-attachments/assets/22b72177-5efd-41bd-a379-279c5d3d6570)

## PcB
![image](https://github.com/user-attachments/assets/0485b1cc-bf01-471c-8ac0-0e32327e3520)

## 3D
![image](https://github.com/user-attachments/assets/5f78ef44-0033-4234-8754-25963f5015af)
![image](https://github.com/user-attachments/assets/312b232a-e4f4-4df9-9f16-4b0d035c77d3)


