# Proyecto -geospatial-data-project-

## 1. Objetive

A company that has hired me to find their new office to relocate to, so I have been tasked to find the right office based on at least three of the following criteria (knowing in advance that it is impossible to cover all of them):

    1) Designers like to go to design talks and share knowledge. There must be some nearby companies that also design.
    2) 30% of the company has at least 1 child. (day care centers)
    3) Developers like to be close to successful tech startups that have raised at least $1M.
    4) Executives really like Starbucks. Make sure there is a Starbucks not too far away.
    5) Account managers need to travel a lot.
    6) Everyone in the company is between 25 and 40 years old, give them somewhere to party.
    7) The CEO is a vegan.
    8) If you want to make the maintenance guy happy, a basketball arena should be about 10 miles away.
    9) The office dog "Pepe" needs a groomer every month. Make sure there is one not too far away.

I have chosen points 1, 7 and 8.

------


## 2. Development

The preliminary intention is to analyze which companies within the **companies.json** file meet one of the initial requirements.

Then proceed to locate my company among the possible locations of the companies, and then using geolocation and the API get the requirements based on the proximity of the company.


I have chosen the location of the company based on which important design spaces are "close" to the company.

3.1. Based on the list provided by: https://gruposaglo.com/2019/05/23/las-mejores-escuelas-de-diseno-en-los-estados-unidos/ I make the first sift between east and west coast, seeing that on the west coast there are two important centers in the state of New York, namely the **Pratt Institute** and the **Rochester Institute of Technology**.

3.2. The second step is to see how many companies are in New York City as the urban center of the state and the country.

3.3. I read the documentation and research how to connect to the FourSquare API (chosen from other options).

3.4. I make the *unwinded* of the database in MongoDB, to separate the different offices that a single company may have.

3.5. I generate the code to access to the chosen queries with the parameters that I need.

3.6. I search for the different queries and generate the code that automates the obtaining of the necessary data.

3.7. Finally I generate a map with the markers found and customize it.

---