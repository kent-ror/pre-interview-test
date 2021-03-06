# RadiusOnline Screening Test

#### SALES TAXES

Basic sales tax is applicable at a rate of 10% on all goods, except books, food, and medical products that are exempt. Import duty is an additional sales tax applicable on all imported goods at a rate of 5%, with no exemptions.

When I purchase items I receive a receipt that lists the name of all the items and their price (including tax), finishing with the total cost of the items, and the total amounts of sales taxes paid. The rounding rules for sales tax are that for a tax rate of n%, a shelf price of p contains (np/100 rounded up to the nearest 0.05) amount of sales tax.

- [ ] Implement a page printing out the receipt details (as a HTML page) for these shopping carts (see Input 1, Input 2, Input 3)
- [ ] Write a rspect (optional)

Proper object orientated design is important. Each row in the input represents a line item of the receipt.

#### Input 1
Quantity | Product | Price
:------: | :-----: | :----:
1 | book | 12.49
1 | music cd | 14.99
1 | chocolate bar | 0.85

#### Output 1
Quantity | Product | Price
:------: | :-----: | :----:
1 | book | 12.49
1 | music CD | 16.49
1 | chocolate bar | 0.85

Sales Taxes: 1.50

Total: 29.83

#### Input 2
Quantity | Product | Price
:------: | :-----: | :----:
1 | imported box of chocolates | 10.00
1 | imported bottle of perfume | 47.50

#### Output 2
Quantity | Product | Price
:------: | :-----: | :----:
1 | imported box of chocolates | 10.50
1 | imported bottle of perfume | 54.65

Sales Taxes: 7.65

Total: 65.15

#### Input 3
Quantity | Product | Price
:------: | :-----: | :----:
1 | imported bottle of perfume | 27.99
1 | bottle of perfume | 18.99
1 | packet of headache pills | 9.75
1 | box of imported chocolates | 11.25

#### Output 3
Quantity | Product | Price
:------: | :-----: | :----:
1 | imported bottle of perfume | 32.19
1 | bottle of perfume | 20.89
1 | packet of headache pills | 9.75
1 | imported box of chocolates | 11.85

Sales Taxes: 6.70

Total: 74.68

## Coding Style
Please follow the guidelines below when developing this project.

- [Ruby on Rails Coding Style Guidelines](https://github.com/kent-ror/rails-style-guide)

## References

[1] http://www.ruby-lang.org

[2] https://github.com/kent-ror/rails-style-guide