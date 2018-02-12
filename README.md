# BossNow3

Arpit Saxena completed his B-tech in Computer Science & Engineering in 2016 from JECRC
University, Jaipur, India. He is a Microsoft Student partner where he developed 4 azure
enabled UWP apps, one of them having Machine Learning capability. He worked as an intern
in figaro softwares, an oracle partner company in Warszawa, Poland for 3 months on position
of software quality analyst. He worked as Data Analyst at a startup zillion.io, where he was
handling data of Nike company. He also worked for TCS for 6 months before coming to University of Texas at Arlington
for MS in Computer Science.



 Why this app exists ?
This app will allow users to act as buyers and sellers in required times. Through the app, the
seller will post the pictures and give a brief description of the product to be sold. The sellers
will be able to raise a quotation base price upon which buyers will raise it to their affordable
amounts of bids. Through this, the seller will be ensured of the best price for their product and
the buyers will get their desired product at their affordable limit prices based on demand of
that particular product at the time. After the bidding, once the product is sold, the product is
marked as sold in the app. Overall, this app will ensure smooth, profitable and fair transfer of
a product from a seller to a buyer.
PURPOSE AND NEED
 What the App will do ?
This app will provide the buyers, a facility to bid on the specific products that they are
interested to purchase. The buyers can also chat with the sellers for queries about the product.
The seller will post the pictures and give a brief description of the product to be sold. Also, the
sellers will be able to raise a quotation base price upon which buyers will raise it to their
affordable amounts of bids. Sellers will also be able to choose whom their product will be sold
to. After the bidding, once the product is sold, the product is marked as sold in the app. This
app will allow a person to act as a seller at one time and a buyer at another time.
BUSINESS DRIVERS AND THEIR SIGNIFICANCE
 Who will use it - what users are expected and roles will they have ?
The app is being designed keeping in mind the trend and economics of sales, purchases,
bargaining and profitability via current models of marketing by general public. This app will
be used by both sellers who want to receive the highest price for their products and buyers who
want to purchase either a normal product or a product in high demand which is in limited
quantity.
BENEFITS AND COSTS
 Is this a mobile version of an existing function?
This is a new function which we are trying to implement. There are many online or mobile
sales apps like Amazon, Walmart etc. but there never was a dynamic 2-way open bidding
process where the buyer as well as the seller were in full control of the price of the desired
product and where there was dynamic pricing i.e. Price of a product increases with increase in
its demand.
 What other resources will be utilized?
To provide personalized experience to every user, we will be using GPS to look up the current
location of the user with the permission of the user so that the delivery or shipping costs may
be premeditated. There will also be an option to provide the zip code by the user so that location
based preferential searching and sorting can take place. Also, to store the user profile
information, their preferences, ratings, etc. we will create a separate database for it. The login
process will be taken care of by the Facebook or Google+ login process. The users can view
their ordered or sold products in the Shopping Cart.
IMPLEMENTATION METHOD
We will implement this app using Android Studio and will present it on our own Smartphones.
We will bundle it into a single APK file during final submission

FUNCTIONS OF THE APP
1) A system admin function that sets up the database
There will be a system admin who will function to set up the database.
2) sign-in credentialing and forgot password feature
The app will have a sign-in credentialing either through Gmail, Facebook or phone number. Also,
there will be a forgot password feature to retrieve any lost or forgotten password via the registered
phone number or email address in the account.
3) Admin Monitoring
The admin will frequently and periodically monitor posts, offerings for bids and blocks products
and users if needed.
4) Post an advertisement for a product by seller.
The seller will be able to post the advertisement regarding his product on this app so that it can be
viewed by many people who are interested in the similar category of products.
5) Search, Sort, Select and place a bid on the product by Buyer.
The buyer will be able to browse through the list of products in the similar category of items. The
buyer will be able to search and sort for products via a number of filters like price, size, dimensions,
weight, etc. This gives the buyer the exact personalized product that he wishes to purchase. Then,
he/ she will select any particular product and will place a bid higher than the base quotation price
fixed by the buyer.
6) Interaction of Buyer and seller through a personal Chat box.
The buyer will be able to interact directly with the seller via a personal chat box through which the
buyer can clarify his queries with the seller, negotiate regarding price and ask about delivery
charges and process.
7) 2-Way Rating system.
In this app, unlike most other apps, the sellers can rate buyers and vice versa too. This enables fair
bidding and removes any kind of unwanted spamming of the system by fake ids and false upbidding.
8) Track the product
The Buyer has the ability to track his ordered product. After buying the product, the buyer will
receive a Tracking ID. When he will enter that Tracking ID in the Tracking page, the status of
shipping of the product will be displayed. This completes the transparency in the entire process.
High-Level Use Cases
UC 1: Monitor Posts.
- TUCBW the admin clicks on the posts of users.
- TUCEW the admin monitors the posts page.
UC 2: Set up Database.
- TUCBW the admin clicks on set up database.
- TUCEW admin clicks the ‘confirm’ button on the confirmation dialog.
UC 3: Block Users
- TUCBW the admin clicks on buyer/ seller ID with reports more than 10.
- TUCEW the admin clicks on ‘Block Users’.
UC 4: Back up Database
- TUCBW the admin clicks on backup database.
- TUCEW the admin backing up the database.
UC 5: Search for Products
- TUCBW the buyer clicks on search textbox and enters product to be searched.
- TUCEW the buyer sees the searched product.
UC 6: Sort for Products using Filters
- TUCBW the buyer clicks on the ‘Filter’ button.
- TUCEW the buyer sees the sorted products.
UC 7: Interactive Chat with Seller/ Buyer
- TUCBW the buyer/ seller clicks on the ‘Chat’ button.
- TUCEW the buyer/ seller views the chat screen.
UC 8: Rate the Seller/ buyer
- TUCBW the buyer/ seller clicks on product he has purchased/ sold.
- TUCEW the buyer/ seller rating the seller/ buyer.
UC 9: Post an Ad
- TUCBW the seller clicks on ‘Post an Ad’.
- TUCEW the seller clicks on ‘Ok’ and posts the ad.
UC 10: Login
- TUCBW the user clicks on ‘Login’.
- TUCEW the user sees Welcome page.
UC 11: Logout
- TUCBW the user clicks on ‘Logout’.
- TUCEW the user sees the Homepage.
UC 12: Reset forgotten Password
- TUCBW the user clicks on ‘Reset Password’.
- TUCEW the user resets Password.
UC 13: Bid on Products
- TUCBW the buyer increments/ decrements the price.
- TUCEW the buyer sees the bid on Product.
UC 14: Track the ordered Products
- TUCBW the buyer clicks on ‘Tracking ID’.
- TUCEW the buyer sees the Tracking details.
Use Case Diagram
Requirements Use-Case Traceability Matrix
Priority
Weight
UC
1
UC
2
UC
3
UC
4
UC
5
UC
6
UC
7
UC
8
UC
9
UC
10
UC
11
UC
12
UC
13
UC
14
R1 4 X
R2 3 X
R3 3 X
R4 2 X
R5 3 X
R6 4 X
R7 2 X
R8 2 X
R9 4 X
R10 2 X
R11 2 X
R12 3 X
R13 1 X
R14 3 X
Score 2 4 3 3 2 2 2 2 4 3 3 3 4 1
Use Case List
Use Case
UC 1 Monitor Posts.
UC 2 Set up Database.
UC 3 Block Users
UC 4 Back up Database
UC 5 Search for Products
UC 6 Sort for Products using Filter
UC 7 Interactive Chat with Seller/ Buyer
UC 8 Rate the Seller/ Buyer
UC 9 Post an Ad
UC 10 Login
UC 11 Logout
UC 12 Reset forgotten Password
UC 13 Bid on Products
UC 14 Track the ordered products
Increment Matrix
Use
Case
Priority Effort Depends
on
Iteration 1
due date
10/06/2017
Iteration 2
due date
11/01/2017
Iteration 3
due date
11/29/2017
UC 1 4 1 None 1 - -
UC 2 3 1 None 1 - -
UC 3 3 0.5 UC 1 0.5 - -
UC 4 3 1 None 1 - -
UC 5 2 1 None - 1 -
UC 6 2 1 UC 5 - 1 -
UC 7 2 1 None - 1 -
UC 8 1 0.5 UC 7 - 0.5 -
UC 9 3 1 None - - 1
UC 10 2 1 None - - 1
UC 11 3 0.5 UC 10 - - 0.5
UC 12 4 0.5 None - - 0.5
UC 13 4 1 None - - 1
UC 14 1 1 None - - 1
UC 15 3 1 None - - 1
Total
Effort
13 3.5 3.5 6
Domain Diagram
EXPANDED USE CASES
UC1: MONITOR POSTS
Actor: Admin System: App
0. App displays the admin Homepage.
1. TUCBW Admin clicks on POSTS. *2. App displays the POSTS page with buyer and
Seller ID and number of reports for them.
3. TUCEW admin monitors the POSTS page
UC2: SET UP DATABASE
Actor: Admin System: App
0. App displays the Admin Homepage.
1. TUCBW admin clicks on Set up database. 2. App displays set up database page.
3. TUCEW admin clicks the confirm button on the
confirmation dialog.
UC3: BLOCK USERS
Pre-Condition: Admin clicks on POSTS page.
Actor: Admin System: App
0. System displays POST page.
1. TUCBW admin clicks on the Buyer/ Seller ID with
reports more than 10.
*2. System displays the profile page.
3. TUCEW admin clicks on Block user.
Post-Condition: User is blocked.
UC4: BACK UP DATABASE
Pre-Condition: Admin sets up the Database.
Actor: Admin System: App
0. System displays Admin Homepage.
1. TUCBW admin clicks on backup database. 2. System displays a confirmation dialog box.
3. Admin clicks on OK button. 4. System displays confirmation message.
5. TUCEW admin backing up the database.
Post-Condition: Database is backed up.
See Figure 6
UC5: SEARCH FOR PRODUCTS
Actor: Buyer System: App
0. The app displays the main page.
1. TCUBW buyer clicks on Search text box and enters
product to be searched.
*2. App displays the list of products.
3. TUCEW buyer sees the searched products.
UC6: SORT FOR PRODUCTS USING FILTER
Pre-Condition: Buyer searches for products.
Actor: Buyer System: App
0. App displays the searched products page.
1. TUCBW Buyer clicks on filter button. *2. App displays available filters for that
product.
3. Buyer clicks on the desired filter. 4. App displays the product after sorting.
5. TUCEW the buyer sees the sorted products.
Post-Condition: Sorted Products are displayed.
See Figure 7
UC7: INTERACTIVE CHAT WITH SELLER/ BUYER
Pre-Condition: Buyer selects a Product to Buy.
Actor: Buyer/ Seller System: App
0. App displays buyer’s/ seller’s profile page.
1. TUCBW buyer/ Seller clicks on Chat button. 2. App displays Chat Screen.
3. TUCEW buyer/ Seller views Chat screen.
Post-Condition: Buyer/ Seller sends message to Seller/ Buyer.
UC8: RATE THE SELLER/ BUYER
Pre-Condition: Buyer/ Seller has to purchase/ Sell the product.
Actor: Buyer/ Seller System: App
0. App displays buyer’s/ Seller’s cart page.
1. TUCBW buyer/ Seller clicks on product he has
purchased/ Sold to rate the seller/ Buyer.
2. App displays the purchased/ Sold product
with the seller/ Buyer details.
3. The buyer/ Seller clicks Rating. 4. App displays rating dialog box.
5. TUCEW buyer/ Seller rating the seller/ buyer.
Post-Condition: The Buyer/ Seller rates.
See Figure 10
UC9: POST AN AD
Actor: Seller System: App
0. App displays Post Ad page.
1. TUCBW seller clicks on Post an Ad. 2. App displays new ad page.
3. TUCCW seller entering the product details. 4. App displays confirmation dialog box.
5. TUCEW seller clicks OK and posts an ad.
See Figure 1
UC10: LOGIN
Actor: User System: App
0. App displays the homepage.
1. TUCBW User clicks on Login. 2. App displays Login page.
3. User enters Username and Password. 4. App displays Welcome page.
5. TUCEW user sees Welcome page.
See Figure 2
UC11: LOGOUT
Actor: User System: App
0. App displays any screen.
1. TUCBW user clicks on Logout. 2. App displays Confirmation dialog box.
3. User clicks on OK. 4. App displays Homepage.
5. TUCEW user sees the Homepage.
See Figure 8
UC12: RESET FORGOTTEN PASSWORD
Actor: User System: App
0. App displays Login Page.
1. TUCBW user clicks on reset Password. 2. App displays reset Password main page.
3. User enters Email ID. 4. App displays message to check email.
5. User clicks on the reset link in email. 6. System displays reset Password Page.
7. TUCEW user resets Password.
See Figure 9
UC13: BID ON PRODUCTS
Pre-Condition: Buyer selects product to be Purchased.
Actor: Buyer System: App
0. App displays Product page.
1. TUCBW buyer increments/ decrements the price. 2. App displays price by the bidder.
3. TUCEW buyer sees the bid on the product.
Post-Condition: The Buyer successfully places the Bid.
See Figure 11
UC14: TRACK THE ORDERED PRODUCTS
Pre-Condition: The Buyer has to purchase the product.
Actor: Buyer System: App
0. App displays Buyer cart page.
1. TUCBW buyer clicks on the tracking ID. *2. App displays the Tracking ID page.
3. TUCEW buyer sees the Tracking details.
Post-Condition: The Buyer shall be able to Track order.
UI PROTOTYPES
Figure 1: Login Figure 2: Logout
Figure 3: Home-screen Figure 4: App Welcome Page Logo
Figure 5: Navigation Figure 6: View Posts
Figure 7: Chat Figure 8: Forgot Password
Figure 9: Bidding Figure 10: Post an Ad
Figure 11: Tracking
SEQUENCE DIAGRAMS
DESIGN CLASS DIAGRAM
CHANGES MADE FROM ITERATION 2 TO ITERATION 3
1) In the Functional Requirements of the app, the stats has been removed as we
display the stats in the firebase and not in the app.
2) In the Functions of the app, Track the product has been added.
3) In the Functional Requirements, we have changed R7, R8, R11 and R12.
4) In the High-Level Use Case and Expanded Use Case, we have combined the rating
and chat of buyer and seller.
5) We have changed the Use Case diagram according to the use cases.
6) The Traceability Matrix has also been changed since the number of Functional
Requirements and the Use Cases has been changed.
7) For the Domain Diagram, we have included the Multiplicity and Relationships.
8) Sequence Diagram has been modified according to the Use Case Diagram.
COMMENTS AND THEIR CORRESPONDING RE-WORKS
Have you revisited the earlier diagrams to update them with any new knowledge you have about
modeling and the App? Did not see any updates.
Yes, We have revised all the earlier diagrams and mentioned the changes in the Iteration 3
Have 2 UC15? HL UCs -- Many TUCBW and TUCEW are poorly constructed, ambiguous. Not
following the principles of the TUCBW and TUCEW. Further, it looks as if the EUCs are different
than the HLUC. The team should go back and update the HLUC so that they are compatible with
the EUCs.
The above-mentioned changes have been done accordingly. The HLUC has been changed
according to the EUCs.
UCD -- Admin doesn’t have a login? Rating should be one UC instead of two, same goes for
chatting. UCD name missing system name for each of the diagrams.
Yes, we are showing the admin functionalities through Firebase. Rating and chatting of buyer and
seller has been included in the same step.
We already had the system names for all the UCD.
RUCTM -- A requirement should not be covered by multiple UCs. If it is, the requirement should
be reallocated. And missing coverage of UC 16.
The above mentioned has been corrected.
(UC list may have been a pdf conversion problem?)
Yes, Change has been made now.
DMD -- Missing many relationships, multiplicities. what is seller cart?
We have done the changes and mentioned them in Iteration 3 now.
Seller Cart is the new class which we have added in Iteration 2
Incremental Matrix -- Missing unit of ‘person week’. And efforts do not appear to be estimated
consistently. The whole app can be implemented in 3 weeks? What is the unit of effort the team is
using?
EUC -- Many missing pre- and post-conditions. Included pre- and post-conditions do not seem
correctly (unambiguously) defined. Many expanded contents are incorrect. For example, EUC2;
no pre- or post-conditions; Are there more steps after step 2 here and before step 3? And TUCBW
and TUCEW are different from the HLUC2 and they should be the same. The non-trivial steps
should be identified in the EUCs – SDs should address these EUCs with non-trivial steps. The
UIPs should be referenced to the EUC steps (e.g., “see figure 1”) and they are not; at least 1 per
EUC, preferably 2.
For the Pre and Post conditions, the changes have been made. EUC2 has also been modified.
The TUCBW and TUCEW in HLUC has been changed accordingly.
We have identified all the non- trivial steps and did the SD accordingly.
The figure numbers have been referenced to the EUC.
UIPs – look good, but not referenced to EUCs; no figure numbers or figure titles provided. Some
of the UIP diagrams seem incomplete – could use some annotations to identify key points of the
UIPs, especially for the steps they are used to reference in the EUCs.
The above-mentioned changes have been made
SDs -- Missing some SDs for EUCs. The increment matrix says the team should have EUCs 1
through 8 complete and working on 9 through 16 -- missing SDs for UC 2, 4, 7, 9, 10, 12, 13, and
14.
DCD – use smaller arrowheads on the relations (just a point of notation). Overlapping relations
lines on the drawing make it tough to follow the relations and identify the relation types at times;
maybe an alternative layout of classes would help . . . .
Yes, we have modified our DCD according to the above comment
