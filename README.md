
# This contribution improves the Tiber Challenge `tasks.py` file by adding:

1. **Mocked Contract Interactions**  
   - Implemented mocks for Autonity, ERC20, and Uniswap contracts using `unittest.mock` and `HexBytes` for realistic simulation.  
   - Allows developers to **test all challenge tasks locally** without incurring on-chain gas costs.

2. **Real Testnet Verification**  
   - Successfully connected to the **Autonity Piccadilly Testnet** and executed a **real ATN transfer**.  
   - Verified functionality of all 8 challenge tasks both **offline (mocked)** and **online (real RPC)**.  
   - Example Transaction:  
     - **Tx Hash:** `0x1278c8ef19...99e3`  
     - Confirmed via [Piccadilly Block Explorer](https://piccadilly.autonity.org).

3. **Developer Benefits**  
   - Faster iteration with offline testing.
   - Reliable confidence before running code on the live network.
   - Reduced onboarding friction for new participants.

---
# 📸 Project Gallery Of My Contributions 

This section showcases all my contributions and what I done 

## Mock And Tested (User Case Testing) Transaction Outputs
<img width="1920" height="956" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/7d8aacc9-1f7d-419f-b1c8-20cbe2448af0" />

<img width="1920" height="896" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/1dba1a01-2420-417d-bc0a-3394f73880c5" />

---

## Code edited by me in tasks.py and outputs 
<img width="1920" height="1028" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/02df5142-aee3-405d-8428-de9ef73eb68f" />

<img width="1920" height="1028" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/43e9c728-2c87-40a5-842c-192857badb2e" />

<img width="1920" height="1028" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/5f6b8b42-33ae-4ba0-abbf-b68cdef2a49c" />

---

**Summary of Work Done**
- Enhanced `tasks.py` to support **dual-mode testing** (mocked + real).  
- Implemented unit tests with realistic mocks for:
  - Autonity validator functions
  - ERC20 token transfers & balances
  - Uniswap price queries & swaps
- Demonstrated **end-to-end workflow**:
  - Local validation with mocks
  - Real RPC call to Piccadilly Testnet for live transaction confirmation
- Documented workflow for both offline and online execution in the repo’s README.

---

✅ **Outcome:**  
This contribution ensures that future Tiber Challenge participants can **develop, debug, and verify** their solutions locally, and then **seamlessly switch** to the live testnet for final verification.
