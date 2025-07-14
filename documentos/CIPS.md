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

Claro! Vou explicar as **partes típicas de um CIP** e os **papéis envolvidos** no processo, conforme o padrão oficial de Cardano Improvement Proposals.

---

## Partes de um CIP (Cardano Improvement Proposal)

Um CIP geralmente é estruturado com as seguintes seções:

1. **Título (Title)**

   * Nome claro e descritivo da proposta.

2. **Número do CIP (CIP Number)**

   * Identificador único atribuído quando a proposta é registrada.

3. **Autor(es) (Authors)**

   * Pessoas que criaram a proposta, com informações de contato.

4. **Status**

   * Indica o estágio da proposta, como:

     * Draft (rascunho)
     * Reviewing (em revisão)
     * Accepted (aceito)
     * Rejected (rejeitado)
     * Final (finalizado)

5. **Tipo (Type)**

   * Classificação do CIP, por exemplo:

     * Standard (padrão de protocolo)
     * Process (processos e governança)
     * Informational (informativo)

6. **Área (Category)**

   * Qual parte do ecossistema Cardano a proposta afeta, como:

     * Node
     * Wallet
     * Metadata
     * etc.

7. **Resumo (Abstract)**

   * Breve descrição do que a proposta aborda.

8. **Rationale**

   * Explicação do motivo e justificativa para a proposta.

9. **Especificação (Specification)**

   * Detalhes técnicos da proposta, formatos, algoritmos, processos.

10. **Implementação (Implementation)**

    * Status da implementação prática, se houver.

11. **Referências (References)**

    * Links e documentos relacionados.

12. **Histórico de versões (Revision History)**

    * Registro das atualizações do documento.

---

## Papéis no Processo de um CIP

1. **Autor(es)**

   * Criam e submetem a proposta.
   * Responsáveis por mantê-la atualizada e responder dúvidas.

2. **Revisores**

   * Membros da comunidade ou especialistas que analisam o CIP.
   * Comentam, sugerem melhorias, validam a proposta técnica.

3. **Mantenedores (Maintainers)**

   * Responsáveis pelo repositório oficial dos CIPs.
   * Fazem o controle de versão, publicam as propostas e moderam o processo.

4. **Comunitários**

   * Participam da discussão, dão feedback público.
   * Podem apoiar ou contestar a proposta.

5. **Tomadores de decisão**

   * Podem ser membros da equipe Cardano (IOHK, Emurgo, etc.) ou grupos de governança.
   * Decidem se a proposta será adotada na rede.


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

Claro! Aqui está uma **lista dos principais CIPs (Cardano Improvement Proposals)** com suas **descrições, objetivos e usos práticos**. Os CIPs são documentos que definem padrões, melhorias ou sugestões técnicas para o ecossistema Cardano.

---

### 🧩 **Lista de CIPs da Cardano (Principais e mais adotados)**

| **CIP**      | **Nome**                       | **Descrição / Uso**                                                                                                                   |
| ------------ | ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------- |
| **CIP-0001** | CIP Process                    | Define o processo de criação, submissão, revisão e aprovação dos próprios CIPs.                                                       |
| **CIP-0020** | Stake Pool Metadata Standard   | Padroniza o formato de metadados das stake pools (nome, descrição, homepage etc.). Usado por exploradores como PoolTool e Daedalus.   |
| **CIP-0025** | Cardano NFT Metadata           | Define o padrão de metadados para NFTs na Cardano. Essencial para coleções NFT interoperáveis.                                        |
| **CIP-0030** | dApp-Wallet Web Bridge         | Especifica o padrão de comunicação entre carteiras Cardano e dApps via navegador (ex: conexão com wallets como Nami ou Eternl).       |
| **CIP-0031** | Reference Inputs               | Introduz inputs de referência para ler dados de utxos sem consumi-los. Fundamental para contratos inteligentes com leitura de estado. |
| **CIP-0032** | Inline Datums                  | Permite armazenar dados diretamente na transação, em vez de usar hashes. Melhora legibilidade e uso de contratos inteligentes.        |
| **CIP-0033** | Reference Scripts              | Permite armazenar scripts diretamente na blockchain e reutilizá-los sem incluí-los repetidamente em cada transação. Reduz custos.     |
| **CIP-0040** | Plutus Core Versions           | Define como diferentes versões do Plutus Core são representadas e compatibilizadas na rede.                                           |
| **CIP-0068** | NFT Metadata Standard (v2)     | Extensão do CIP-25, com suporte mais robusto para metadados legíveis por máquina (machine-readable).                                  |
| **CIP-0078** | Governance Actions Metadata    | Define o formato de metadados para ações de governança on-chain no modelo de governança da era Voltaire.                              |
| **CIP-0086** | DRep Metadata                  | Define o formato padrão de metadados para Representantes Delegados (DReps), parte da governança participativa.                        |
| **CIP-0095** | Wallet Address QR Encoding     | Padroniza como os QR Codes de endereços Cardano devem ser gerados e lidos.                                                            |
| **CIP-0094** | On-Chain Governance Procedures | Estabelece diretrizes e estruturas para propostas on-chain na era Voltaire.                                                           |
| **CIP-0093** | Voting Procedures              | Define formatos e estruturas para processos de votação.                                                                               |
| **CIP-0065** | Multi-Signature Metadata       | Define como registrar múltiplas assinaturas de participantes em uma transação (útil para DAOs e co-custódia).                         |
| **CIP-0014** | Hardware Wallet Compatibility  | Regras de compatibilidade para suportar carteiras físicas (Ledger, Trezor etc.) com Cardano.                                          |

---

### 🛠️ **CIPs mais relevantes para desenvolvedores de dApps**

* **CIP-0030**: comunicação com carteiras
* **CIP-0031 / 32 / 33**: melhorias no modelo e eficiência de contratos inteligentes
* **CIP-0025 / 0068**: NFTs
* **CIP-0065**: multiassinatura e metadados colaborativos

---

### 🧬 **CIPs voltados para governança (Era Voltaire)**

* **CIP-0078**: metadados de ações de governança
* **CIP-0086**: identidade e metadados dos DReps
* **CIP-0093 / 0094**: procedimentos formais de votação e governança on-chain

---

### 📚 Fontes oficiais e documentação

* 🔗 Lista oficial: [https://cips.cardano.org](https://cips.cardano.org)
* 📘 Repositório GitHub: [https://github.com/cardano-foundation/CIPs](https://github.com/cardano-foundation/CIPs)

---



[1]: https://github.com/Cerkoryn/CIPs?utm_source=chatgpt.com "GitHub - Cerkoryn/CIPs"
[2]: https://github.com/cardano-foundation/CIPs?utm_source=chatgpt.com "GitHub - cardano-foundation/CIPs: Cardano Improvement Proposals (CIPs)"

