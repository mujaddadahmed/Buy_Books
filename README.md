# BuyBooks

BuyBooks is a full-stack book selling application developed using **ASP.NET Core MVC (.NET 8)**. It provides a platform for customers to browse and buy their favorite books and novels.

**GitHub:** [https://github.com/mujaddadahmed/Buy_Books]

## Core Functionalities and Technologies

1. **User Authentication**
   - Utilizes ASP.NET Core Identity for secure user registration and login.
   - Supports external authentication with Google and Facebook.

2. **Profile Management**
   - Users can update, edit, and remove their information in profiles.
   - Supports email confirmation and password management.

3. **Search Functionality**
   - Built-in search feature using AJAX for asynchronous search results loading.

4. **Cart and Summary Feature**
   - Supports cart management and provides an order summary before proceeding with the order.

5. **Flexible Payment Methods**
   - Customers can pay via card or cash apps.
   - Dummy payment services from the Stripe API are used.

6. **Order Status Listing**
   - Provides a detailed view of all orders and their states, e.g. approved / delivered / processed.

## Additional Enhancements

- **AJAX** — Used for dynamic content loading, improving the user experience.
- **Clean Architecture** — Applied to maintain a clean and manageable codebase.
- **Caching** — Implemented to improve performance and speed up data retrieval.
- **Dockerizing** — Dockerized the application for easier deployment across environments.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript, AJAX, Bootstrap for responsive design.
- **Backend:** ASP.NET Core MVC
- **Database:** Microsoft SQL Server with Entity Framework Core as the ORM.
- **Auth:** ASP.NET Core Identity, Google authentication.
- **Deployment:** Docker for containerization and IIS local server.

## Screenshots

**Figure 1:** The first view of BuyBooks navigates the customer through the products we are offering.
![Figure 1](images/image1.jpeg)

**Figure 2:** Search bar is provided for filtering search results on the basis of the search term.
![Figure 2](images/image2.jpeg)

**Figure 3:** The Register page.
![Figure 3](images/image3.jpeg)

**Figure 4:** Populating all the required fields.
![Figure 4](images/image4.jpeg)

**Figure 5:** Registration successfully done!
![Figure 5](images/image5.jpeg)

**Figure 6:** On clicking "Hello \<username\>".
![Figure 6](images/image6.jpeg)

**Figure 7:** The profile options and information appear.
![Figure 7](images/image7.jpeg)

**Figure 8:** Email editing partial view.
![Figure 8](images/image8.jpeg)

**Figure 9:** Password changing tab.
![Figure 9](images/image9.jpeg)

**Figure 10:** External login tab.
![Figure 10](images/image10.jpeg)

**Figure 11:** Personal data download and account deletion tab.
![Figure 11](images/image11.jpeg)

**Figure 12:** To add a product to cart, click on details.
![Figure 12](images/image12.jpeg)

**Figure 13:** The details view appears.
![Figure 13](images/image13.jpeg)

**Figure 14:** The count can be customized.
![Figure 14](images/image14.jpeg)

**Figure 15:** On clicking "Add to cart", the book is added to the cart.
![Figure 15](images/image15.jpeg)

**Figure 16:** Click on the cart icon in the top-left corner to view the cart.
![Figure 16](images/image16.jpeg)

**Figure 17:** Products in the cart appear.
![Figure 17](images/image17.jpeg)

**Figure 18:** The count can be increased or decreased here, and the product can be removed from the cart.
![Figure 18](images/image18.jpeg)

**Figure 19:** On clicking the summary button, the summary of our order appears.
![Figure 19](images/image19.jpeg)

**Figure 20:** On clicking "Place order" in the order summary, the payment view appears.
![Figure 20](images/image20.jpeg)

**Figure 21:** Provide email and then choose payment option.
![Figure 21](images/image21.jpeg)

**Figure 22:** A dummy QR appears which contains an option to simulate scan.
![Figure 22](images/image22.jpeg)

**Figure 23:** The payment is authorized, as it is a test payment.
![Figure 23](images/image23.jpeg)

**Figure 24:** The order is placed successfully!
![Figure 24](images/image24.jpeg)

**Figure 25:** The order list can be accessed from the "Manage Order" option in the top-left corner of the home page, and it contains the status of all your orders.
![Figure 25](images/image25.jpeg)
