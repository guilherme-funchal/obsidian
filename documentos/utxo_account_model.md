### Comparação: UTxO vs Account Model

| Aspecto                                    | Modelo UTxO                                                                                                | Modelo Account                                                                        |
| ------------------------------------------ | ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| **O que é**                                | Conjunto de saídas de transações não gastas (UTxOs), que representam unidades específicas de valor         | Contas com saldo acumulado atualizado diretamente                                     |
| **Funcionamento básico**                   | Cada transação consome UTxOs e cria novas UTxOs. O saldo é a soma das UTxOs pertencentes a um usuário      | Cada conta tem um saldo, que é alterado diretamente em cada transação                 |
| **Exemplo de blockchain**                  | Bitcoin, Cardano                                                                                           | Ethereum, Binance Smart Chain                                                         |
| **Estado global**                          | É representado pelo conjunto de UTxOs distribuídos pela rede                                               | Um único registro global com o saldo de cada conta                                    |
| **Paralelismo**                            | Alto — transações que gastam UTxOs diferentes podem ser processadas em paralelo facilmente                 | Mais difícil de paralelizar devido a possíveis conflitos de contas                    |
| **Complexidade de rastreamento**           | Pode ser mais complexo rastrear o histórico completo de fundos, pois eles são fragmentados em várias UTxOs | Mais simples, pois o saldo da conta é atualizado diretamente                          |
| **Privacidade**                            | Melhor privacidade — cada UTxO é uma entidade separada, dificultando a ligação direta das transações       | Menor privacidade — o saldo da conta é visível e atualizado em cada operação          |
| **Facilidade para contratos inteligentes** | Tradicionalmente mais difícil, pois requer gerenciamento dos UTxOs de forma específica                     | Facilita a execução de contratos, pois o estado da conta é facilmente modificado      |
| **Taxas e recursos**                       | Pode ser mais eficiente no uso de recursos e taxas, pois as transações são baseadas em inputs e outputs    | Taxas são pagas por alteração de estado, podendo ser menos eficientes em alguns casos |

---

### Resumo rápido:

* **UTxO**: modelo baseado em "fichas" (outputs) que são gastas e criam novas fichas. É eficiente, paralelo e oferece melhor privacidade, usado por blockchains como Bitcoin e Cardano.
* **Account Model**: modelo de saldo por conta, simples e direto, mais fácil para contratos inteligentes complexos, usado por Ethereum.


