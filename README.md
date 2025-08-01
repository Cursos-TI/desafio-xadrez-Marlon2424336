## ♟️ Desafio de Xadrez

## 🧠 Níveis Implementados

### 🥉 Nível Novato

* **Peças**: Bispo, Torre e Rainha
* **Estrutura usada**: `for`
* **Movimentos**:

  * Bispo: 5 casas na diagonal superior direita
  * Torre: 5 casas para a direita
  * Rainha: 8 casas para a esquerda

---

### 🥈 Nível Aventureiro

* **Peça**: Cavalo
* **Estruturas usadas**: `for` + `while`
* **Movimento**: Em L, utilizando dois loops aninhados

---

### 🥇 Nível Mestre

* **Peças**: Bispo e Cavalo
* **Técnicas usadas**:

  * **Bispo**: movimentação com função recursiva
  * **Cavalo**: movimentação em L com `for`, `continue` e `break`

---

## ✅ Requisitos Funcionais

1. **Entrada de Dados**

   * As direções e movimentos são definidos diretamente por variáveis no código.
   * Uso de constantes permitido para facilitar manutenção.

2. **Estruturas de Repetição**

   * Todos os níveis utilizam estruturas de repetição (`for`, `while`, `do-while`, `recursão`).

3. **Saída de Dados**

   * Os movimentos são exibidos claramente com `printf`, organizados por peça e direção.

---

## 🚫 Requisitos Não Funcionais

* **Performance**: Execução sem atrasos ou lentidão perceptível.
* **Documentação**: Código comentado, funções nomeadas com clareza.
* **Manutenibilidade**: Nomes de variáveis e funções autoexplicativos.

---

## 📥 Como Executar

```bash
gcc xadrez.c -o xadrez
./xadrez
```

Você será solicitado a escolher um dos níveis (1, 2 ou 3) e verá os movimentos realizados por cada peça.

---

## 🔍 Detalhes Técnicos

### Funções criadas:

| Função                     | Finalidade                                       |
| -------------------------- | ------------------------------------------------ |
| `moverBispoNovato()`       | Loop `for` para simular 5 movimentos na diagonal |
| `moverTorreNovato()`       | Loop `for` para 5 movimentos à direita           |
| `moverRainhaNovato()`      | Loop `for` para 8 movimentos à esquerda          |
| `moverCavaloAventureiro()` | Loop aninhado com `for` e `while` em L           |
| `moverBispoRecursivo()`    | Recursão com chamada decrescente                 |
| `moverCavaloMestre()`      | Uso de `for`, `continue` e `break`               |

