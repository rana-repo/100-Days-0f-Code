# Day 9 - Dictionarier, Nesting and Secret Auction
## Concepts Practised
- Dictionaries : a kind of data structure that stores items in key-value pairs. A key is a unique identifier for an item, and a value is the data associated with that key.
     {key: value}

 Example:

 programming_dictionary = {
    "Bug": "An error in a program that prevents the program from running as expected."
    "Function": "A piece of code that you can easily call over and over again."
 }    

 Retrieving items from dictionary.

 print(programming_dictionaey["Function"])


Adding new items to dictionary.

programming_dictionary["Loop"] = "The action of doing something over and over again."
print(programming_dictionary)

Create an empty dictionary.

empty_dictionary={}

loop through a dictionary

for key in programming_dictionary:
    print(key)
    print(programming_dictionary[key])


### Nesting

Capitals = {
    "France": "Paris",
    "Germany": "Berlin",
}

Nesting a list/Dictionary in a Disctionary

travel_log = {
    "France": {"Cities_visited": ["Paris", "Lille", "Dijon], "total_visits": 12},
    "Germany": ["Berlin", "Hamburg"]
}


Nesting Dictionary in a list

travel_log = [
    {
        "country": "France",
        "cities_visited": ["Paris" , "Lille", "Dijon"],
        "total_visits": 12
    },
    {
        "country" : "germany",
        "cities_visited: ["Berlin", "Hamburg", "Stuttgart"],
        "total_visits": 5
    },
]


## Secret Auction\