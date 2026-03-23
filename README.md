# Projeto-1---Lançamento-Aurora-Singer

# 🚀 Projeto Aurora Singer – Simulação de Decisão de Lançamento

## 📖 Sobre o projeto

Este projeto simula a análise de condições para o lançamento de uma nave espacial com base em dados de telemetria.

A partir de um dataset com informações como temperatura, bateria, pressão e autonomia, o sistema avalia automaticamente se a nave está apta para decolagem, utilizando regras de validação pré-definidas.

Além disso, o projeto realiza uma análise energética para verificar se há autonomia suficiente para a execução segura da decolagem.

---

## 🎯 Objetivo

O objetivo deste projeto é:

- Validar condições críticas de lançamento com base em dados
- Simular um processo de tomada de decisão automatizado
- Avaliar a autonomia energética da nave antes da decolagem

---

## 📊 Tecnologias utilizadas

- Python
- Pandas
- Random

---

## 📁 Estrutura do projeto

- `dataset`: dados simulados de telemetria
- `notebook`: análise e simulação do lançamento
- `README.md`: documentação do projeto

---

## ⚙️ Funcionamento

O projeto segue as seguintes etapas:

1. Leitura do dataset de telemetria :contentReference[oaicite:0]{index=0}  
2. Exploração inicial dos dados (estrutura e tipos)  
3. Seleção aleatória de um cenário de lançamento  
4. Aplicação de regras de validação:
   - Temperatura interna e externa
   - Estado de carga da bateria (SOC)
   - Pressão do tanque
   - Status dos módulos críticos
   - Comunicação de telemetria
   - Autonomia mínima  
5. Definição da decisão final:
   - **READY (pronto para decolagem)**
   - **ABORT (decolagem abortada)**

---

## ⚡ Análise energética

O projeto também calcula:

- Capacidade total da bateria (kWh)
- Energia disponível
- Consumo estimado durante a decolagem
- Consumo real considerando perdas
- Autonomia estimada do sistema

Esses cálculos complementam a decisão final, garantindo maior segurança no processo.

---

## 📈 Resultado

O sistema permite simular diferentes cenários de lançamento e tomar decisões com base em regras objetivas.

Além disso, demonstra como dados podem ser utilizados para apoiar decisões críticas em contextos operacionais complexos.

---

## 💡 Aprendizados

Durante o desenvolvimento deste projeto, foi possível compreender a importância de:

- Validação de dados antes da tomada de decisão
- Uso de regras de negócio em sistemas automatizados
- Integração entre análise de dados e lógica operacional
