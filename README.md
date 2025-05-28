# 🖥️ Sistemas Operacionais – Algoritmos de Escalonamento

Este repositório contém implementações de algoritmos clássicos de escalonamento de processos utilizados em Sistemas Operacionais. Cada algoritmo está organizado como um **checkpoint**, e você pode marcar os que já foram concluídos usando as checkboxes abaixo.

## ✅ Progresso dos Checkpoints

- [ ] **Checkpoint 1 – FIFO (First In, First Out)**  
  Executa os processos na ordem em que chegam.  
  Características:
  - Simples de implementar
  - Injusto para processos curtos
  - Útil em sistemas por lotes

- [ ] **Checkpoint 2 – SJF (Shortest Job First)**  
  Executa primeiro o processo com menor tempo de execução.  
  Características:
  - Minimiza o tempo médio de espera
  - Pode causar inanição
  - Versão: Não preemptiva

- [ ] **Checkpoint 3 – Round Robin**  
  Cada processo recebe um intervalo fixo de tempo (quantum).  
  Características:
  - Preemptivo
  - Justo entre processos
  - Ideal para sistemas de tempo compartilhado

- [ ] **Checkpoint 4 – Prioridade**  
  Executa o processo com maior prioridade (menor valor numérico).  
  Características:
  - Pode ser preemptivo ou não
  - Processos com baixa prioridade podem sofrer inanição
  - Envelhecimento (aging) pode ser usado para evitar inanição

---

## 📁 Estrutura do Projeto

```text
/SistemasOperacionais
├── checkpoint1_FIFO/
├── checkpoint2_SJF/
├── checkpoint3_RoundRobin/
├── checkpoint4_Prioridade/

## 💻 Tecnologias Usadas

- ☕ **Java** — Linguagem principal

## 🚀 Como rodar o projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/pedrogts/Compiladores.git
