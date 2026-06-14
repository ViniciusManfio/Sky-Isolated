# Sky-Isolated
A decentralized social network concept inspired by Ace Combat 7. Isolated satellite nodes act as independent chat servers, simulating a global communication blackout where users are invisible outside their current orbital sector.



---

# 🛰️ rede-sky | Project Sky Isolated

> **"The sky is not connected."** 
> *— Global Network Status, Post-Farbanti Blackout.*

---

## 🌌 O Conceito
Inspirado no maior ponto de virada de **Ace Combat 7: Skies Unknown**, este projeto é o protótipo de uma rede social conceitual e descentralizada. 

Após a destruição massiva de satélites em órbita (Síndrome de Kessler), o mundo perdeu a infraestrutura de comunicação global. A **rede-sky** simula o estado do planeta após o apagão: não existe um servidor central. A comunicação foi fragmentada em nós de satélites sobreviventes isolados e independentes.

## 📡 Como Funciona (Mecânicas da Rede)

*   **Satélites como Servidores:** Cada servidor ativo funciona de forma anônima e isolada, como um satélite remanescente em órbita.
*   **Usuários Fantasmas (Quebra de IFF):** Não existe busca global de usuários. O sistema de identificação está quebrado. Você só consegue visualizar, interagir ou saber da existência de outros pilotos se estiver conectado exatamente no mesmo satélite (órbita) que eles.
*   **Isolamento de Dados:** Mensagens e dados não cruzam a atmosfera. Se o Satélite A cair ou for desconectado, os usuários dele perdem o sinal imediatamente, sem afetar o Satélite B.

## 🛠️ Arquitetura Proposta

O projeto foi desenhado para rodar de forma federada e assíncrona:
*   **Nós Independentes:** Cada "satélite" pode ser inicializado de forma isolada (ex: instâncias Docker separadas).
*   **Comunicação em Tempo Real:** Uso de WebSockets para criar as salas orbitais onde os sinais se encontram.

---

## 🚀 Como Começar (Mentalidade de Desenvolvimento)

Este repositório foi criado para documentar a criação desta infraestrutura. O objetivo é simular o caos tático de comunicação em uma interface inspirada nos HUDs militares e telas de radar clássicas da franquia.

> *Mantendo a escuta ativa. Pilotos, escolham seus canais com cuidado.*
