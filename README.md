# Web Parsing

In this quiz, I parse L'Oréal Paris USA site. To be persise, Their skincare product's page:
https://www.lorealparisusa.com/products/skin-care/shop-all-products.aspx?size=21&page=1

Firstly, I create csv file to save parsed information in it.
I use csv module so that saved information is cleaner.

Secondly, I send a request to a site and check whether I get access to it or not.

Afterwards, I use bs4 module to get the desired information from the site, which is
the brand, name and a description of a Product.

Lastly, I use sleep function to delay the requests to the server, because I didn't want to be 
locked out of it. So the request is sent every 15 seconds.
