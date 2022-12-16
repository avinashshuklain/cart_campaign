# cart_campaign
1: Combo campaigns
For the combo campaign to work, the customer must combine a minimum of two products to get the campaign price. A combo campaign contains a list of products that the customer can combine, here is an example:

EAN                         Price
5000112637922               30 SEK
5000112637939               30 SEK
7310865004703               30 SEK
7340005404261               30 SEK
7310532109090               30 SEK
7611612222105               30 SEK

Here are some combination examples a customer can make, a product can be combined with itself.

    • 5000112637922 + 7310865004703 = 30 SEK
    • 7340005404261 + 7310532109090 + 5000112637922 + 7310865004703 = 60 SEK

Note: If the customer adds three products to their basket and all of them are in a campaign, the customer only pays the campaign price for two of them and will pay original price for the third product.


2: Volume campaigns
The volume campaigns are based on number of items the customer needs to add to their basket to trigger the campaign price. For example, you can setup a campaign for Coca-Cola and the customer needs to buy two to get the campaign price.

EAN             Price               Minimum purchase quantity
8711000530085   85                  2
7310865004703   20                  2

Note: If the customer adds a third item to the basket, the customer needs to pay regular price for the third item and campaign price for the rest.

3: How to run
Download the source code from https://github.com/shuklaavinash/cart_campaign and run in any browser, as there is no database connection so no need to setup any configuration. Bydefault index.html page showing "Combo Campign" and index_volumn.html page is showing "Volumn Campign".