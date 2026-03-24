# Projeto Aurora Singer – Simulação de Decisão de Lançamento

## 📖 Sobre o projeto

Este projeto simula a análise de condições para o lançamento de uma nave espacial com base em dados de telemetria.

A partir de um dataset com informações como temperatura, bateria, pressão e autonomia, o sistema avalia automaticamente se a nave está apta para decolagem, utilizando regras de validação pré-definidas.

Além disso, o projeto realiza uma análise energética para verificar se há autonomia suficiente para a execução segura da decolagem.

---

## Objetivos

* Validar condições críticas de lançamento com base em dados
* Simular um processo de tomada de decisão automatizado
* Avaliar a autonomia energética da nave antes da decolagem

---

## Tecnologias utilizadas

* Python
* Pandas
* Random

---

## Estrutura do projeto

```
Projeto-Aurora-Singer
 ┣  Projeto_Aurora_Singer.ipynb
 ┣  dataset_telemetria_sintetico_anomalias_ptbr.csv
 ┣  README.md
```

---

## ⚙️ Funcionamento

O projeto segue as seguintes etapas:

1. Leitura do dataset de telemetria
2. Exploração inicial dos dados (`DataFrame.head()` e `DataFrame.info()`)
3. Seleção aleatória de um cenário de lançamento
4. Aplicação de regras de validação
5. Definição da decisão final:

   * READY (Pronto para decolagem)
   * ABORT (Decolagem abortada)

---

## Regras de validação

* Temperatura interna: 18 a 35 °C
* Temperatura externa: -5 a 30 °C
* SOC (bateria): ≥ 60%
* Pressão do tanque: 95 a 145 bar
* Módulos críticos: operacionais
* Telemetria: ativa
* Autonomia mínima: ≥ 45 minutos

---

## Análise energética

O sistema calcula:

* Capacidade total da bateria (kWh)
* Energia disponível
* Consumo estimado na decolagem
* Consumo real considerando perdas
* Autonomia estimada do sistema

Esses cálculos complementam a decisão final, garantindo maior segurança no processo.

---

## Fluxograma do processo

![Fluxograma](assets/FLuxograma.png)

---

## Como executar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/Projeto-Aurora-Singer/Projeto-1---Lan-amento-Aurora-Singer.git
```

### 2. Acessar a pasta

```bash
cd Projeto-1---Lan-amento-Aurora-Singer
```

### 3. Instalar dependências

```bash
pip install pandas
```

### 4. Executar o notebook

* Abrir o arquivo `.ipynb` no Google Colab ou Jupyter Notebook
* Executar todas as células

---

## Exemplo de saída

O sistema irá exibir:

* Dados do cenário selecionado
* Resultado da decisão (READY ou ABORT)
* Cálculos energéticos

---

## Aprendizados

Durante o desenvolvimento deste projeto, foi possível compreender:

* A importância da validação de dados em sistemas críticos
* O uso de regras de negócio para tomada de decisão automatizada
* A integração entre análise de dados e lógica operacional
* O papel da eficiência energética em sistemas computacionais

---

## Uso de Inteligência Artificial

A IA foi utilizada para:

* Geração do dataset sintético
* Identificação de anomalias
* Análise de riscos operacionais

---

## Considerações finais

Este projeto demonstra como dados podem ser utilizados para apoiar decisões críticas em contextos operacionais complexos, como sistemas aeroespaciais.

---

## Autores

* Mayara Luisa Vicente Rosa
* Gabriel Coutinho Barcelos
* Pedro Henrique de Souza Elias
* Gabriel Luis de Lima Ramos
