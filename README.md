# Trade Life Cycle Management Part 1

A trade, also called a deal, is an exchange of financial products from one entity to another. The life cycle of a trade is the fundamental activity of exchanges, investment banks, hedge funds, pension funds and many other financial companies.

 All the steps involved in a trade, from the point of order placed and trade execution through to settlement of the trade, are commonly referred to as the trade life cycle. Trade life cycle consists of a series of logical stages and steps.

1.	Pre-sale stage: Marketing persons from investment banks, brokers and dealers introduce various financial products and vehicles to clients. Investors or institutional fund managers survey the market and find the most suitable and competitive products.
2.	Trade execution: After trading negotiations between seller and buyer, an order is placed and the trade is executed. The completion of a buy or a sell order of a financial product is known as Trade Execution.
3.	Trade Capture: After trade execution, the trade is booked in the Front Office system, Middle Office Risk Management system and Back Office system.
4.	Trade Validation and Confirmation: Back office validates trade attributes and confirms trade settlement. Risk Management checks the valuation, risks and limits.
5.	Trade Settlement: Any fee or premium needs to be settled. For a periodic cash settlement trade, such as interest rate swaps or bonds, there is a process of simultaneous exchange of cash between parties at each payment date.
6.	Trade Termination: A trade may be expired at maturity or terminated early. The early termination  could be caused by a position sell or triggered by an early termination provision, such as auto call/cancel, knock-out, etc.

1.	Trade Capture
First of all, a user needs to download and install FinPricing application. After registering an account and logging in, the user should create a least one book to hold trades. You can find the instruction of managing books at http://www.finpricing.com/faq/manageBook.html. A book is a collection of financial assets. It could be a portfolio or trading strategy or desk. FinPricing portfolio management supports multi-level book(portfolio) hierarchies.
FinPricing provides two interfaces for users to capture trades:
•	Book a single trade
•	Book multiple batch trades

1.1.	How to book a single trade in FinPricing?

•	Click the Trade tab at the top-left corner of the application. Then, expend Product -> FixedIncomeProduct. Next, select the Bond. Here we are using Bond as an example.

 
•	A selection window pops up, allowing users to select a book to hold the new trade. Note that trades should be stored in leaf node books only. After a book selected, all bond trades within this book are displayed in the main window
 
•	Users can select an existing trade and then click the Load button to extract the trade details for modification, validation, and what-if analysis. But this section is mainly focused on creating a new trade.

•	Next, click the New button. A bond definition template is displayed in the main window. Fill the template and click the Save button.
 
•	If you input all the data in correct format, especially the dates, you will see the OK window pops up. That means the new trade has been created in the system.
 

1.2.	How to load multiple bulk trades into FinPricing?

•	Click the Tool tab at the top-left corner of the application. Next, expend Product -> InterestRateProduct. Then, select the Interest Rate Swap.
 


•	Next, click the Load button. A window pops up allowing users to browse the local folders and select files.

•	After selecting a bulk trade file that is in csv format, click the Open button.
 
 

1.	FinPricing starts to load all the trades defined in the file. Finally a summary table is displayed in the main window telling you how many trades are successfully loaded and how many of them fail.
 




Trade life cycle has different stages, by which a trade flows through. These detail steps are from the point of order, receipt, execution and settlement of trades in a systematic manner. In other words, it is regarded as a series of logical steps which are represented in such a manner where the trade is allowed to go through keeping track of its related objective and importance.

You can find more details at
https://finpricing.com/lib/IrCurveIntroduction.html


