<h1>Kunyo Test Solution </h1>
<p>
    For the required solution, we can use this system made in Laravel(kunyo_test.zip). <br>
    So, please install this system in your local <br>
    The database is also attached(kunyo_test.sql). <br>
    This system allows users to place order, get reward and use reward to place more order. <br>
    The UML diagram and schema can be found within the system.
</p>


<h3>The more detailed instructions and explanation is available on the Home page of the system along with links to different page.</h3>

<h3>How to use the system:</h3>

- To credit the reward points after order completion, we can use this system. <br>
- Customer have to place order first. <br>
- Once order is placed, it is listed in the Order List page. <br>
- The order status can be changed by clicking the Status link <br>
- When the status is changed to Completed, the user gets the reward points. <br>
- The reward points is converted as per the requirement so that it can be easily redeemed later. <br>
- The customer can redeem the reward points while placing order.
- The system supports multi-currency as well, but conversion value is hardcoded for now.
- USD is the default currency and the data is always saved in USD. The conversion takes place for display only.
- The currency can be changed by clicking on the top dropdown which appears in Product, Order Placement and Order Listing page.
- The code and funtions can be found in following files:
  - Routes: routes/web.php
  - Functions: app/Http/Controllers/ProductController.php
  - Theme files are inside the folder: resources/views/Products

<strong>Note: Currently this system is for single user only and no login is required for now. <br></strong>
