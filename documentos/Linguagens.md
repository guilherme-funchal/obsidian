Na Cardano, várias **linguagens de programação** são utilizadas, cada uma com um papel específico na infraestrutura da blockchain, nos contratos inteligentes e nas ferramentas associadas.

Aqui estão as principais linguagens usadas:

---

## 🧠 1. **Haskell** (linguagem principal)

* **Uso:** Desenvolvimento do núcleo da Cardano (nó, consenso, ledger).
* **Por quê?** Alta confiabilidade, segurança formal, e forte tipagem funcional.
* **Componentes escritos em Haskell:**

  * Ouroboros (algoritmo de consenso)
  * Cardano Node
  * Plutus Core (motor de contratos)
  * Marlowe Engine (DSL para contratos financeiros)

---

## ⚙️ 2. **Plutus** (contratos inteligentes)

* **Uso:** Linguagem principal para escrever **smart contracts on-chain** em Cardano.
* **Baseada em:** Haskell (é uma extensão/dialeto dele)
* **Funciona em duas partes:**

  * **Plutus Core:** executa on-chain (compilado)
  * **Plutus Tx:** código escrito em Haskell e compilado para on-chain

---

## 📜 3. **Marlowe** (contratos financeiros)

* **Uso:** Linguagem de **alto nível e declarativa** para contratos financeiros.
* **Destinada a:** Usuários não programadores (ex: analistas, empresas)
* **Visual:** Pode ser usada via blocos visuais no Marlowe Playground.
* **Baseada em:** DSL embutida (eDSL) em Haskell

---

## 🌐 4. **TypeScript / JavaScript**

* **Uso:** Ferramentas frontend e bibliotecas para desenvolvedores dApps.
* **Bibliotecas populares:**

  * `lucid` → construção de transações off-chain
  * `cardano-serialization-lib` → serialização de dados da blockchain
  * `nami`, `cip-30` → interfaces para carteiras web

---

## 🦀 5. **Rust**

* **Uso:** Desenvolvimento de bibliotecas leves e rápidas, como:

  * `cardano-wallet`
  * `cardano-multiplatform-lib` (bindings para JavaScript/WebAssembly)
* **Por quê?** Eficiência, segurança de memória, boa integração com WebAssembly.

---

## 🖥️ 6. **Python**

* **Uso:** Scripts, bibliotecas e integração com ferramentas externas.
* **Exemplos:**

  * Ferramentas CLI para automação
  * `pycardano` → biblioteca para criar e assinar transações

---

## 🧪 Outras linguagens associadas:

| Linguagem              | Uso                                                                                                |
| ---------------------- | -------------------------------------------------------------------------------------------------- |
| **SQL**                | Consultas em bancos da blockchain (por exemplo, db-sync)                                           |
| **C++ / Go**           | Alguns projetos auxiliares da comunidade                                                           |
| **WebAssembly** (WASM) | Compilação de contratos e bibliotecas para execução leve em navegadores ou blockchains compatíveis |

---

## 🔍 Resumo por camadas:

| Camada                 | Linguagens principais                               |
| ---------------------- | --------------------------------------------------- |
| Base / Protocolo       | **Haskell**                                         |
| Contratos inteligentes | **Plutus**, **Marlowe**, **Haskell**                |
| dApps / Frontend       | **TypeScript**, **JavaScript**, **Rust** (via WASM) |
| Ferramentas / Scripts  | **Python**, **Rust**, **Shell scripts**             |
