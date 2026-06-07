# Trading Tax Calculator

A standalone, browser-based tax estimator built for active traders
with complex income situations — prop firm payouts, stocks and ETFs,
Section 1256 futures contracts, rental income, and W-2 wages. No
installation required. Open the HTML file in any browser and it works.
All data saves automatically to your browser between sessions.

Built because standard tax calculators don't understand trader tax
status, the 60/40 futures rule, or how prop firm income is actually
taxed. This one does.

---

## Screenshot

<img width="866" height="1264" alt="Screenshot 2026-06-06 at 10 04 54 PM" src="https://github.com/user-attachments/assets/6934e4a4-ab87-4c72-98e9-f5dd4ddc7980" />
<img width="896" height="1277" alt="Screenshot 2026-06-06 at 10 05 10 PM" src="https://github.com/user-attachments/assets/193aac89-0a7b-45c7-9839-41b89f59da55" />

---

## Features

### Both Versions
- **Prop firm income** — gross payouts (1099-NEC) minus deductible
  expenses (challenge fees, PA fees, platform costs); taxed as
  self-employment income, not capital gains
- **Stocks & ETFs** — short-term and long-term net gain/loss with
  prior year loss carryforward
- **Futures (Section 1256)** — net gain/loss from broker or Form 6781
  with prior year Sec. 1256 loss carryforward; 60/40 long/short-term
  blended rate applied automatically
- **Rental income** — gross income minus expenses with prior year
  passive loss carryforward
- **All 50 states + Washington D.C.** — bracket-calculated effective
  state tax rates with standard deductions per filing status
- **Quarterly estimated tax planner** — Q1 through Q4 federal and
  state payment tracker with due dates; shows balance remaining after
  payments already made
- **Lock buttons** — lock any field to prevent accidental changes
- **Auto-saves** — all inputs persist in browser localStorage

### v2.0 Only (Day Trading — Full Version)
- **W-2 income** — wages plus federal and state withholding already
  paid via payroll
- **Self-employment business income** — supports sole proprietor,
  single-member LLC, and S-Corporation structures; S-Corp handles
  reasonable salary, payroll withholding, and pass-through
  distributions separately
- **Full FICA section** — Social Security (6.2%), Medicare (1.45%),
  and Additional Medicare Tax (0.9% on wages over $200K single /
  $250K MFJ); current year withheld and prior year paid tracked
  separately
- **NIIT** — Net Investment Income Tax (3.8%) calculated for
  high-income filers
- **IRA eligibility and contributions** — Traditional IRA, Roth IRA,
  and Roth conversion tracking; age 50+ catch-up contribution support;
  Roth income phase-out applied automatically
- **Safe harbor calculation** — compares current year payments to
  prior year tax liability to flag underpayment risk
- **Deductible trading expenses** — shared deduction across all
  trading income streams

---

## Version History

### v2.0 — Day Trading Tax Calculator [current] (`day_trading_tax_calculator.html`)
Full-featured day trading tax calculator for traders with W-2 income,
self-employment structures, and multiple income streams.

- Added W-2 wages and withholding (federal and state)
- Added self-employment and business income section with sole prop,
  single-member LLC, and S-Corporation support
- Added full FICA section (SS, Medicare, Additional Medicare Tax)
  with current year withheld and prior year paid
- Added NIIT (3.8%) for high-income filers
- Added IRA contribution tracking with Roth eligibility phase-out
  and age 50+ catch-up support
- Added Roth conversion tracking
- Added safe harbor calculation against prior year tax liability
- Added deductible trading expenses field shared across income streams

### v1.0 — Simple Version (`simple_trading_tax_calculator.html`)
First version covering the core trader tax situations — prop firm,
stocks, futures, and rental income.

- Prop firm income (1099-NEC) with deductible expense offset
- Stocks and ETFs with short-term, long-term, and carryforward
- Futures with Section 1256 60/40 treatment and loss carryforward
- Rental income with passive loss carryforward
- All 50 states + D.C. with bracket-calculated effective rates
- Quarterly estimated payment tracker (Q1–Q4)
- Lock buttons on all fields
- Browser localStorage persistence

---

## How to Use

1. Download the version that fits your situation:
   - **Simple version** — prop firm + trading + rental income only
   - **Full version** — add W-2 income, self-employment structures,
     FICA, and IRA tracking
2. Open the file in any modern browser — Chrome, Firefox, Safari,
   or Edge
3. No internet connection needed after download
4. Select your filing status and state of residence
5. Fill in your income sections (leave at zero for any that
   don't apply)
6. Enter estimated payments already made this year
7. Your tax breakdown and quarterly payment schedule update
   in real time

Your inputs save automatically in your browser. Use the lock
buttons to protect values you don't want changed accidentally.

---

## Important Tax Notes

- **Prop firm payouts** are self-employment income taxed at ordinary
  rates plus 15.3% SE tax — the 60/40 futures rule does not apply
  to them
- **Section 1256 futures** receive 60/40 blended rate treatment
  (60% long-term, 40% short-term) federally; all states tax futures
  as ordinary income
- **Rental income** is passive — no SE tax applies; passive loss
  rules and depreciation recapture are not modeled
- **QBI deductions** are not modeled — consult a CPA
- Results are estimates only — consult a tax professional for advice
  specific to your situation

---

## Built With

- HTML, CSS, JavaScript
- No frameworks or dependencies — single file, works offline
- Browser localStorage for data persistence
- 2025 federal tax brackets and all 50-state bracket data built in

---

## A Note on How This Was Built

These calculators were built collaboratively with Claude
(Anthropic's AI). I defined the requirements, iterated on each
version, tested the outputs against real tax scenarios, caught
and corrected calculation errors, and drove every decision about
what to build and how. Claude helped with code generation and
iteration. The problem-solving, product thinking, and validation
were mine.

I believe in being transparent about AI-assisted work.

---

## License

This project is licensed under the GNU General Public License v3.0.
See the [LICENSE](LICENSE) file for details.

Free to use and modify. If you distribute a modified version, you
must also make your source code available under the same GPL v3
license.

---

## Author

**Meagan Lapworth**
[linkedin.com/in/meagan-lapworth-smallwinz](https://www.linkedin.com/in/meagan-lapworth-smallwinz)
[github.com/MeaganLapworth](https://github.com/MeaganLapworth)
