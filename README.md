# DeliveryApp
We're creating our delivery application.

# Food Recommendation System

We’re attempting to create a personalized food recommendation system that leverages recommendations based not only on popular choices within the individual’s area but certain characteristics that are more appealing to them as well. This goes beyond simply accounting for preference of cuisine or high-rated restaurants as it considers the features of restaurants they’ve already visited in the past to come up with more accurate recommendations. Ultimately, we’re trying to improve the quality of the recommendations offered, so that it doesn’t take too long for people to find a restaurant worth their time.

This recommendation system is available as mobile application as well as a web extension.

# Timeline:
March - April 2024:
* Use React.js for front-end & Django for back-end
Selecting Food/Restaurants from drop-down menu (Connect to Google to get the list of restaurants that exist in Singapore)
Determine their location either from Google’s location services if it’s turned on or ask them to enter their pincode.
Complete the entire front-end and make sure the UI is clean and user-friendly.
Login/SignUp Page - User Credentials
Option to choose Food / Restaurants
Main Page - Search Bar for Food/Restaurants
Restaurants
Create a display for all of those restaurants, ordered by proximity from closest to furthest, and ask the user to select the specific location they would like to order from.
Work on creating display cards/templates for each restaurant with all the necessary information (location, distance, opening and closing times, ratings, etc.)
Connect to the different delivery services for that restaurant (Grab, Deliveroo, Foodpanda, and more) and find the one with the cheapest delivery fee/existing deals.
Create an elegant display for these deals that represents their attractiveness and ranks them from best to worst offer.
Food
Create a display for the food items they have ordered using the display cards
Work on creating display cards/templates for each food item with all the necessary information (cuisine, ratings, etc.)
After food selection, list all the food items sorted by price suggested by our recommendation system from various platforms (Grab, FoodPanda, Deliveroo, and more)
Once the user clicks on the offer that they want to use, redirect them to that application immediately.
The selected item gets added to the cart 


# April - May 2024:



# May - June 2024:



# Project End - June 2024




# Features to Add:
GAI chatbot specialized in food
Take a general-purpose LLM (perhaps one that’s already been customized for food) and use instruction fine-tuning to guide the model to provide accurate responses to the user’s queries.
We’ll most likely have to generate these instructions and update the model weights for our task.
We can also perform RL with human feedback and get people to rate the quality of the responses that our chatbot provides to guide it in the right direction.
Backend
Links to internal database containing restaurants the user has visited and reviews given
We can either find the restaurants they’ve visited through a pop-up asking them if they went there, or we can use location data provided by Google to see if they visited that restaurant.
We can also recommend based on the restaurant’s aesthetics(type of restaurants they visit) (prefer cost or quality)
Obtain this information from prior reviews on either Google or other review platforms like TripAdvisor, Yelp, etc. (Connect to these APIs)
Have to perform data scraping to obtain the information and then find keywords related to the aesthetics to improve the quality of future recommendations.
Links to connect food delivery apps (Grab, foodpanda,etc):
We can checkout the offers and deals going on and suggest the best among them
This is linked to the database as it suggests based on their reviews and tastes as well(quality or cost)
(Optional) Links to the Youtube videos, if they wanted to cook themself:
Suggest youtube videos if they don't want to eat outside
Way to store log-in information if they choose to sign up with our platform.
Frontend
Simple interface that displays the recommendations we’ve generated to the user in the form of cards or different templates they can interact with.
Restaurant Name
Location (Proximity)
Eat-in or Delivery
Google Rating
Users should be able to filter by rating, price, etc.
Login with Google account option
Pop-up Menu
Info About Us
Visited Restaurants
Ratings/Reviews
Chatbot
Ordered food items





API:
https://www.foodspark.io/api/zomato/ 
