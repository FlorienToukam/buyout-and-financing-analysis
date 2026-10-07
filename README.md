# Core Molding buyout and financing analysis

I modeled an acquisition of Core Molding Technologies to compare sponsor equity returns, cash funding needs and the effect of seller financing. The main question was whether a higher percentage return justified the additional repayment risk.

## Start here

1. Read the [investment memorandum](Core_Molding_Investment_Memorandum.pdf).
2. Open the [five-year Excel model](Core_Molding_Buyout_Model.xlsx).
3. Begin with `Summary`, then trace `Operating`, `Financing` and `Returns`. Change `Assumptions!D4` to select Downside, Base or Upside. `ESOP` is a separate financing-capacity screen.

## Investment conclusion

I would not advance the modeled acquisition at a 6.0x entry EBITDA multiple without a lower price and committed follow-on capital. Both base structures fall below the model's 20% return hurdle.

| Base case | Senior debt and sponsor equity | With seller financing |
| --- | ---: | ---: |
| Initial sponsor equity | $117.96m | $88.99m |
| Follow-on equity required | $13.68m | $14.54m |
| Gross sponsor XIRR | 14.8% | 16.8% |
| Equity MOIC | 1.97x | 2.13x |
| Exit equity proceeds | $259.60m | $220.23m |

Seller financing reduces the initial equity investment, but the note grows to $35.25 million by exit and its cash interest slows senior-debt repayment. In the downside, the seller-financed structure returns 0.75x invested equity versus 0.87x without the note.

## Why cash conversion matters

FY 2025 operating cash flow less capital spending was $1.92 million. The same calculation for the twelve months through June 2026 was negative $8.30 million despite $28.97 million adjusted EBITDA. I separated production revenue from tooling, modeled working capital and capital expenditure, and included follow-on sponsor funding in XIRR and MOIC.

The price sensitivity holds base operations and the exit multiple constant. It produces entry enterprise-value ceilings of $149.23 million without the seller note and $161.43 million with it to reach the selected 20% hurdle. These are conditional model outputs, not company appraisals.

## Scope and assumptions

Entry and exit use 6.0x adjusted EBITDA. The senior loan is 2.5x entry EBITDA, with 8% cash interest and 5% annual original-principal amortization. The seller-financed case adds a 1.0x note with 4% cash interest and 4% payment-in-kind interest. Transaction, financing and exit costs are included.

The company figures come from public disclosures. Acquisition terms, growth, margins and financing structures are modeling assumptions. The projected returns are investment-level gross sponsor outcomes before fund fees, carry and investor taxes. There is no claim of an actual transaction or historical private-equity performance.

The ESOP screen removes outside sponsor equity and identifies an unfunded $17.17 million first-year requirement in the base case. It does not model trust accounting, participant allocations, repurchase obligations or tax benefits.

## Sources and checks

Primary references are Core Molding's FY 2025 results, H1 2026 results and 2025 annual report. Full URLs and context are in [sources.json](sources.json) and the workbook's `Sources` sheet.

Workbook results were independently recalculated across all three operating cases and both buyout structures. The saved model opens in the base case. See [the verification record](model-verification.json).

Case updated October 1, 2026.
