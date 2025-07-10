Os **CIPs (Cardano Improvement Proposals)** são propostas de melhoria da Cardano que seguem um processo colaborativo, transparente e aberto à comunidade. Eles funcionam como documentos formais que descrevem novas funcionalidades, mudanças ou padrões para a blockchain Cardano.

---

### 🔧 Como funciona o processo dos CIPs:

#### 1. **Proposição**

* Qualquer membro da comunidade pode propor um CIP.
* A proposta deve ser enviada como um **Pull Request** no repositório oficial [CIP no GitHub](https://github.com/cardano-foundation/CIPs).
* Ela precisa seguir um **formato estruturado**: título, resumo, motivação, especificação técnica e considerações de segurança.

#### 2. **Categorias de CIP**

Os CIPs são classificados em três tipos principais:

* **Standards Track (Padrões Técnicos)**: Propostas que afetam diretamente o protocolo, como alterações em transações, contratos ou formatos de dados.
* **Process (Processos)**: Mudanças em processos fora do protocolo, como governança, desenvolvimento ou ciclos de lançamento.
* **Informational (Informativo)**: Documentação, boas práticas ou sugestões que não exigem implementação obrigatória.

#### 3. **Rascunho (Draft)**

* Após o envio, o CIP entra em estado de **rascunho** e passa por discussão pública.
* Revisores da comunidade e especialistas técnicos analisam a proposta.

#### 4. **Discussão e Revisão**

* A comunidade pode comentar, sugerir melhorias ou apontar falhas.
* Revisores formam um grupo de validadores que dão feedback técnico e de clareza.

#### 5. **Status**

Os CIPs passam por diversos **status**, como:

* `Draft` (rascunho)
* `Proposed` (proposto)
* `Active` (ativo)
* `Final` (finalizado)
* `Rejected`, `Withdrawn`, `Obsolete`

#### 6. **Aprovação e Implementação**

* Quando aprovado, o CIP pode ser implementado pelos desenvolvedores das ferramentas principais da Cardano (como o node ou carteiras).
* Alguns CIPs influenciam diretamente nas atualizações de protocolo via hard forks.

---

### 📋 Exemplo de CIPs famosos:

* **CIP-68**: Define um novo padrão de metadados on-chain para ativos nativos.
* **CIP-25**: Padrão para metadados de NFTs na Cardano.
* **CIP-30**: Interface de dApps com carteiras Cardano via navegador.

---

### 🤝 Atores no processo

* **Autores**: quem propõe o CIP.
* **Revisores**: voluntários técnicos que avaliam a qualidade, coerência e impacto do CIP.
* **Editores**: gerenciam o repositório GitHub e mantêm o fluxo editorial.

---

### ✅ Benefícios dos CIPs

* Transparência no desenvolvimento.
* Inclusão da comunidade no processo de evolução.
* Redução de riscos técnicos via revisão aberta.
* Padrões bem definidos que favorecem interoperabilidade entre ferramentas.

---
Segue uma lista com alguns dos CIPs mais importantes, incluindo status e breve descrição:

---

## 📘 CIPs selecionados

|                Número                | Título                                  |  Status  | Resumo                                                                                              |
| :----------------------------------: | :-------------------------------------- | :------: | :-------------------------------------------------------------------------------------------------- |
|               CIP‑0001               | CIP Process                             |  Active  | Define o processo padrão para criação, revisão e aprovação de CIPs ([GitHub][1], [GitHub][2])       |
|               CIP‑0002               | Coin Selection Algorithms               |  Active  | Detalha algoritmos como “Largest‑First” e “Random‑Improve” para seleção de moedas                   |
|               CIP‑0003               | Wallet Key Generation                   |  Active  | Especifica padrões para geração de chaves em carteiras                                              |
|               CIP‑0005               | Common Bech32 Prefixes                  |  Active  | Define prefixos Bech32 comuns utilizados em endereços e identificadores                             |
|               CIP‑0030               | Cardano dApp‑Wallet Web Bridge          |  Active  | Padrão para interação entre dApps e carteiras via browser (API JS)                                  |
|               CIP‑0052               | Cardano Audit Best Practice Guidelines  | Proposed | Diretrizes para auditorias de segurança na plataforma                                               |
|               CIP‑0089               | Distributed dDApps & Beacon Tokens      |  Active  | Integrações de DEXs distribuídos e Beacon Tokens em carteiras desktop                               |
|               CIP‑0129               | Governance Identifiers                  | Proposed | Padroniza estrutura bech32 para IDs de governança (DRep, CC, etc.) na era Conway                    |
|               CIP‑0100               | Governance Metadata                     | Proposed | Sugere formato unificado de metadados para eventos de governança                                    |
| CIP‑0169 (referenciado via CIP‑1694) | Primeiro passo para governança on‑chain |  Active  | Introduziu funcionalidades de criação e votação de propostas on‑chain via hard fork Plomin em 2024  |

---

### 🗂️ Mais CIPs ativos significativos

* CIP‑0010: Registro de labels de metadados em transações
* CIP‑0019: Endereços Cardano
* CIP‑0020: Mensagens/comentários em transações
* CIP‑0031: Reference Inputs
* CIP‑0032: Inline Datums
* CIP‑0033: Reference Scripts
* CIP‑0055: Parâmetros de protocolo (era Babbage)
* CIP‑0080: Ciclo de depreciação de serialização de transações
* CIP‑0083: Metadados de transação cifrados (addendum CIP‑0020)
* CIP‑0084: Evolução do ledger Cardano ([GitHub][2], [GitHub][1])

[1]: https://github.com/Cerkoryn/CIPs?utm_source=chatgpt.com "GitHub - Cerkoryn/CIPs"
[2]: https://github.com/cardano-foundation/CIPs?utm_source=chatgpt.com "GitHub - cardano-foundation/CIPs: Cardano Improvement Proposals (CIPs)"

