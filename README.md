# Arunesh_portfolio

## [Project 1: A simple Django app to find page ranking in google by keywords.](https://github.com/aruneshroy91/django-pagerank)

1. First fetch the google search data. To solve this use Requests
package along with custom search engine and a generated API key is used to obtain the google
search data.
2. A code for making the query and ranking :
◦ A loop over all 10 pages fetched by Google search
◦ API request is made to fetch search data for particular page with desired keyword
◦ Another loop inside the first loop investigates the page data to obtain the desired keyword
and parent domain.
◦ If the domain name ends with target domain we get the page rank and other features printed.
Django integration
1. In home.html we ask for the input, target domain and the keyword(s).
2. Send the input data in the add function of views.py
3. The logic of the code is integrated within the views.py
4. Returns JSON response.

## [Project 2: Profitable-App-Profiles-for-the-App-Store-and-Google-Play-Markets](https://github.com/aruneshroy91/Profitable-App-Profiles-for-the-App-Store-and-Google-Play-Markets)
Analyze data to understand what type of apps are likely to attract more users
* Description of the Apple Store dataset 
One can find the dataset [here](https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps).
* Data Cleaning
We are interested in free English apps
* Remove duplicate entries
Check whether the data contains any app data for multiple times.
* Cleaned for unique data
We curated a dictonary using the number of reviews as stated above to find the app data corresponsing to the maximum number of reviews. 
* iOS data do not contain duplicate entries
*Filter non-English apps: We will focus here only on the English apps
* Find an app profile that fits both the App Store and Google Play
* Analysis of "prime_genre" in App Store data
* The most common genre is "Games". The second most common genre is "Entertaiment"
* The least common genre is "Catalog".
* Most apps are designed for entertainment purpose (games, photo and videos etc) as opposed to the practical purposes (education, shopping, utilities etc)

* App Store app recommnedation
Besed on the analysis above based on user rating per genre, the recommended app profile should be "Games".

* Analysis of "Category" and "Genres" in Play Store data
* Tools, Entertainment, Education, Business are the most common genres.
* Apps for practical and well as for entertainment is present which is in contrast with the App Store data.
* An app which can cover both entertainment and gaming genre can become a profitable app.
* The frequncy tables indicate that the app genres with most frequency can be the apps with most users. But some other parameters must be considered before a concrete conclusion. 
* Most profitable app profile
App that deals with productivity will be the most profitable app profile.
