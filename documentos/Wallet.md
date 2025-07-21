Na Cardano, existem diferentes **tipos de carteiras** (wallets) usadas para armazenar, enviar, receber e delegar ADA e tokens nativos. Elas podem ser classificadas por **função, nível de segurança e arquitetura**. Aqui estão os principais tipos:

---

### 🧩 1. **Carteiras de Software**

Executadas em dispositivos (PC ou celular), acessíveis e fáceis de usar.

#### a) **Hot Wallets (Carteiras quentes)**

* Conectadas à internet.
* Mais convenientes, mas menos seguras.

**Exemplos:**

* **Eternl** (antiga CCVault)
* **Nami Wallet** (voltada para dApps, usada em navegadores)
* **Flint** (simples, amigável, também compatível com dApps)
* **Typhon Wallet** (avançada, suporte a multisig e tokens nativos)

#### b) **Light Wallets (Carteiras leves)**

* Não precisam sincronizar toda a blockchain.
* Utilizam serviços externos para consultar dados.

**Exemplo:**

* **Yoroi Wallet** (leve, da Emurgo, disponível para navegador e mobile)

---

### 🧱 2. **Carteiras Full Node**

* Requerem download completo da blockchain.
* Mais seguras e independentes, mas pesadas.

**Exemplo:**

* **Daedalus Wallet** (desenvolvida pela IOHK)

  * Instala em desktop (Windows, Mac, Linux)
  * Mantém cópia completa da blockchain Cardano
  * Indicado para usuários avançados e operadores de stake pool

---

### 🔐 3. **Carteiras de Hardware**

* Dispositivos físicos que armazenam chaves privadas offline.
* Consideradas **as mais seguras** para grandes quantias.

**Exemplos compatíveis:**

* **Ledger Nano S / Nano X**
* **Trezor Model T**

São usadas em conjunto com softwares como:

* Daedalus
* Yoroi
* Eternl
* Nami

---

### 🧾 4. **Carteiras Multisig**

* Exigem múltiplas assinaturas para autorizar transações.
* Usadas por organizações ou para segurança avançada.

**Ferramentas:**

* Typhon Wallet (parcial suporte)
* Carteiras personalizadas com scripts Plutus

---

### 🧬 5. **Carteiras com suporte a Smart Contracts / dApps**

* Compatíveis com **Plutus scripts** e interação com contratos inteligentes.

**Exemplos:**

* Nami Wallet
* Eternl
* Flint
* Typhon

---

### 🪪 6. **Carteiras para Identidade Descentralizada (DID)**

* Futuras integrações com **Atala PRISM** para identidade digital.

---

### Comparativo rápido:

| Tipo         | Exemplo      | Segurança  | Indicado para               |
| ------------ | ------------ | ---------- | --------------------------- |
| Full Node    | Daedalus     | Alta       | Usuários técnicos           |
| Light Wallet | Yoroi, Flint | Média      | Usuário comum               |
| Hot Wallet   | Nami, Eternl | Média      | dApps, staking, dia a dia   |
| Hardware     | Ledger       | Muito alta | Grandes quantias, segurança |
| Multisig     | Customizadas | Alta       | Times, empresas             |

