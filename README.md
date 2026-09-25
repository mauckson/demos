# Demos

Three browser-only demos by Ian Mauck. All three run entirely in your browser: nothing is uploaded, no account is created on a server, and no data leaves the page. Every portfolio, fund, manager and letter is synthetic, written for the demo; the few published figures (index returns in Allocate's stress scenarios, and company outcome shares in Fund Sim's calibration table) are cited where they appear.

## Allocate

Allocate is a "close the month" tool for institutional allocators such as endowments, foundations, and family offices. It walks a portfolio through five steps: what data came in, what could become cash and by when, where the portfolio sits against its policy targets and bands, what changed at the managers, and a review of ranked flags with a memo. It also carries a raise-cash planner, a records ledger, three stress scenarios (the GFC and the dot-com bust on their own calendar returns, and a COVID-shaped path), and five bear-market drawdown windows. A built-in sample portfolio loads on sign-in; you can also upload your own spreadsheet or a folder of statements, which are read in the browser only. Open it at `allocate/`.

## Manager Monitor

Manager Monitor reads a fund manager's quarterly letter, extracts a fixed set of fields, cites the exact sentence each value came from, diffs the quarter against the prior one, and drafts a change memo ranked by materiality. The demo runs in scripted mode on synthetic letters, so it makes no calls to any AI service. Open it at `manager-monitor/`.

## Fund Sim

Fund Sim is a seed fund portfolio construction simulator. Set a fund's size, fees, carry, number of first checks, entry price, reserves and follow-on strategy, and it runs thousands of funds on a power-law outcome distribution to show the spread of net multiples, the chance of returning the fund, when cash comes back, and the reserves a strategy actually needs. Three scenarios can be compared side by side, and an LP view shows calls, distributions and net cash flow by year, with net IRR across runs. Every default is an illustrative assumption, not market data, and the simulation runs in your browser. Open it at `fund-sim/`.

## Data disclaimer

All portfolios, funds, managers, letters, returns, documents and fund parameters in these demos are synthetic or illustrative and were written for illustration. They do not describe any real institution, fund, manager, or client, and nothing here is investment advice. Index figures in Allocate's stress scenarios are published public index returns, and Fund Sim's calibration table sets its results beside published figures; both are cited inside the app.
