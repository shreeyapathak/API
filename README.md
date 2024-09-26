# To Design API
1)Create User

POST/users
Body
{
  username:.....,
  email:....,
  password:...,
  name:....
  }

2)get all Users

Get/users

3)get a specific user profile

GET/users/{user ID}

4)update user profile

PATCH/users
{
name:.....,
Phone no.:....,
email:.....,
}

5)get all products

GET/products

6)get a specific product

GET/products/{product ID}

7)add product in a cart

POST/products

8)remove product from cart

DELETE/products/{product ID}

9)create an order

POST/orders
Body
{
name:.....,
phone no.:....,
Items name:.....,
quantity:.....,
Amount:......,
}


10)cancel an order

DELETE/orders/{order ID}
