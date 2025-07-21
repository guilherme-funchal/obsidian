# 📘 Cardano Questions and Answers


1. What did Bitcoin Improvement Proposal BIP-39 introduce?
   
**Answer:**  
A process for turning random seeds into sets of predefined words

2. A derivation is described with which two pieces of information?
   
**Answer:**  
Whether it is hardened or not
The derivation index

3. What type of addresses are on Cardano?
   
**Answer:**  
Payment addresses
Stake addresses

4. What does the payment part of an address indicate?
   
**Answer:**  
The spending conditions associated with the address

5. Which of the following are true regarding base addresses?
   
**Answer:**  
It consists of both a payment and delegation part
Scripts allow combining multiple public keys and time conditions together

6. What does it mean if a user makes use of enterprise addresses?
    
**Answer:**  
* **They opt out of participation in the proof of stake protocol**


7. What must happen to a stake address balance before it can be used as a payment input?
   
**Answer:**  
- It must be turned into UTxO entries**


8. Select the correct statements about virtual machines:**
   
**Answer:**  
- It provides the same capabilities and interfaces that the real architecture would have**
A virtual machine is an execution environment that mimics a specific hardware architecture**


9. Which of the following statements are correct:**

**Answer:**  
- Virtual machines provide a safe execution environment for smart contracts**
- Blockchain virtual machines need to be able to quantify resource usage with a high degree of precision**

10. Select the correct statements:**
    
**Answer:**  
- Plutus refers to the programming platform which encompasses elements such as (Untyped) Plutus Core and Plutus Tx**
- Plutus Application Framework: a collection of tools for working with smart contracts in Haskell**
- The Cardano ledger only comprehends Plutus Core**

11. The Plutus virtual machine measures resource usage along two dimensions. What are they?
    
**Answer:**  
- Steps and memory**

12. Which of the following is NOT true regarding Haskell?
    
**Answer:**  
- The Cardano ledger only understands Haskell**


13. Which statement is NOT true about Aiken?
    
**Answer:**  
-It is complex to set up and configure**


14. What is one of the main characteristics of Helios, a Cardano-specific programming language?

- It is a purely functional language inspired by TypeScript**


15. What does 'eDSL' mean?
    
**Answer:**  
- Embedded Domain Specific Language**

15. What kind of trustless smart contract logic could you implement using a Cardano native script?
    
**Answer:**  
- A token minting policy which ensures a maximum supply of tokens**

16. What are the six primitives that come with Marlowe?
    
**Answer:**  
- Pay, Close, If, When, Let, Assert**


17. Select the step NOT involved in block generation.
    
**Answer:**  
- The block producer ensures that at least two other block producers have included the same transactions as them**

18. In the context of a proof-of-work consensus algorithm, a ‘nonce’ \_\_\_\_\_;
    
**Answer:**
- Is a random number that miners add to the block data**

19. CIP-0030**
    
-  Qual é o propósito do CIP-0030 no ecossistema Cardano?
**Answer:** 
-  Serve como uma ponte para comunicação entre DApps e carteiras Cardano.

20. NFTs no Cardano**
    
-  Verdadeiro ou Falso: Existe mais de uma proposta para padronizar NFT no Cardano?
**Answer:** 
-  Verdadeiro. Exemplos: CIP-25, CIP-68.

21. CIP-0057 (Plutus Core)**
    
-  Por que o CIP-0057 foi introduzido?
**Answer:** 
-  Para alinhar o desenvolvimento de linguagens de programação alternativas para contratos inteligentes.

22. Demeter.run**
- Qual funcionalidade NÃO é oferecida pelo Demeter.run?
  
**Answer:**  
- Plataforma de cunhagem de NFT.

23. Carteiras de Nó Completo**
Quais são carteiras de 'nó completo'?

**Answer:**  
-  Daedalus.

24. Staking Líquido** 
-  Qual afirmação NÃO é verdadeira sobre staking líquido?
- 
**Answer:** 
-  "Há um período de espera antes de acessar sua ADA" e "Todas as blockchains PoS têm staking líquido".

25. SPO** 
-  SPO é a sigla para?
  
**Answer:** 
-  Operador de Pool de Stake.

26. Recompensas de Staking** 
-  Se delegar na Época N, quando recebe as primeiras recompensas?
  
**Answer:** 
-  Época N+2.

27. Seleção de Stake Pools** 
-  O que NÃO é uma consideração ao selecionar um pool?
  
**Answer:** 
-  O pool deve estar no mesmo país que você.


28. Delegação da Fundação Cardano**
-  Com que frequência a Fundação Cardano rotaciona delegações?
  
**Answer:**  
-  A cada 12 meses.

29. Ativos Nativos**
    
**Answer:**

-  Um ativo nativo é governado por qual?
-  Sua política (minting policy).

30. Casos de Uso de NFTs**
-  O que NÃO é um caso de uso de NFT?
-  
**Answer:**

-  Sua senha de login.

31. Padrões de Metadados**
-  Quais são padrões de metadados?

**Answer:** 

-  CIP-25, CIP-68, CIP-60 (Todas acima).

32. Tokens de Utilidade vs. Segurança**

-  Tokens de utilidade são fungíveis com tokens de segurança?

**Answer:** 
-  Falso.

33. DEXs no Cardano**
    
-  Como são executados pedidos em uma DEX?

**Answer:** 
-  Off-chain.

34. Perda Impermanente (IL)**

-  Quais afirmações são verdadeiras sobre IL?

**Answer:**  

É um risco para provedores de liquidez.
Você pode perder dinheiro se o preço mudar após o depósito.

35. Tipos de DEX**
-  Quais são os dois principais tipos de DEX?

**Answer:**  
* Fabricante de mercado automatizado (AMM)
* Modelo de livro de pedidos

36. Prova de Trabalho (PoW) vs. Prova de Participação (PoS)**
-  Afirmações corretas sobre PoW e PoS?
  
**Answer:**  

* PoW usa poder de hash
* PoS refere-se à moeda nativa

Afirmações corretas sobre slashing?
-  Afirmações corretas sobre slashing?
-  
**Answer:**

* Penaliza comportamentos maliciosos
* Foi projetado para sancionar adversários

37. Algoritmos Híbridos**
    
**Answer:** 
-  Por que são úteis?
-  Reduzem fraquezas de algoritmos individuais.


38. Prova de Autoridade (PoA)**
-  O que a diferencia do PoS?
  
**Answer:** 

-  Exige reputação e investimento financeiro.

39. Prova de Atividade (PoA)**
-  Afirmação verdadeira?
- 
**Answer:** 
-  Combina PoW (mineração) e PoS (validação).

40. Prova de Importância (PoI)**
-  O que a diferencia do PoS?

**Answer:** 

-  Avalia contribuições além do stake financeiro.

41. Prova de Queimadura (PoB)**
    
-  Afirmação INCORRETA?
-  
**Answer:** 
-  "Apenas primeiros adotantes podem queimar moedas".

Prova de Espaço (PoSpace)

42.Afirmações corretas?

**Answer:** 

* "Parcelas" são conjuntos de dados em discos
* Mais parcelas = maior chance de gerar blocos

43. Como um produtor gera blocos?
    
**Answer:** 
Espera um tempo aleatório de uma fonte confiável.

44. What distinguishes a block header from a block body in the structure of a blockchain block?
    
**Answer:**  
The block header acts as a short identifier of the block and its producer and provides proof of entitlement to produce the block, while the block body contains a list of transactions


45. Which of the following statements about Cardano’s block time are correct? (Choose 3)
    
**Answer:**  

- Cardano’s block time helps support a maximum block size of 88 kilobytes  
- Block time refers to the average production time between two consecutive blocks  
- Cardano adds a new block approximately every 20 seconds


46. Which of the following statements accurately describes Chain Growth, Common Prefix, and Chain Quality in the context of blockchain?
    
**Answer:**  

Chain Growth - the speed at which new blocks are added to the chain; Common Prefix - the part of the chain that can be trusted in an honest node's local chain; Chain Quality - the proportion of honest blocks in an honest node's chain

47. Select two correct statements about how to avoid double-spending attacks.
    
**Answer:**  
- The number of blocks the user should wait for before accepting a transaction depends on the block generation power held by potential attackers  
- Waiting before confirming a transaction assures the user that a fork will not appear in the blockchain and that the tokens are indeed theirs


48. What happens during a hard fork in a blockchain protocol?
    
**Answer:** 

A hard fork requires all nodes to upgrade to the latest protocol version otherwise the network could split between those using the new and old protocols


49. Cardano’s Vasil upgrade in September 2022 was a soft fork that added innovative features to Cardano, including improved performance.
    
**Answer:**  

True — It was a soft fork introducing performance improvements


50. Select the correct statements about block rewards. (Choose 2)
    
**Answer:**  

- Block rewards are consistent and known in advance  
- The halving of a block reward can encourage energy efficiency among miners to remain profitable


51. Which of the following is NOT true of transaction fees?
    
**Answer:**  

Fixed and calculated in the same way for all blockchains


52. Select the correct statements about Preview and PreProd. (Choose 2)
    
**Answer:**  

- The PreProd network is meant to simulate mainnet conditions for DApps  
- The Preview network is where new software is deployed

53. PS (Transaction Per Second) is an accurate measure to compare different blockchain networks and protocols.
    
**Answer:**  

False


54. What are the primary functions of Ogmios in the Nebula app? (Choose 3)
    
**Answer:**  

- Creating transactions involved in the Nebula protocol  
- Simplifying communication protocols  
- Assisting in transaction operations

55. Which software development kit (SDK) did Nebula utilize for creating transactions?
    
**Answer:**  

Lucid

56. In which scenario is pipelining most efficient?
    
**Answer:**  

When there is a significant idle time between tasks and one actor waits for another

57. What’s generally true about sharding?
    
**Answer:**  

All shards perform a similar task with different data

58. In the context of the eventual consistency technique, what does a ‘transient state’ refer to?

**Answer:**  

A temporary state before data is written to disk


59. Which statement best describes participants in a state channel?
    
**Answer:**  

Participants must be set at the channel's start and can't be added later


60. Select 2 correct statements on rollups as a layer 2 scalability solution.
    
**Answer:**  

- It's a bundle of off-chain transactions published on-chain as one transaction  
- All rollups process computations off-chain and post a compressed version to layer 1


61. Which of the following statements is true about the efficiency of optimistic rollups?
    
**Answer:**  
They become inefficient if all transactions are disputed


62. In the context of rollups, why are zero-knowledge proofs beneficial?
    
**Answer:**  

They confirm the transaction sequence without redoing all transactions


63. Why can operating a zero-knowledge rollup be costly?
    
**Answer:**  

It requires high-end hardware due to the resources needed to generate a proof

64. What is the main role of validator nodes in optimistic rollups?
    
**Answer:**  

To oversee and challenge optimistic rollup aggregators when needed

65. What better reflects Cardano’s development approach?

**Answer:**  
Evidence-based science and rigorous software development


66. Select the correct statements about peer reviews. (Choose 2)
    
**Answer:**  

- The process of peer review ensures credibility, reliability and well-designed research  
- Peer reviews are done anonymously to avoid bias

67. What was the main objective of the Byron phase in Cardano's development?
    
**Answer:**  
To build a strong foundation for future phases of the Cardano roadmap

68. Cardano utilizes the Ouroboros Proof-of-Stake consensus protocol, which is designed with academic rigor for security and energy efficiency.
    
**Answer**

Delegated Proof-of-Stake

69. KYC procedures ensure proper customer identification and due diligence, which is essential for regulatory compliance.
    
**Answer**

It assists in comprehensive customer due diligence

70.Interoperability enables the transfer of assets and data between different blockchains without relying on a centralized intermediary.

**Answer**

It allows seamless asset and data transfers across networks.

71.Security audits identify vulnerabilities and ensure that the system's integrity and security protocols are robust.

**Answer**

To assess vulnerabilities and ensure system integrity

72.The extended UTXO model in Cardano ensures that transactions can be deterministically validated, which is essential for the reliable and predictable execution of smart contracts.

**Answer**

Deterministic transaction validation

73.FinCEN guidelines focus on preventing both money laundering and terrorism financing, ensuring rigorous oversight of financial transactions.

**Answer**

Financial Crimes Enforcement Network (FinCEN) guidelines

74.Cardano's design allows multiple asset types to be managed directly at the ledger level, reducing reliance on smart contracts and streamlining the transaction process for various tokens.

**Answer**

Multiple asset types can be transacted natively on the ledger without using custom smart contracts

75.The Settlement Layer in Cardano is dedicated to processing transactions and transferring value, keeping it separate from computational operations.

**Answer**

The Settlement Layer

76.Cardano utilizes the Ouroboros Proof-of-Stake consensus protocol, which is designed with academic rigor for security and energy efficiency.

**Answer**

Ouroboros Proof-of-Stake
