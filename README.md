# milestone-1
Topic:-Food Delivery Backend with Order Management

The Food Delivery Backend provides APIs for managing restaurant menus, handling orders, and
simulating order status updates, helping build the foundation for a food delivery service.

Features
1. Add menu items with details like name, price, and category.
2. Place orders by selecting multiple items from the menu.
3. Track the status of an order, which automatically updates over time.

Add Menu Item (POST /menu): Create or update menu items.

1. **Open Postman and Create a New Request**: Click on "New" > "Request", give it a name, and save it in a collection.
2. **Set the HTTP Method to POST**: In the dropdown next to the URL bar, select **"POST"**.
3. **Enter the URL**: Type the API endpoint URL in the field (e.g., `http://localhost:3000/menu`).
4. **Add Data to the Body**: Go to the "Body" tab, select the appropriate format (e.g., **"Raw"** for JSON), and enter your data (e.g., JSON object).
5. **Click "Send"**: After setting up the request, click **"Send"** and check the response in the lower section of the Postman window.


Get Menu (GET /menu): Retrieve menu items.
1. **Open Postman and Create a New Request**: Click on "New" > "Request", give it a name, and save it in a collection.
2. **Set the HTTP Method to GET**: In the dropdown next to the URL bar, select **"GET"**.
3. **Enter the URL**: Type the API endpoint URL in the field (e.g., `http://localhost:3000/menu`).
4. **(Optional) Add Parameters**: If the GET request requires query parameters, click on the "Params" tab and add key-value pairs.
5. **Click "Send"**: After setting up the request, click **"Send"** and check the response in the lower section of the Postman window.

Place Order (POST /orders): Create an order with selected menu items
1.Open Postman: Click on "New" > "Request" and give it a name.
2.Set Method to POST: Choose "POST" from the dropdown next to the URL.
3.Enter the API URL: Type the URL for placing the order (e.g., https://api.example.com/orders).
4.Add Order Details: In the "Body" tab, select "Raw" and "JSON", then enter the order details (e.g., menu items and quantity).
5.Click "Send": Hit the "Send" button to place the order and check the response.

Get Order (GET /orders/:id): Fetch details of a specific order.
1.Open Postman: Click on "New" > "Request" and give it a name.
2.Set Method to GET: Choose "GET" from the dropdown next to the URL.
3.Enter the API URL: Type the URL for fetching the order (e.g., https://api.example.com/orders/123), replacing 123 with the specific order ID.
4.(Optional) Add Authorization: If needed, go to the "Authorization" tab to add an API key or token.
5.Click "Send": Hit the "Send" button to fetch the order details and check the response.
