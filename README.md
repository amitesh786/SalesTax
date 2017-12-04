# SalesTax issue from user define input

1) Implemented Decorator design pattern for tax calculation
2) Create dynamic model for shopping cart. 
3) Code read input from file system -> inputs/input1.txt, inputs/input2.txt, inputs/input3.txt
4) Code handles input errors for example if you pass the argument inputs/input4.txt -> 
   error:inputs/input4.txt (No such file or directory)

Inputs:
1 book at 12.49
1 chocolate bar at .85
1 music CD at 14.99
Outputs:
1 book: 12.49
1 chocolate bar: .85
1 music CD: 16.49
Sales Taxes: 1.50
Total: 29.83

Inputs:
1 imported box of chocolates at 10.00
1 imported bottle of perfume at 47.50
Outputs:
1 imported box of chocolates: 10.50
1 imported bottle of perfume: 54.65
Sales Taxes: 7.65
Total: 65.15

Inputs:
1 packet of headache pills at 9.75
1 bottle of perfume at 18.99
1 box of imported chocolates at 11.25
1 imported bottle of perfume at 27.99
Outputs:
1 packet of headache pills: 9.75
1 bottle of perfume: 20.89
1 box of imported chocolates: 11.85
1 imported bottle of perfume: 32.19
Sales Taxes: 6.70
Total: 74.68
