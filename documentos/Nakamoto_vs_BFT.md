
# 🔐 Protocolos de Consenso em Blockchain: Nakamoto vs BFT

A base de qualquer blockchain está em seu **protocolo de consenso** — o mecanismo que permite que participantes, mesmo desconfiando uns dos outros, concordem sobre o estado da rede.

Entre os protocolos mais relevantes estão o **Protocolo Nakamoto**, utilizado por blockchains como o **Bitcoin**, e os **Protocolos BFT (Byzantine Fault Tolerant)**, presentes em redes como **Cosmos (Tendermint)**, **Aptos (HotStuff)** e **Cardano (Ouroboros)**.

Neste artigo, explicamos em detalhes cada um deles, suas vantagens, desvantagens e casos de uso ideais.

---

## ⚙️ Protocolo Nakamoto (Proof-of-Work)

### 📜 Visão Geral

O protocolo Nakamoto foi proposto por **Satoshi Nakamoto** no whitepaper do Bitcoin em 2008. Ele é baseado na ideia de **Prova de Trabalho (PoW)**, onde os participantes (mineradores) competem para resolver um problema computacional complexo.

Quem resolve o problema primeiro **propõe um novo bloco** e o transmite para a rede. Se for válido, os outros o aceitam e o bloco é adicionado à blockchain.

### 🔁 Como funciona?

1. Mineradores competem para encontrar um *nonce* que satisfaça a condição de dificuldade (hash abaixo de um alvo).
2. O vencedor propaga o bloco com a solução para a rede.
3. Os nós validam o bloco.
4. Se válido, o bloco é adicionado à "cadeia mais longa" — que representa o maior esforço computacional acumulado.
5. Em caso de bifurcação, vence a cadeia mais longa (ou seja, aquela com mais trabalho).

### 🧠 Finalidade Probabilística

Mesmo após a inclusão de um bloco, há uma **probabilidade não nula de reversão**. Por isso, é comum aguardar 6 blocos (no Bitcoin) para considerar uma transação como "final".

### ✅ Vantagens

- **Alta descentralização**: qualquer um pode participar, basta minerar.
- **Resiliência à censura**.
- **Segurança baseada em energia**, difícil de manipular sem controle de 51% do poder computacional.

### ❌ Desvantagens

- **Baixo desempenho e alta latência** (ex: ~10 minutos por bloco no Bitcoin).
- **Alto consumo de energia**.
- **Finalidade probabilística**: não há garantia imediata de que um bloco será mantido.

---

## 🧱 Protocolos BFT (Byzantine Fault Tolerance)

### 📜 Visão Geral

Os protocolos BFT foram criados com base no clássico **Problema dos Generais Bizantinos**, que descreve o desafio de alcançar consenso confiável mesmo com participantes maliciosos.

Esses protocolos são usados por redes **Proof-of-Stake** e de **consenso federado**, e operam por meio de **votação entre validadores conhecidos**.

### 🔁 Como funciona?

1. Um propositor propõe um bloco.
2. Os validadores trocam mensagens (tipicamente "prepare" e "commit").
3. Se 2/3 dos validadores concordam, o bloco é **finalizado**.
4. Não há bifurcação: apenas um bloco é aceito por vez.

Exemplos populares incluem:

- **Tendermint** (Cosmos)
- **HotStuff** (Aptos, Libra/Diem)
- **PBFT** (Practical BFT)
- **Ouroboros Praos/Genesis** (Cardano — híbrido entre BFT e Nakamoto)

### ✅ Vantagens

- **Finalidade determinística**: uma vez finalizado, o bloco **não pode ser revertido**.
- **Baixa latência**: blocos podem ser finalizados em poucos segundos.
- **Alta eficiência energética** (especialmente em Proof-of-Stake).

### ❌ Desvantagens

- **Dependência de um conjunto de validadores confiáveis**.
- Menos resistente a falhas se **mais de 1/3 dos validadores forem maliciosos**.
- Pode exigir sincronismo e mensagens em tempo real — o que limita escalabilidade geográfica.

---

## ⚖️ Comparando os Dois Modelos

| Aspecto                         | **Protocolo Nakamoto**                 | **Protocolos BFT**                         |
|----------------------------------|----------------------------------------|--------------------------------------------|
| Participação                    | Aberta                                 | Limitada a validadores                     |
| Finalidade                      | Probabilística                         | Determinística                             |
| Tolerância a falhas             | Até 50% do hashpower                   | Até 1/3 dos validadores maliciosos         |
| Tempo para confirmar            | Minutos (ex: Bitcoin: 10 min/bloco)    | Segundos (ex: Cosmos: 2s)                  |
| Consumo de energia              | Alto (PoW)                             | Baixo (PoS ou votação digital)             |
| Segurança                       | Alta (se energia for cara)             | Alta (desde que o modelo BFT seja seguro)  |
| Forks (bifurcação)              | Comuns, resolvidos com "cadeia mais longa" | Evitados por design (consenso final)  |

---

## 🎯 Quando usar cada um?

| Situação                                | Melhor Escolha                       |
|----------------------------------------|--------------------------------------|
| Alta descentralização, resistência à censura | **Protocolo Nakamoto**           |
| Baixa latência, transações rápidas     | **Protocolos BFT**                   |
| Ambientes permissionados               | **BFT**                               |
| Ambientes abertos e permissionless     | **Nakamoto**                         |
