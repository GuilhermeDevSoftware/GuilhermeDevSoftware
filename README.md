# Olá, eu sou o Guilherme!

### Engenharia de Computação | Firmware e Sistemas Embarcados | ESP32 • STM32 • C/C++ • Rust

Sou estudante do **8º semestre de Engenharia de Computação na Unilins**, com foco em **firmware, sistemas embarcados e integração entre hardware e software**.

Desenvolvo projetos com **ESP32 e ESP-IDF em C/C++** e **STM32 com Rust embarcado**, envolvendo aquisição de dados, comunicação sem fio e validação em bancada. Também utilizo **Python e MATLAB** para coleta, análise e interpretação dos resultados.

Minha experiência inclui um estágio na **Águia Rádio Comando**, com atividades de manutenção e desenvolvimento de placas de rádio comando, soldagem de componentes e investigação de falhas em circuitos.

Tenho interesse em entender o sistema completo: consultar documentação e datasheets, configurar periféricos, observar sinais no hardware e verificar se os resultados correspondem ao comportamento esperado. Também venho direcionando meus estudos para **Linux embarcado, processamento de sinais e inteligência artificial em dispositivos**.

---

## 💻 Tecnologias e conhecimentos

* **Linguagens:** C, C++, Rust embarcado e Python; Assembly 8051 como base de programação de baixo nível.
* **Microcontroladores e plataformas:** ESP32, STM32 Nucleo-F446RE e Arduino.
* **Firmware:** ESP-IDF, aplicações com FreeRTOS, integração de periféricos, aquisição de dados e depuração por logs.
* **Interfaces e comunicação:** UART, I²C, SPI, Wi-Fi, MQTT, HTTP e comunicação LoRa com módulos SX1278.
* **Análise de dados:** coleta e organização de dados em Python, arquivos CSV, estatística e visualização de resultados no MATLAB.
* **Hardware e baixo nível:** GPIO, registradores, memória, arquitetura de computadores, leitura de datasheets, multímetro e analisador lógico.
* **Ferramentas e ambiente:** Git/GitHub, Linux/WSL, VS Code, Cargo, probe-rs e Arduino IDE; estudos de Linux embarcado com Buildroot.

<p>
  <img alt="C" height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" />
  <img alt="C++" height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" />
  <img alt="Rust" height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" />
  <img alt="Python" height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
  <img alt="MATLAB" height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matlab/matlab-original.svg" />
  <img alt="Linux" height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />
  <img alt="Git" height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
</p>

---

## 📁 Projetos em destaque

### 📡 LoRa Link Analyzer — STM32 + ESP32

**Projeto concluído**, com implementação e validação de um enlace **LoRa ponto a ponto** entre um **STM32 com Rust embarcado** e um **ESP32 com C e ESP-IDF**, utilizando módulos SX1278 de 433 MHz.

O sistema implementa comunicação bidirecional com **confirmação de recebimento (ACK), timeout, retransmissões e identificação de pacotes duplicados**. Os testes incluíram perda de comunicação e recuperação do enlace após o retorno dos dispositivos à área de cobertura.

Os dados foram coletados em **CSV com Python** e analisados no **MATLAB**, com comparação de sessões e avaliação de **RSSI, SNR, pacotes únicos, duplicatas e sequências ausentes**.

**Aprendizados:** integração via SPI, protocolo de comunicação, tratamento de falhas, avaliação experimental de enlaces e análise de dados.

[Ver projeto →](https://github.com/GuilhermeDevSoftware/Lora-Link-Analyzer)

### 📍 Telemetria GPS com ESP32 e ESP-IDF

Projeto de telemetria veicular com **ESP32, GPS e firmware em C com ESP-IDF**, integrando coleta de localização, armazenamento em microSD e comunicação via MQTT. Inclui ferramentas em Python para persistência e análise dos dados, além de atualização de firmware via OTA.

**Aprendizados:** comunicação UART, processamento de mensagens NMEA, tarefas com FreeRTOS e integração entre firmware e aplicações no computador.

[Ver projeto →](https://github.com/GuilhermeDevSoftware/esp32-gps-telemetry-idf)

### 🌡️ Gateway Ambiental com ESP32 e Arduino

Projeto de gateway ambiental com **ESP32 e Arduino**, voltado ao estudo de monitoramento e integração de dispositivos embarcados.

[Ver projeto →](https://github.com/GuilhermeDevSoftware/GATEWAY-AMBIENTAL-ESP32-ARDUINO)

### 🔎 Analisador de Sistemas Embarcados

Projeto educacional com **ESP32** para estudar sinais digitais e interfaces de comunicação em bancada, com testes de GPIO e UART, medições com analisador lógico e registro dos resultados.

**Aprendizados:** temporização, comunicação serial e comparação entre o comportamento esperado pelo código e os sinais observados no hardware.

[Ver projeto →](https://github.com/GuilhermeDevSoftware/embedded-systems-analyzer)

### 🧮 Cálculo de CPF em Assembly

Implementação de algoritmo para cálculo e verificação de CPF em **Assembly**, exercitando manipulação de registradores, operações aritméticas e controle de fluxo.

**Aprendizados:** programação de baixo nível e relação entre instruções, dados e execução do programa.

[Ver projeto →](https://github.com/GuilhermeDevSoftware/Calculo_CPF_Assembly)

---

## 🛠️ Em desenvolvimento

### Monitoramento de energia elétrica sem fio — TCC

Desenvolvo meu **Trabalho de Conclusão de Curso** com o objetivo de monitorar o consumo de energia por meio de **leitura óptica externa de um medidor digital**, com envio dos dados sem fio e visualização em uma plataforma web.

A etapa inicial de bancada validou a detecção óptica com **fototransistor e comparador LM393**, obtendo níveis lógicos estáveis para leitura pelo ESP32. O firmware está sendo desenvolvido em **C++ com ESP-IDF**.

As próximas etapas envolvem a adaptação da interface óptica ao medidor disponível na faculdade e o estudo da comunicação infravermelha conforme o **protocolo ABNT CODI/NBR 14522**, além da transmissão e apresentação dos dados.

---

## 📚 Estudos e interesses atuais

* Firmware em C/C++, ESP-IDF e organização de aplicações com FreeRTOS.
* Rust embarcado no STM32, configuração de periféricos e depuração.
* Interfaces UART, I²C e SPI, com testes e análise de sinais em bancada.
* MATLAB para análise de dados experimentais, estatística e visualização.
* Linux embarcado e geração de imagens com Buildroot.
* Fundamentos de visão computacional e inteligência artificial em dispositivos, com interesse em detecção de falhas.

Pretendo aprofundar meus conhecimentos em **redes CAN, desenvolvimento de drivers e processamento de sinais**, conectando esses estudos a projetos práticos e à pesquisa aplicada.

---

## 🚀 Objetivo profissional

Atuar em **desenvolvimento de firmware, sistemas embarcados e pesquisa e desenvolvimento**, especialmente em comunicação entre dispositivos, instrumentação e aplicações industriais.

Busco oportunidades de **estágio e posições de entrada na área**, contribuindo com minha formação em Engenharia de Computação, experiência em bancada e projetos documentados.

Também tenho como objetivo seguir para o **mestrado e a carreira científica**, aproximando sistemas embarcados, análise de sinais e inteligência artificial de problemas reais de engenharia.

Valorizo código compreensível, documentação e validação no hardware como parte do desenvolvimento.

---

## 📬 Conecte-se comigo

* **LinkedIn:** [Guilherme Costa](https://www.linkedin.com/in/guilherme-costa-a00463291/)
* **E-mail:** [guizeracostasilva@outlook.com](mailto:guizeracostasilva@outlook.com)
* **GitHub:** [@GuilhermeDevSoftware](https://github.com/GuilhermeDevSoftware)
* **Instagram:** [@guiilhermecosta01](https://instagram.com/guiilhermecosta01)

Obrigado pela visita! 🚀
