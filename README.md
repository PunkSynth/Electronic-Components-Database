# Electronic Components Database
Simple Electronic Components Database for DIY electronic developers, from component storage chaos to organization

## Introduction
This electronic components database is just a single Excel file with three tabs.


```
The first tab <Components> is where you add your components. For each item there
  is an Id, Storage (name of the box), Sub storage (name of the compartment),
  Art no (the manufacturer article number), Item (Description of the component), 
  Supplier, Pc (the number of components), Cost/pc, Inventory (the date when 
  the component was added/updated), Cur Conv (currency conversion, I'm using SEK
  as my main currency), Tot (the total value of the component), Categories 
  (The main Category, e.g., Resistors), Sub1 Categories, and finally Sub2 Categories.
```
  
The Categories column in the Components tab have a drop-down list where you can choose your main category for your component. Depending on the Category, the Sub1
  Categories has a drop-down list as well, based on the main categories. Sub2 Categories has it's drop-down list also.
  
```
The second tab <Parameter> contains the curency conversion parameters.
```
  
```
The third tab <Categories_Tab> contain all the tables used in the drop-down lists.
```

## Example
As an example I have added three components that is stored in "The Box" in the compartments 1, 2, and 3.
  
## License
[GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)
