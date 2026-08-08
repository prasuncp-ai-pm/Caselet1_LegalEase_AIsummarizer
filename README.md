# LegalEase QuickSummarizer — Interactive Working Backwards Caselet

Single-page GitHub Pages prototype for the Institute of Product Leadership caselet **“Business Value Modeling for Generative AI Feature — LegalEase - QuickSummarize.”**

## Includes
- Full company/customer problem context
- Roles, objectives and actions for Anya Sharma, Rohan Mehta, Mr. Khanna, Sanjay Gupta and Priya Singh
- Amazon Working Backwards customer promise / PR framing
- Business value model and editable scenario calculator
- Caselet metrics: adoption, churn, support tickets, engagement and NPS
- Recommended AI safety/quality guardrails
- Interactive QuickSummarizer solution PoC
- Simulated document viewer
- Summary / Ask Questions / Key Terms / Risks & Obligations tabs
- Decision simulator
- Original reflection questions
- Responsive mobile layout
- Print-friendly output

## Run locally
Open `index.html` directly, or run `python -m http.server 8000` and visit `http://localhost:8000`.

## GitHub Pages
Create a GitHub repository, upload `index.html` and `README.md`, commit to `main`, then go to **Settings → Pages → Deploy from a branch → main → /(root)**.

## PoC limitation
The AI analysis is simulated front-end content. It does not call an LLM, process real documents, persist data, provide legal advice, determine enforceability, or connect to a backend.

## Caselet economics
The caselet states that a 5% churn reduction could represent approximately **₹1.5 crore retained ARR over 18 months**, while a 15% reduction in legal-related support tickets could save approximately **₹50 lakh annually**. Implementation/API/operating cost is not specified, so the prototype exposes cost as an editable assumption.

## Source
https://import.cdn.thinkific.com/200429/0bTvqhK1TbmFTA0YmQFl_Caselet_%20Business%20Value%20Modeling%20for%20Generative%20AI%20Feature.pdf
