# Projeto: Controle de LEDs RGB e Buzzer com Raspberry Pi Pico W

## Descrição
Este projeto utiliza a comunicação serial para controlar LEDs RGB e um buzzer conectado a uma Raspberry Pi Pico W. A comunicação é realizada através do protocolo UART, permitindo que comandos sejam enviados via monitor serial para acionar os dispositivos.

## Funcionalidades
1. **Controle dos LEDs RGB:**
   - **RED:** Liga o LED vermelho.
   - **BLUE:** Liga o LED azul.
   - **GREEN:** Liga o LED verde.
   - **WHITE:** Liga todos os LEDs simultaneamente.
   - **OFF:** Desliga todos os LEDs.
2. **Controle do Buzzer:**
   - **BUZZER:** Aciona o buzzer por 2 segundos com uma frequência de 1 kHz.

## Hardware Utilizado
- **Microcontrolador:** Raspberry Pi Pico W.
- **LEDs RGB:** Conectados aos pinos GPIO 13 (vermelho), 12 (azul) e 11 (verde).
- **Buzzer:** Conectado ao pino GPIO 21.

## Pinos GPIO Utilizados
| Componente  | GPIO |
|-------------|------|
| LED Vermelho| 13   |
| LED Azul    | 12   |
| LED Verde   | 11   |
| Buzzer      | 21   |

## Como Usar
1. **Conexão do Hardware:** Conecte os LEDs e o buzzer aos pinos GPIO da Raspberry Pi Pico W conforme especificado.
2. **Envio do Código:** Compile o programa e envie-o para a placa utilizando um ambiente de desenvolvimento compatível.
3. **Envio de Comandos:** Utilize o monitor serial para enviar comandos e controlar os dispositivos.

## Fluxo do Programa
1. Inicialização dos pinos GPIO.
2. Monitoramento do monitor serial para ler os comandos enviados.
3. Controle dos LEDs ou do buzzer com base nos comandos recebidos.

## Exemplo de Comandos
- `RED`: Liga o LED vermelho.
- `BLUE`: Liga o LED azul.
- `GREEN`: Liga o LED verde.
- `WHITE`: Liga todos os LEDs simultaneamente.
- `OFF`: Desliga todos os LEDs.
- `BUZZER`: Aciona o buzzer por 2 segundos.

## Dependências
- Biblioteca `pico/stdlib.h` para controle de GPIO e gerenciamento de tempo.

## Observações
- Certifique-se de que o monitor serial esteja configurado corretamente para comunicar-se com a placa Raspberry Pi Pico W.
- Utilize uma fonte de alimentação confiável para garantir o funcionamento adequado dos LEDs e do buzzer.

## Vídeo Demonstrativo
Adicione aqui o link para o vídeo de demonstração do projeto:
[https://drive.google.com/file/d/1IHV75V65DGmhS8Nq8Ut0W0kyzodRiMeA/view?usp=sharing](#)

## Licença
Este projeto está sob a licença MIT. Você é livre para modificar e usar o código conforme necessário, desde que mantenha a referência ao autor original.

---
**Autor:** Theógenes Gabriel Araújo de Andrade  
**Data:** 18/01/2025



