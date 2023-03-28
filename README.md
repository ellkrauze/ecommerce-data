# E-Commerce Data Crawling
<img src="https://itmo.ru/file/pages/213/logo_na_plashke_russkiy_belyy.png" width="400px">

## The Purpose of Project
1. **Data gathering** –– implementation of a data collection system from the selected sources using web-technologies with the possibility of automatic updates.
    Collect raw e-commerce data from popular marketplaces.
2. Selection and implementation of **Big Data** (Hadoop, Spark, Storm).
3. **Processing and Analysis** of the collected and stored data.

## Progress
The dataset should contain these features:
- [ ] `unique_id` –– the unique ID of the product
- [X] `seller_name` –– the name of the seller
- [ ] `brand` –– the brand name of the product
- [X] `title` –– the name of the product
- [X] `url` –– the url of the product
- [X] `review_count` –– the number of reviews
- [X] `current_price` –– the selling price
- [ ] `old_price` –– the selling price before discount
- [ ] `country` –– the original country of the product
- [ ] `item_gender` –– the gender
- [X] `category_0` –– the main category of the product
- [X] `category_1` –– the level 1 category
- [X] `category_2` –– the level 2 category

**Example of sub-categories**:
```
https://www.wildberries.ru/catalog/zhenshchinam/
|– odezhda
    |– bluzki-i-rubashki
    |– odezhda-dlya-doma
    |– bele
    |– bolshie-razmery
    |– bryuki-i-shorty
        |- shorty
    |– verhnyaya-odezhda
    |– dzhempery-i-kardigany
    |– dzhinsy-dzhegginsy
    |– kombinezony-polukombinezony
    |– kostyumy
    |– longslivy
    |– pidzhaki-i-zhakety
    |– platya
    |– tolstovki
    |– tuniki
    |– futbolki-i-topy
    |– yubki
|– odezhda-dlya-doma
    |– halaty
|– budushchie-mamy
|– dlya-vysokih
|– dlya-nevysokih
|– ofis
|– plyazhnaya-moda
|– religioznaya
|– svadba
|– spetsodezhda
|– podarki
    |- zhenshchinam
```
