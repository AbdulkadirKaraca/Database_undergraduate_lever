# Database_undergraduate_lever
Designed and developed a mock online shopping database. And using oracle form and report to create a interface to maintain and manipulate the database.


# Jixiang Lu

# Database Initial Study

# CS-457 Database Design

## Analyze the company:

### Description of the company:
This company is a large-scale and third-party electronic shopping website. As a shopping platform, its purpose is that buyers and sellers use simple, efficient, low-cost electronic means of communication, to conduct various business activities without face-to-face. There are two back management systems, one for buyers to choose some goods to buy and check the order, one for supplier to handle orders and manage product. Therefore, it needs to record the buyer registers information, the Supplier's information, the details of the goods, the mail type information, the account information, the address information and the order information. It is necessary for the company to design a database to manage the information.

### Existing Database System:

### What data goes into the system
#### Customer：
* Add the information of customers: Customer_ID (automatically generate), Last Name, First name, Phone Number, Email, Password, Address_ID.
* Add the information of address: Address_ID (automatically generate), Street, City, State, Country, and Postcode.
* Add the information of account: Pay Number (automatically generate), Card type, Pay Account, Pay Status and Cvv.
* Add the information of order: Order Number (automatically generate), Customer_ID, Goods_ID, Order Data, Goods Quantity, Ship Number, Pay Number and total price.
#### Supplier:
* Add the information of Supplier: Company_ID(automatically generate), Company Name, Company Telephone, Company Email, Company Password, Company Account, Address_ID
* Add the information of Goods: Goods_ID(automatically generate), Goods Name, Goods Introduction, Goods Weight, Goods Unit, Goods MarketPrice, Goods MemberPrice, Goods Picture Url, Goods inventory, Company_ID and Label_ID.
* Add the information of address: Address_ID (automatically generate), Street, City, State, Country, and Postcode.
* Add the information of shipping: Ship_ID (automatically generate), Ship Type, Ship Fee and Company_ID.
#### Website manager:
* Add the information of goods label: Label_ID (automatically generate), Label_name.
### What output is produced
#### To Customer:
* Query the information of customers: Customer_ID (automatically generate), Last Name, First name, Phone Number, Email, Password.
* Query the information of address: Street, City, State, Country, and Postcode.
* Query the information of account: Card type, Pay Account, Pay Status and Cvv.
* Query the information of order: Order Number (automatically generate), Customer_ID, Order Data, Goods Quantity, and total price.
* Query the information of Goods: Goods Name, Goods Introduction, Goods Weight, Goods Unit, Goods MarketPrice, Goods MemberPrice, Goods Picture Url, Goods inventory.
* Query the information of shipping: Ship Type, Ship Fee.
* Query the information of goods label: Label_name.
* Query the information of Supplier: Company Name, Company Telephone, Company Email.
* Query the information of Supplier address: Street, City, State, Country, and Postcode.
#### To Supplier:
* Query the information of Supplier: Company_ID(automatically generate), Company Name, Company Telephone, Company Email, Company Password, Company Account.
* Query the information of address: Street, City, State, Country, and Postcode.
* Query the information of order: Order Number (automatically generate), Order Data, Goods Quantity, and total price
* Query the information of customer address: Street, City, State, Country, and Postcode.
* Query the information of account: Pay Status.
* Query the information of shipping: Ship Type, Ship Fee and Company_ID.
* Query the information of Goods: Goods Name, Goods Introduction, Goods Weight, Goods Unit, Goods MarketPrice, Goods MemberPrice, Goods Picture Url, Goods inventory.
* Query the information of goods label: Label_name.
* Query the information of customers: Last Name, First name, Phone Number, Email.
### Who use the output:

* There are two background managing systems, one for buyers to set themselves information, choose some goods to buy and check the order, one for suppliers to set themselves information, handle orders and manage product.

### What kind of problems have been determined with the existing system?
		Hardware related problems:
			Resource problems (insufficient resources)
		Software related problems:
It is necessary for this website to need a third parties software to pay for the orders safety.
		Performance issues:
			The website needs to run on a server 24 hours a day.

### Define Objective:

#### The new system:
* The information of customer Table
* The information of supplier Table
* The information of address Table
* The information of order Table
* The information of goods Table
* The information of goods-label Table
* The information of shipping Table
* The information of Account Table

### Initial Objective:
* This website is a third-party electronic shopping website. The company will just conduct software maintenance and troubleshooting for application and database servers. buying and selling will be finished by customers and suppliers.

### Define Scope and Boundaries:

* Time constraints:

### The company wants the new system to be fully operational within 6 weeks.

* Budget constraints:

* No funds.

* Hardware and software constraint:

The new system must operated on the company’s existing local network and must be be developed with oracle DBMS.


