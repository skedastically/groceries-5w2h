# Read this - 5w2h in groceries shopping

A method to plan my shopping trips using the [5W2Hs](https://www.indeed.com/career-advice/career-development/5w2h-analysis)

## Usage

0. Download the [Excel](groceries.xlsx)/[ODS](groceries.ods) file and open it.

1. Enter your budget (cell `I1`).

2. Browse the flyers[^1] and choose the items you like.

3. In each row, log down `what` the item is, `where` to get it and its listed `price`.

   - Use shortcodes as listed in `$Discount` sheet (e.g. `fb` for Food Basics). The workbook will VLOOKUP() relevant stores to find discounts (`disc`)

   - Toggle on tax (`tax`) if necessary (0=no tax (default), 1=taxed)

4. Assign `category` to each line item (vegetables? fruits? meat? i.e. `why` you buy it)

5. Sort table by `category`.

6. For each category, choose the best deal(s) based on `price` and `where`, and input quantity bought in `quantity`. Try not to go over your budget.

7. Sort table by `where`, and **filter out empty values** in `quantity`. You will have a list of your final items.

8. Determine `when` to shop - which store to go first-to-last in a particular order.

9. (optional, in groups) Determine `who` to shop for each store.

> *Notes: Edit the `Discount` sheet and the discount/tax rates per your needs.*

## Other tips

- Use "Duplicate sheet" to create new plans every week.

- Set a timer towards your next bus to avoid **wasting time**[^2] in the store.

- Think of shopping not as a relaxing period, but a game we have to play in life.

[^1]: Flyers for stores near Fanshawe College main campus (Zip code: `N5Y 5R6`)
    - [FoodBasics](https://foodbasics.ca/flyer.en.html) (requires store selection)
    - [Real Canadian Superstore](https://www.realcanadiansuperstore.ca/print-flyer)
    - [No Frills](https://www.nofrills.ca/print-flyer)
    - [Walmart](https://www.walmart.ca/flyer)
    - [Giant Tiger](https://www.gianttiger.com/collections/flyers-and-deals?view=flyers) (requires postcode)
    - [Metro](https://www.metro.ca/en/flyer)
    - [ValuMart](https://www.valumart.ca/print-flyer) (requires postcode + store selection)
    - [FreshCo](https://freshco.com/flyer/)
    - [Loblaws](https://www.loblaws.ca/print-flyer)
    - [Sobeys](https://www.sobeys.com/en/flyer/)

    Non-groceries
    
    - [Rexall](https://www.rexall.ca/eflyer/) (requires postcode + store selection)
    - [Shopper's](https://www.shoppersdrugmart.ca/en/flyer) (requires postcode + store selection)
    - [Forest City Surplus](https://www.fcsurplus.com/flyer.pdf)
    - [Canadian Tire](https://www.canadiantire.ca/en/flyer.html)

[^2]: "Time is money only when you have money. If you don't have money, time doesn't mean shit" - D.J.
