# Rossmann-Sales-Project

* Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

* You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.

![image](https://user-images.githubusercontent.com/74107667/207579277-df671418-e62a-42e2-94b9-e9e836ff8a11.png)

* **Dirk Rossmann** GmbH, commonly referred to as Rossmann, is one of the largest drug store chains in Europe with around **56,200 employees** and more than 4000** stores**. In 2019 Rossmann had more than €10 billion turnover in Germany, Poland, Hungary, the Czech Republic, Turkey, Albania, Kosovo and Spain.
The company was founded in **1972** by Dirk Rossmann with its headquarters in Burgwedel near Hanover in Germany. The Rossmann family owns 60% of the company. The Hong Kong-based A.S. Watson Group owns 40%, which was taken over from the Dutch Kruidvat in 2004.


* The product range includes up to **21,700 items** and can vary depending on the size of the shop and the location. In addition to drugstore goods with a focus on skin, hair, body, baby and health, Rossmann also offers promotional items ("World of Ideas"), pet food, a photo service and a wide range of natural foods and wines. There is also a **perfume range with around 200 commercial brands**. Rossmann has **29 private brands with 4600 products (as of 2019)**. In 1997, the first own brands Babydream, Facelle, Sunozon and Winston were introduced. The best-known Rossmann brands are Isana (skin, hair and body care), Alterra (natural cosmetics), domol (cleaning and laundry detergents) alouette (paper tissues etc).

# <b> Data Description </b>

*  <b>Id</b> - an Id that represents a (Store, Date) duple within the test set
*  <b>Store</b> - a unique Id for each store
*  <b>Sales</b> - the turnover for any given day (this is what you are predicting)
*  <b>Customers</b> - the number of customers on a given day
*  <b>Open</b> - an indicator for whether the store was open: 0 = closed, 1 = open
*  <b>StateHoliday</b> - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None
*  <b>SchoolHoliday</b> - indicates if the (Store, Date) was affected by the closure of public schools
*  <b>StoreType</b> - differentiates between 4 different store models: a, b, c, d
*  <b>Assortment</b> - describes an assortment level: a = basic, b = extra, c = extended
*  <b>CompetitionDistance</b> - distance in meters to the nearest competitor store
*  <b>CompetitionOpenSince[Month/Year]</b> - gives the approximate year and month of the time the nearest competitor was opened
*  <b>Promo</b> - indicates whether a store is running a promo on that day
*  <b>Promo2</b> - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating
*  <b>Promo2Since[Year/Week]</b> - describes the year and calendar week when the store started participating in Promo2
*  <b>PromoInterval</b> - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store

Dataset Link :- https://drive.google.com/drive/folders/1g1bLN8th-QVDIKW-XIKRp3ifCbjZKmYy?usp=share_link
