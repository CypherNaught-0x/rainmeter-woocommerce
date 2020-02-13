# WooCommerce integration for [Rainmeter](https://www.rainmeter.net/)
I've created this simple skin for Rainmeter to show the sales report of a WooCommerce Shop since I couldn't find anything like it online and thought this might help someone get started. And mostly because I think it's pretty cool.

![Screenshot](https://user-images.githubusercontent.com/9931495/74457590-c3758880-4e88-11ea-9cb5-82c9a01e466c.png)
*Other skin used: [Mond by hiphopium](https://www.deviantart.com/hiphopium/art/Mond-762455575)*

# Setup
1. git clone or download release and copy to your **Skins** folder.
2. Sign in to your WooCommerce Dashboard
3. Go to **WooCommerce->Settings->Advanced->Rest-API**
4. Click on **create key**
5. Give it a name like rainmeter and make it read-only
6. Copy your key and secret to the **Variables.inc** replacing **woocommerce_api_key** and **woocommerce_api_secret** respectively
7. In Variables.inc also give your shop a name and add the base URL without a / at the end.
8. Load the skin and customize to your hearts content.