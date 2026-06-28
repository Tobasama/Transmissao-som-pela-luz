Projeto desenvolvido para a disciplina ECA409 e ECA407.

Instituição: Instituto Mauá de Tecnologia.

## Descrição

Este projeto consiste em um sistema de comunicação óptica capaz de transmitir um sinal de áudio utilizando um feixe laser. Uma música reproduzida em um computador é convertida em um sinal elétrico, amplificada e utilizada para modular a intensidade luminosa de um laser. No receptor, um LED é utilizado como fotodetector, convertendo novamente as variações da luz em um sinal elétrico. Após uma segunda etapa de amplificação, o sinal é enviado para um Raspberry Pi Pico, responsável pelo processamento e reprodução do áudio.

---

## Objetivo

Desenvolver um sistema capaz de transmitir áudio sem fio utilizando um feixe laser como meio de comunicação e reproduzir a música através do Raspberry Pi Pico.

---

## Funcionamento

O sistema opera conforme o fluxo abaixo:

```
Computador
    │
    ▼
Sinal de Áudio
    │
    ▼
Amplificador
    │
    ▼
Laser
    │
    ▼
Transmissão Óptica
    │
    ▼
LED (Fotodetector)
    │
    ▼
Amplificador
    │
    ▼
Raspberry Pi Pico
    │
    ▼
Filtro passa-baixas
    │
    ▼
Saída de Áudio
```

---

## Componentes Utilizados

- Computador
- Raspberry Pi Pico
- Módulo Laser
- LED (utilizado como fotodetector)
- Circuito amplificador (transmissor)
- Circuito amplificador (receptor)
- Alto-falante
- Resistores
- Capacitores
- Protoboard
- Cabos de conexão
- Fonte de alimentação

---

## Princípio de Funcionamento

1. O computador reproduz uma música.
2. O sinal de áudio é amplificado.
3. O laser recebe esse sinal e varia sua intensidade luminosa.
4. O LED receptor detecta as variações de luz.
5. O LED gera um pequeno sinal elétrico correspondente ao áudio.
6. O sinal é amplificado.
7. O Raspberry Pi Pico recebe o sinal e realiza sua modulação.
8. O Sinal passa por um filtro passa-baixas.
9. O Sinal se torna som.

---

## Resultados

O sistema foi capaz de transmitir o sinal de áudio por comunicação óptica. A utilização do LED como receptor permitiu recuperar as informações enviadas pelo laser, sendo necessária uma etapa adicional de amplificação antes do processamento pelo Raspberry Pi Pico.


---

## Possíveis Melhorias

- Utilização de fotodiodo em substituição ao LED receptor.
- Controle automático de ganho.
- Maior alcance da transmissão.
- 
<img width="1092" height="782" alt="WhatsApp Image 2026-06-22 at 19 32 08" src="https://github.com/user-attachments/assets/a729725e-b12c-4898-b5a9-e9eaef196c55" />



<img width="1037" height="153" alt="image" src="https://github.com/user-attachments/assets/728c6263-5d8a-4519-88ce-74b06ead43fc" />

---

## Autores

Pethros Tsiloufas 21.01351-9
Giovanni Corradini Nunes 23.00909-8
Giovanna Macarroni Freire 23.00991-8
Thomas Schneider Mourão  23.01209-9


