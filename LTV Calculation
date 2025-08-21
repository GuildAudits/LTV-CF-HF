### **1. Collateral Factor (CF)**

* **Definition:** A protocol-defined parameter that tells you the **maximum borrowing power** of a collateral asset.
* **Example:**

  * If ETH has a **collateral factor = 80%**, then depositing **\$1,000 ETH** lets you borrow **up to \$800** worth of assets.
* Think of it as the **upper limit** the protocol allows.

---

### **2. Loan-to-Value (LTV)**

* **Definition:** A dynamic ratio showing your **current loan vs. your collateral’s current value**.

* **Formula:**

  $$
  \text{LTV} = \frac{\text{Loan Value}}{\text{Collateral Value}} \times 100
  $$

* **Example:**

  * You deposit **\$1,000 ETH** (collateral).
  * You borrow **\$600 USDC**.
  * LTV = 60%.

* LTV fluctuates as asset prices change.

---

### **3. Health Factor (HF)**

* **Definition:** A safety buffer metric used by protocols (e.g., Aave). It shows how close you are to liquidation.

* **Formula (simplified):**

  $$
  \text{HF} = \frac{\text{Collateral Value} \times \text{Collateral Factor}}{\text{Loan Value}}
  $$

* **Interpretation:**

  * **HF > 1** → Safe.
  * **HF = 1** → At the liquidation threshold.
  * **HF < 1** → Liquidatable.

* **Example:**

  * Collateral: \$1,000 ETH.
  * CF: 80% → borrowing power = \$800.
  * Loan: \$600.
  * HF = \$800 ÷ \$600 = **1.33** (safe).
  * If ETH drops and collateral is now \$700 → borrowing power = \$560.

    * HF = \$560 ÷ \$600 = **0.93** → liquidation possible.

---

### Summary

* **Collateral Factor:** The maximum % of collateral value you’re allowed to borrow. (Protocol rule)
* **LTV:** Your real-time borrow ratio vs. collateral. (Your current status)
* **Health Factor:** A liquidation risk indicator combining CF and LTV. (Your risk score)

