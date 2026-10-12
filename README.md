# Car Sales Tax, Title & Registration Fees by U.S. State (2026)

Open dataset of vehicle sales tax rates and DMV title/registration fees for all 50 states and Washington, DC.
Every figure comes from the official state DMV or revenue department page listed in the `official_source` column.

Maintained by **[US Vehicle Tax Calculator](https://usvehicletaxcalculator.com/)**, a free calculator for tax, title and license costs in every state.
Last checked: **2026-10-07**.

## Files

| File | Contents |
|---|---|
| [`car-sales-tax-by-state.csv`](car-sales-tax-by-state.csv) | One row per state (51 rows) |
| [`car-sales-tax-by-state.json`](car-sales-tax-by-state.json) | Same data as JSON |

## Columns

- `state_rate_pct`: statewide vehicle sales/use tax rate. Blank where the state uses a different tax (for example North Carolina's Highway Use Tax or Oklahoma's excise tax); see `tax_type`.
- `local_tax`: whether city/county tax is added on top.
- `tax_on_30000_new_car`: state-level tax on a $30,000 new car bought from a dealer, with no trade-in and no local tax (Nevada includes its 6.85% statewide minimum).
- `title_and_registration_fees`: first-year title, plate and registration fees for a typical gas passenger car in the same scenario.
- `trade_in_dealer_new`: whether a dealer trade-in lowers the taxable price.
- `status`: `verified` = every figure confirmed on an official page; `tax rates verified` = tax rates confirmed, some smaller fees still being checked.

## Cheapest and most expensive states ($30,000 new car, tax + fees)

Cheapest: Alaska ($115.00), Montana ($258.53), Oregon ($418.00), South Carolina ($555.00), Alabama ($642.25).
Most expensive: California ($2,647.00), Minnesota ($2,628.00), Nevada ($2,541.85), Maine ($2,486.00), Washington ($2,364.25).

## All states

| State | State rate | Tax on $30k | Title & reg. fees | Total | Dealer trade-in |
|---|---|---|---|---|---|
| [Alabama](https://usvehicletaxcalculator.com/states/alabama/) | 2% | $600.00 | $42.25 | $642.25 | full credit |
| [Alaska](https://usvehicletaxcalculator.com/states/alaska/) | 0% | $0.00 | $115.00 | $115.00 | full credit |
| [Arizona](https://usvehicletaxcalculator.com/states/arizona/) | 5.6% | $1,680.00 | $551.10 | $2,231.10 | full credit |
| [Arkansas](https://usvehicletaxcalculator.com/states/arkansas/) | 6.5% | $1,950.00 | $38.00 | $1,988.00 | partial credit |
| [California](https://usvehicletaxcalculator.com/states/california/) | 7.25% | $2,175.00 | $472.00 | $2,647.00 | no credit |
| [Colorado](https://usvehicletaxcalculator.com/states/colorado/) | 2.9% | $870.00 | $635.80 | $1,505.80 | full credit |
| [Connecticut](https://usvehicletaxcalculator.com/states/connecticut/) | 6.35% | $1,905.00 | $254.00 | $2,159.00 | full credit |
| [Delaware](https://usvehicletaxcalculator.com/states/delaware/) | 5.25% | $1,575.00 | $75.00 | $1,650.00 | full credit |
| [District of Columbia](https://usvehicletaxcalculator.com/states/district-of-columbia/) | see note | $1,230.00 | $240.00 | $1,470.00 | no credit |
| [Florida](https://usvehicletaxcalculator.com/states/florida/) | 6% | $1,800.00 | $373.85 | $2,173.85 | partial credit |
| [Georgia](https://usvehicletaxcalculator.com/states/georgia/) | 7% | $2,100.00 | $38.00 | $2,138.00 | full credit |
| [Hawaii](https://usvehicletaxcalculator.com/states/hawaii/) | see note | $1,350.00 | $107.25 | $1,457.25 | no credit |
| [Idaho](https://usvehicletaxcalculator.com/states/idaho/) | 6% | $1,800.00 | $84.25 | $1,884.25 | full credit |
| [Illinois](https://usvehicletaxcalculator.com/states/illinois/) | 6.25% | $1,875.00 | $316.00 | $2,191.00 | full credit |
| [Indiana](https://usvehicletaxcalculator.com/states/indiana/) | 7% | $2,100.00 | $51.35 | $2,151.35 | full credit |
| [Iowa](https://usvehicletaxcalculator.com/states/iowa/) | see note | $1,510.00 | $35.00 | $1,545.00 | full credit |
| [Kansas](https://usvehicletaxcalculator.com/states/kansas/) | 6.5% | $1,950.00 | $40.00 | $1,990.00 | full credit |
| [Kentucky](https://usvehicletaxcalculator.com/states/kentucky/) | 6% | $1,800.00 | $30.00 | $1,830.00 | full credit |
| [Louisiana](https://usvehicletaxcalculator.com/states/louisiana/) | 5% | $1,500.00 | $136.50 | $1,636.50 | full credit |
| [Maine](https://usvehicletaxcalculator.com/states/maine/) | 5.5% | $1,650.00 | $836.00 | $2,486.00 | full credit |
| [Maryland](https://usvehicletaxcalculator.com/states/maryland/) | 6.5% | $1,950.00 | $320.50 | $2,270.50 | full credit |
| [Massachusetts](https://usvehicletaxcalculator.com/states/massachusetts/) | 6.25% | $1,875.00 | $135.00 | $2,010.00 | full credit |
| [Michigan](https://usvehicletaxcalculator.com/states/michigan/) | 6% | $1,800.00 | $218.00 | $2,018.00 | full credit |
| [Minnesota](https://usvehicletaxcalculator.com/states/minnesota/) | 6.88% | $2,062.50 | $565.50 | $2,628.00 | full credit |
| [Mississippi](https://usvehicletaxcalculator.com/states/mississippi/) | 5% | $1,500.00 | $38.00 | $1,538.00 | full credit |
| [Missouri](https://usvehicletaxcalculator.com/states/missouri/) | 4.23% | $1,267.50 | $77.75 | $1,345.25 | full credit |
| [Montana](https://usvehicletaxcalculator.com/states/montana/) | 0% | $0.00 | $258.53 | $258.53 | n/a (no tax) |
| [Nebraska](https://usvehicletaxcalculator.com/states/nebraska/) | 5.5% | $1,650.00 | $38.70 | $1,688.70 | full credit |
| [Nevada](https://usvehicletaxcalculator.com/states/nevada/) | see note | $2,055.00 | $486.85 | $2,541.85 | full credit |
| [New Hampshire](https://usvehicletaxcalculator.com/states/new-hampshire/) | 0% | $0.00 | $667.00 | $667.00 | n/a (no tax) |
| [New Jersey](https://usvehicletaxcalculator.com/states/new-jersey/) | 6.63% | $1,987.50 | $119.00 | $2,106.50 | full credit |
| [New Mexico](https://usvehicletaxcalculator.com/states/new-mexico/) | 4% | $1,200.00 | $79.50 | $1,279.50 | full credit |
| [New York](https://usvehicletaxcalculator.com/states/new-york/) | 4% | $1,200.00 | $141.50 | $1,341.50 | full credit |
| [North Carolina](https://usvehicletaxcalculator.com/states/north-carolina/) | see note | $900.00 | $113.00 | $1,013.00 | full credit |
| [North Dakota](https://usvehicletaxcalculator.com/states/north-dakota/) | 5% | $1,500.00 | $98.00 | $1,598.00 | full credit |
| [Ohio](https://usvehicletaxcalculator.com/states/ohio/) | 5.75% | $1,725.00 | $62.00 | $1,787.00 | full credit |
| [Oklahoma](https://usvehicletaxcalculator.com/states/oklahoma/) | see note | $1,350.00 | $127.25 | $1,477.25 | partial credit |
| [Oregon](https://usvehicletaxcalculator.com/states/oregon/) | 0.5% | $150.00 | $268.00 | $418.00 | no credit |
| [Pennsylvania](https://usvehicletaxcalculator.com/states/pennsylvania/) | 6% | $1,800.00 | $120.00 | $1,920.00 | full credit |
| [Rhode Island](https://usvehicletaxcalculator.com/states/rhode-island/) | 7% | $2,100.00 | $157.00 | $2,257.00 | full credit |
| [South Carolina](https://usvehicletaxcalculator.com/states/south-carolina/) | see note | $500.00 | $55.00 | $555.00 | full credit |
| [South Dakota](https://usvehicletaxcalculator.com/states/south-dakota/) | 4% | $1,200.00 | $12.00 | $1,212.00 | full credit |
| [Tennessee](https://usvehicletaxcalculator.com/states/tennessee/) | 7% | $2,144.00 | $40.50 | $2,184.50 | partial credit |
| [Texas](https://usvehicletaxcalculator.com/states/texas/) | 6.25% | $1,875.00 | $92.00 | $1,967.00 | full credit |
| [Utah](https://usvehicletaxcalculator.com/states/utah/) | 4.85% | $1,455.00 | $203.50 | $1,658.50 | full credit |
| [Vermont](https://usvehicletaxcalculator.com/states/vermont/) | 6% | $1,800.00 | $141.00 | $1,941.00 | full credit |
| [Virginia](https://usvehicletaxcalculator.com/states/virginia/) | 4.15% | $1,245.00 | $45.75 | $1,290.75 | no credit |
| [Washington](https://usvehicletaxcalculator.com/states/washington/) | 6.5% | $2,100.00 | $264.25 | $2,364.25 | full credit |
| [West Virginia](https://usvehicletaxcalculator.com/states/west-virginia/) | 6% | $1,800.00 | $66.50 | $1,866.50 | full credit |
| [Wisconsin](https://usvehicletaxcalculator.com/states/wisconsin/) | 5% | $1,500.00 | $311.50 | $1,811.50 | full credit |
| [Wyoming](https://usvehicletaxcalculator.com/states/wyoming/) | 4% | $1,200.00 | $621.00 | $1,821.00 | full credit |

Local taxes, vehicle weight, age, price and county fees change the real amount. Use the [calculator](https://usvehicletaxcalculator.com/) for an estimate with your own numbers.

## License

[CC BY 4.0](LICENSE). You can use, share and adapt the data, including commercially. Please credit
**US Vehicle Tax Calculator** with a link to https://usvehicletaxcalculator.com/.

## Corrections

Found a rate that changed? Open an issue with a link to the official source, or email contact@usvehicletaxcalculator.com.
