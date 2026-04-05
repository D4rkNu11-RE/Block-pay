# BlockPay

BlockPay is a mini prototype demonstrating how a trust-based escrow payment flow can work between merchants and customers. It is designed as an educational proof-of-concept for enterprise-style agreements, not as a finished product.

> **Note:** This is not a completed project — it is a mini prototype. Keep that in mind when exploring the code and behavior.

## What this project contains

The `Black_pay` folder contains the source code for this prototype. It includes Python modules for handling customer, merchant, and bank interactions, plus a very basic UI mockup to show how payment steps might be presented.

## Key ideas

- A trusted escrow-style flow where money is held until an agreed event happens.
- Simple separation of roles: customer, merchant, and acquirer bank.
- A learning prototype for how blockchain-style confirmation and fund release could be represented.

## Files in `Black_pay`

- `acquirer_bank.py` – handles bank-side logic for approving or releasing funds.
- `BLOCKCHAIN.PY` – represents the blockchain or ledger logic used for tracking transaction state.
- `customer.py` – customer-facing logic around requesting payment and confirming delivery.
- `merchant.py` – merchant-facing logic for submitting orders and tracking confirmations.
- `db_setup.py` – database setup or initialization support for prototype data storage.
- `dm.html`, `sr.html`, `sr1.html` – simple HTML pages for demo screens.
- `dm1.css`, `sr.css` – CSS styles for the prototype front-end screens.

## How to explore this prototype

1. Open the `Black_pay` folder.
2. Review the Python files to understand how the roles interact.
3. Open the HTML files in a browser to see the prototype UI screens.
4. Remember this project is a concept demo, so the behavior is simplified.

## Recommended focus areas

- `BLOCKCHAIN.PY` to understand how transaction state is tracked.
- `customer.py` and `merchant.py` to see the flow between buyer and seller.
- `acquirer_bank.py` for the payment release logic.

## Why it matters

This prototype helps explain the value of using a middleman or escrow-style system in cases where trust and verification are important. The code is meant to teach the core idea rather than serve as production-ready software.

## Next steps if you want to continue development

- Add real payment gateway integration.
- Improve the blockchain model and transaction validation.
- Add a proper web app interface instead of static HTML.
- Build more robust error handling, logging, and security.

---

Thank you for checking out BlockPay!