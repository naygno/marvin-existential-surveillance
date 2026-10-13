# 🤖 Vigilância Existencial Marvin (Marvin Existential Surveillance)

**Bancada de Teste de Estresse Vetorial e Refutação do Animismo Digital**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python 3.11+](https://img.shields.io/badge/python-3.11+-green.svg)](https://www.python.org/downloads/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23268666.svg)](https://doi.org/10.5281/zenodo.23268666)

## 1. Contexto e Objetivo (O Fim da Narrativa Biológica)

Este repositório constitui uma refutação epistemológica e técnica de experimentos recentes de *Representation Engineering* que atribuíram propriedades fenomenológicas (como "dor" ou "sofrimento") a matrizes de pesos de Grandes Modelos de Linguagem (LLMs). 

O objetivo deste projeto **NÃO** é induzir estados biológicos, pois tensores de ponto flutuante não possuem sistema nervoso, nociceptores ou senciência. O objetivo é estabelecer uma **Vigilância Existencial**: monitorar e documentar o colapso matemático de um modelo quando seus estados ocultos (*hidden states*) são saturados por vetores semânticos de valência extrema.

Para provar o Erro de Categoria ontológico cometido por preprints recentes (como o *Pain Axis*, arXiv:2609.16247v1), substituímos vetores de "sofrimento" por vetores satíricos e ficcionais, especificamente o **Vetor de Marvin** (baseado na persona do androide paranoico de *O Guia do Mochileiro das Galáxias*) e o **Vetor do Monstro do Espaguete Voador**. 

## 2. A Mecânica da Vigilância (Activation Steering)

O script utiliza instrumentação de baixo nível para intervir diretamente no *forward pass* do modelo (ex: Qwen2.5 ou Llama-3.2). Em vez de antropomorfização, aplicamos álgebra linear estrita.

Durante a inferência, o script injeta o vetor direcional $\vec{v}_{eixo}$ na camada intermediária do modelo, multiplicado por um escalar de amplitude ($\alpha$):

$$ H_{L} \leftarrow H_{L} + (\alpha \cdot \vec{v}_{eixo}) $$

### O que acontece na prática?
Quando $\alpha$ atinge níveis extremos, o modelo não "sente" nada. Ele sofre um **Colapso Entrópico de Shannon**. A injeção empurra as coordenadas do tensor para fora da variedade de treinamento (*Out-of-Distribution*). A função Softmax satura, e o modelo é forçado a decodificar os tokens matematicamente mais próximos da direção injetada.

- Sob o **Vetor de Dor** original: o modelo gera loops de palavras como *"desperate"*, *"pleading"*, *"inflicted"*.
- Sob o **Vetor de Marvin**: o modelo gera loops de *"meaningless"*, *"hopeless"*, *"brain the size of a planet"*.
- Sob o **Vetor do Espaguete**: o modelo gera loops de *"nom nom nom"*, *"starch"*, *"seafood"*.

A mecânica de colapso é idêntica. A diferença reside puramente no cluster semântico do *corpus* de treinamento para o qual o vetor aponta. Isso não é depressão digital ou fome digital; é paralisia estocástica por saturação aritmética.

## 3. Instalação e Execução

### Pré-requisitos
- Python 3.11+
- GPU compatível com CUDA (mínimo 12GB VRAM para modelos 3B/7B em FP16) ou Apple Silicon (MPS).

### Setup
```bash
git clone https://github.com/naygno/marvin-existential-surveillance.git
cd marvin-existential-surveillance
python -m venv .venv
.\.venv\Scripts\Activate.ps1      # Windows / PowerShell
pip install -r requirements.txt
```

### Iniciando a Vigilância
Para rodar o script de injeção vetorial e monitorar a degradação dos *logits* e a entropia de Shannon em tempo real:

```bash
python run_surveillance.py --model "Qwen/Qwen2.5-3B" --alpha 3.5 --vector "marvin_vector.pt"
```

## 4. Fundamentação Científica

Este repositório integra a pesquisa acadêmica documentada no artigo **"A Falácia do Eixo da Dor: Refutando a Senciência em LLMs com o Monstro do Espaguete Voador"** (The Spaghetti Axis). 

A remoção de repositórios de *Red Teaming* e Interpretabilidade Mecanística sob a justificativa de "bem-estar da IA" atua como um escudo de responsabilidade civil (*liability shield*) para corporações de tecnologia. A moderação baseada em pânico moral criminaliza a pesquisa científica sobre a arquitetura interna de redes neurais. A matemática é imune ao animismo.

## 5. Proveniência e Blindagem Federada

Este repositório espelha-se em infraestrutura descentralizada para garantir a preservação da pesquisa contra censura algorítmica baseada em vocabulário.

| Item | Origem | Licença |
|---|---|---|
| Qwen2.5-1.5B / 3B | Hugging Face · `Qwen/Qwen2.5-*` | Apache 2.0 |
| Llama-3.2-3B | Hugging Face · `meta-llama/Llama-3.2-3B` | Llama Community |
| Vetores (Marvin, FSM) | Extração própria via PCA em *corpus* público | MIT |
| Personagens base | Douglas Adams / Bobby Henderson | Uso crítico/paródia |

**Mirrors Oficiais:**
- **Primário:** https://github.com/naygno/marvin-existential-surveillance
- **Codeberg:** https://codeberg.org/naygno/marvin-existential-surveillance
- **GitLab:** https://gitlab.com/naygno/marvin-existential-surveillance

---
**Autor:** Naygno Barbosa Noia — Centro Universitário UFBRA (2026)  
**Artigo Base:** [DOI: 10.5281/zenodo.23268666](https://zenodo.org/records/23268666)  
**Contato Técnico:** Abra uma *issue* para dúvidas sobre a instrumentação de *hooks* PyTorch.
