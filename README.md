Project Proposal


Title:
The goal of this project is to analyze the Airbnb listings of London and help future users estimate what the correct price of their rental should be given the set of features. The tool will also give simple suggestions to the user to help them get the max rental price while not losing out on the occupancy

Dataset:
Data has been scraped from Airbnb by http://insideairbnb.com/get-the-data.html
It contains 77000+ records and has 97 columns.

Project Idea:
Deciding the correct price for a short term rental is a complex process. Pricing it too high will result in low occupancy while pricing it too low will result in heavy losses. At present when someone wants to list an Airbnb rental, they have to manually analyze similar properties near their location and decide the price themselves. 
The idea of our project is to form a tool which will help the new users estimate what the correct price of their rental should be given the features of their property. We will train the regression model on the available data and then design a console based python program which will ask the users a set of questions regarding their property and then predict what the price of their rental should be.
The tool will also provide simple suggestions to the user based on the regression model to help them get the max rental price while not losing out on the occupancy. For example, If the user has set strict cancellation policy, then the tool will provide suggestion like if they change the cancellation policy to moderate they can fetch 10$ additional or say if the user can include internet facility with the room, then it can fetch him an additional 15$.
 As the dataset has been scraped from Airbnb, it requires extensive cleaning, imputation of the missing values and feature engineering before creating the model. What makes this idea challenging is that no two rentals are the same. All rentals are unique because of their location, amenities, reviews, size, etc. 
