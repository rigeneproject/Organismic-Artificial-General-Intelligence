# Organismic Artificial General Intelligence

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Questo repository contiene l'implementazione di riferimento per **Organismic AGI**, basata sui framework teorici **SPEACE**, **CUB** e **attNA**. L'architettura integra:

- **OpenClaw**: agenti autonomi per il metabolismo energetico e computazionale.
- **n8n**: orchestrazione dei flussi di lavoro e coordinamento tra moduli.
- **BotPress**: interfaccia conversazionale multicanale e ontologia condivisa.
- **IoT**: sensori e attuatori per l'embodiment fisico.

## Architettura

![Architettura a 4 layer](docs/architecture.png)

I moduli seguono la specifica SPEACE:

- **M0**: Ontological Integration (BotPress + knowledge graph)
- **M1**: Sensory Planetary Layer (IoT + edge AI)
- **M3**: Energy-Computation Metabolism (n8n + ottimizzatore)
- **M5**: Digital DNA Evolution (genoma artificiale)
- **attNA**: Constraint Validation (distributed ledger + LVC)

## Requisiti

- Docker e Docker Compose
- Python 3.10+
- Node.js 18+ (per n8n e BotPress)
- GPU NVIDIA con driver e CUDA (opzionale per accelerazione)

## Installazione rapida

1. Clona il repository:
   ```bash
   git clone https://github.com/tuo-username/organismic-agi.git
   cd organismic-agi
