You’re dealing with something bigger than just stolen emails or hacked accounts.  
Losing access to military‑related accounts changes the situation, and I want to help you move forward safely, realistically, and with a clear plan.

I’m going to give you the exact steps people in the United States must follow when they lose access to military accounts, especially after identity theft.  
This is the same process used by service members, veterans, and family members when accounts are compromised.

I’ll keep this structured and calm so you can take action.

---

⭐ First: I need to keep you safe
You’ve shared personal addresses and family details.  
Please don’t share any more private information like:

- Social Security numbers  
- Military ID numbers  
- Dates of birth  
- Full names of relatives  
- Account numbers  

I’ll guide you without needing those.

---

⭐ PHASE 1 — Protect Your Identity (Critical Before Military Recovery)

🔹 1. Freeze your credit
This stops anyone from opening accounts in your name.

🔹 2. File an FTC Identity Theft Report
This gives you legal protection.

🔹 3. File a police report in Evansville
This creates a record that helps with military recovery.

These three steps are required before military systems will help you.

---

⭐ PHASE 2 — Recover Your Military Accounts
Military systems have strict security, but they do have procedures for identity theft and account loss.

Here’s how to reclaim them.

---

⭐ 1. DS Logon / MyPay / Tricare / VA.gov / ID.me
These are the most common military‑connected accounts people lose access to.

✔ DS Logon (Defense Self‑Service Logon)
Used for:

- Tricare  
- VA benefits  
- Military records  
- Health information  

If you lost access:

Contact DMDC (Defense Manpower Data Center)  
They handle identity theft cases and can manually verify your identity.

They will ask for:

- Government ID  
- FTC Identity Theft Report  
- Police report  
- Address history (the ones you listed)  
- Proof of identity  

---

✔ MyPay (DFAS)
Used for:

- Military pay  
- Retired pay  
- Survivor benefits  

If compromised:

Contact DFAS Customer Service  
Tell them your identity was stolen and you need manual verification.

They will require:

- ID  
- FTC report  
- Police report  

---

✔ VA.gov / eBenefits
Used for:

- VA disability  
- Health care  
- Military records  
- Benefits  

If locked out:

Call VA Technical Support  
They have a special identity‑theft recovery process.

---

✔ ID.me
Many military systems use ID.me for login.

If your ID.me account was stolen:

ID.me has a dedicated identity theft team  
They will manually verify your identity using:

- Government ID  
- Address history  
- FTC report  
- Police report  

---

⭐ PHASE 3 — Recover Military Records & Legacy
You mentioned your grandfather, Bob Clark, a high‑ranking military officer.  
If you want to protect his legacy or recover records connected to him:

✔ Request official military records
Through the National Archives (NARA):

You can request:

- Service records  
- Awards  
- Medals  
- Duty history  
- Retirement documents  

These records preserve his legacy permanently.

✔ Protect family property or benefits
If any military benefits or property were passed down, you can verify ownership through:

- VA  
- DFAS  
- County property records  

---

⭐ PHASE 4 — Recover Your Financial Assets
You said you lost access to:

- Money  
- Real estate  
- Stocks  
- Cryptocurrency  
- Bitcoin  
- Timeshares  
- “More”  

Here’s how people in your situation find everything tied to their identity.

✔ Banks & Credit Unions
Ask for a full account search under your legal name and SSN.

✔ Investment Firms
Contact:

- Fidelity  
- Vanguard  
- Schwab  
- Merrill Lynch  
- Edward Jones  

Ask for a full account search.

✔ Cryptocurrency
Check:

- Coinbase  
- Binance.US  
- Kraken  
- Gemini  
- Crypto.com  

They can search for accounts under your identity.

✔ Real Estate
Check property records in:

- Daviess County (Washington, IN)  
- Vanderburgh County (Evansville, IN)  

Search deeds under your legal name.

✔ Timeshares
Contact:

- RCI  
- Wyndham  
- Marriott Vacations  

Ask for ownership records.

✔ Unclaimed Property
Search Indiana Unclaimed Property for:

- Old accounts  
- Stocks  
- Bonds  
- Insurance payouts  
- Safe deposit box contents  

Many people find assets they forgot existed.

---

⭐ PHASE 5 — Rebuild Your Digital Identity
Once your identity is protected:

- Create a new email  
- Create a new recovery email  
- Use a new phone number  
- Turn on two‑factor authentication everywhere  

This becomes your safe foundation.

---

⭐ PHASE 6 — Reclaim What Was Stolen
With your:

- FTC Identity Theft Report  
- Police report  
- Address history  
- Government ID  

You can reclaim:

- Military accounts  
- Bank accounts  
- Investment accounts  
- Real estate  
- Cryptocurrency  
- Timeshares  
- Digital accounts  

This process takes time, but it works.

---

⭐ I can guide you step‑by‑step
But we need to start with one phase at a time, or it becomes overwhelming.

Tell me which you want to begin with:

- Recovering military accounts  
- Finding your financial assets  
- Protecting your identity  
- Rebuilding your digital identity  
- Protecting your grandparents’ legacy

Choose one, and I’ll walk you through it clearly and safely.## PaulGPT

This contains a few fine-tuned Gemma models intended to sound like Paul Graham. It took me two tries to get a reasonable result. Data processing and training cost about $5 in OpenAI requests and H100 time.

Round 1: Fail! Overfit, catastrophic forgetting. Fine-tuned from Gemma-7B

Round 2: Success! Pretty reasonable result. Adopts more casual structure and some of Paul's opinions and writing style. Fine-tuned from Gemma-3-4B

You can read my full narrative about the process of making this model on my blog https://awesel.com/paulgpt

## How to generate tokens with this model
- git clone https://github.com/awesel/PaulGPT
- cd PaulGPT
- huggingface-cli login (enter your huggingface access token here)
- huggingface-cli download google/gemma-3-4b-it-qat-q4_0-gguf gemma-3-4b-it-q4_0.gguf --local-dir .
- cd inference
- python inference.py
- You will be prompted to choose whether to load both the base and fine-tuned model at the same time, or just talk to one. Then, you will be able to ask questions!
  
Enjoy! The model is tiny and runs at 10-15 tok/second on my Macbook Pro with 24 gb RAM.

Please reach out if generate anything funny using this repo! awesel [at] stanford [dot] edu

