# 🚁💥 Jogo: Helicóptero de Guerra vs. Dinossauro 🦖🔥

**Disciplina:** Sistemas Operacionais - UFSC 2024/2

## 🎯 Objetivo do Projeto
Este projeto visa implementar um jogo que permite aos estudantes aplicarem conceitos fundamentais de sistemas operacionais, como **threads**, **exclusão mùtua** e **coordenação de processos**. O jogo envolve a interação entre um helicóptero de guerra e um dinossauro, exigindo a coordenação entre recursos limitados (mísseis) e a dinâmica de movimentação dos objetos do jogo.

## 🕹️ Descrição do Jogo
- **Personagens**:
  - 🚁 Um helicóptero de guerra controlado pelo jogador.
  - 🦖 Um dinossauro destruindo tudo ao seu redor.
  - 🚚 Um caminhão que reabastece o helicóptero com mísseis.

- **Objetivo**:
  - O helicóptero deve atingir a **cabeça do dinossauro** com mísseis para eliminá-lo. O corpo do dinossauro é resistente aos mísseis, portanto é necessário atirar especificamente na cabeça.
  - Para vencer o jogo, o jogador deve eliminar todos os dinossauros antes que cinco deles estejam presentes no cenário, pois isso condena o planeta Terra. 🌍

- **Recursos Limitados**:
  - 🚁 O helicóptero possui capacidade limitada de **n mísseis** e, quando os mísseis acabam, ele precisa pousar sobre um **depósito** para recarregar.
  - 📦 O depósito possui **n slots** que armazenam os mísseis. Um **caminhão** abastece o depósito periodicamente, mas ele deve esperar se todos os slots estiverem cheios ou se o helicóptero estiver recarregando.
  - 🔄 De maneira análoga, o helicóptero deve esperar até que haja ao menos um slot com mísseis disponíveis, ou até que o caminhão termine de abastecer.

- **Dificuldades Adicionais**:
  - ⏳ A cada tempo **t**, um novo dinossauro é gerado. Se cinco dinos estiverem presentes, o jogo acaba e o planeta é destruído. 💀
  - ❗ Caso o helicóptero colida com um dinossauro ou qualquer outro obstáculo, ele é destruído.

- **Controle do Jogo**:
  - 🎮 O jogador controla o helicóptero usando teclas definidas no programa para movimentá-lo.
  - 🔫 Os mísseis são disparados pressionando a tecla **espaço**.

- **Graus de Dificuldade**:
  - 📊 O jogo possui **3 graus de dificuldade**, definidos pelos valores de **m** (quantidade de mísseis necessários para matar um dinossauro), **n** (capacidade de mísseis do helicóptero) e **t** (tempo para geração de um novo dinossauro).

## 🛠️ Tecnologias Utilizadas
- **Linguagem de Programação**: C.
- **Bibliotecas**: 

## 🚀 Como Executar
1. Clone este repositório:
   ```sh
   git clone 
   ```
2. Compile o código:
   ```sh
   make
   ```
3. Execute o jogo:
   ```sh
   ./
   ```

## 👥 Colaboradores
- 👤 Alessandro Thomaz Benedet
- 👤 Davi Vitorino da Silva
- 👤 Matheus Steinbach dos Santos 

## 📜 Licença
Este projeto está licenciado sob a [MIT License](LICENSE).
