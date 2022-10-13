# Big Basket :
* [Live](https://big-basket-re.vercel.app)
* Big Basket is a E-Commerce web app where user can create account and place orders.

# Test :
* email : abhi@email.com
* password : 123456

# Demo : 
* Home : User can explore the items in the home page

![Imgur](https://i.imgur.com/1vodkwE.png)

* Register : User can view items and can add items to the cart but cannot place order if not logged in. If user don't have an account user can create by clicking Login and then Register link in the Login Page. On successfully registering user will be logged in automatically.
 
![Imgur](https://i.imgur.com/C4KD6CJ.png)

* Login : User can give credentials(email and password) and log in. 
![Imgur](https://i.imgur.com/ibll3rR.png)

* Add Items: User can add items to the cart from the home page or product page. If the user add item more than the stock left from home page it show error 

![Imgur](https://i.imgur.com/4QYLcAQ.png)

![Imgur](https://i.imgur.com/rakh9tF.png)

* Cart : User can change quantity(limited) of the items and can remove item if user added the same item 5 times from home page it will show as item1 = 5qty.

![Imgur](https://i.imgur.com/7yY39qw.png)

![Imgur](https://i.imgur.com/azLEfNr.png)

* Shipping Address : User need to give the address.

![Imgur](https://i.imgur.com/C4KD6CJ.png)

* Payment Method : *Currently RazorPay is not implemented* Select the Cash on Delivery.

![Imgur](https://i.imgur.com/AlcKk06.png)

* Place Order : Place the Order.

![Imgur](https://i.imgur.com/0gjDmco.png)

* Order : Check the order status.

![Imgur](https://i.imgur.com/Y7t1QnR.png)

* Order History : User can check their order history and check their current status. To access Order History click on your username a dropdown will appear click on Order History from their.

![Imgur](https://i.imgur.com/zVvqYXS.png)

![Imgur](https://i.imgur.com/vQIE91o.png)

* Logout : User can logout using Logout button.

![Imgur](https://i.imgur.com/zVvqYXS.png)


# Tech :
* NEXTJS : React framework for the frontend.
* NEXT-AUTH :
* MONGODB : 
* UseContext and UseReducer Hooks : State Manangement.
* React-Hook-Form : 
* Axios
* bcryptjs
* js-cookie
* mongoose
* react-toastify
* TAILWIND-CSS : CSS framework for styling and creating UI components.
* HEADLESSUI : Completely unstyled, fully accessible UI components, designed to integrate with Tailwind CSS.
* REACT_ICONS : Includes popular icons.

# To run on Local Machine :
* Download/clone the repository
* open the folder on the VS-Code or any code-editor or IDE.
* Open the Termimal ```cd``` into the folder:
* Run the command in the Terminal :
```
   npm i
   // or 
   yarn 
```
* To Start the Next Web App run the command in the terminal :
```
  npm run dev 
  // or
  yarn dev
```
