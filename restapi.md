// Page 1
    > List of City.
        > GET -  http://localhost:17001/location
        https://febzomatoapi.herokuapp.com/location
    > List of Restaurant.
        > GET -  http://localhost:17001/restaurant
        https://febzomatoapi.herokuapp.com/restaurant
    > Restaurant on the basis of city.
        > GET -  http://localhost:17001/restaurant?stateId=2
        https://febzomatoapi.herokuapp.com/restaurant?stateId=2
    > List of QuickSearch.
        > GET -  http://localhost:17001/mealType
        https://febzomatoapi.herokuapp.com/mealType

// Page 2
    > List of Restaurant on the basis of Meal.
        > GET -  http://localhost:17001/restaurant?stateId=2&mealId=3
        https://febzomatoapi.herokuapp.com/restaurant?stateId=2&mealId=3
                 http://localhost:17001/restaurant?stateId=2
                 https://febzomatoapi.herokuapp.com/restaurant?stateId=2
    > Filter on the basis of cuisine.
        > GET - http://localhost:17001/filter/4?cuisineId=2
        https://febzomatoapi.herokuapp.com/filter/4?cuisineId=2
    > Filter on the basis of cost.
        > GET -  http://localhost:17001/filter/4?lcost=700&hcost=1500
        https://febzomatoapi.herokuapp.com/filter/4?lcost=700&hcost=1500
    > Sort on the basis of cost.
        > GET -  http://localhost:17001/filter/4?lcost=500&hcost=1500&sort=-1
        https://febzomatoapi.herokuapp.com/filter/4?lcost=500&hcost=1500&sort=-1

// Page 3
    > Detail of Restaurant.
        > GET -  
        // On the basis of object id - http://localhost:17001/details/629dfcb646b97e59fe9de493

        // On the basis of Normal id - http://localhost:17001/details/3
        https://febzomatoapi.herokuapp.com/details/3

    > Menu of the restaurant.
        > GET -  http://localhost:17001/menu/5
        https://febzomatoapi.herokuapp.com/menu/5
    
// Page 4
    > Menu details (selected item)
        > POST - http://localhost:17001/menuItem
    > Place Order.
         > POST -  http://localhost:17001/placeOrder

    
// Page 5
    > List of Order placed.
        > GET - http://localhost:17001/orders
    > List of order placed of particular user.
        > GET - http://localhost:17001/orders?email=ahmad@gmail.com
        https://febzomatoapi.herokuapp.com/orders?email=ahmad@gmail.com

        
                     
    > Update order status
        > PUT -  http://localhost:17001/updateOrder/2


// Extra 
    > Delete Order.
        > DELETE -  http://localhost:17001/deleteOrder/62d93688ab87afd3a75a5a93


/// User Register
 > https://authapizomato.herokuapp.com/api/auth/register

