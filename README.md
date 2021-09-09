# assignment2-Muddasani
# Sahithi Muddasani
### Chennai,India
 Among the places that I had visited, I felt **Chennai** as the best place to live in despite of its **hot** weather conditions. It has a wide range of cultures in the lifestyle of people living there that vary from deep rooted **Indian culture** to growing **western culture**.

--- 

## Directions from Maryville to Chennai
1. Book a flight from Kansas International Aiport to Chennai, India.

1. Book an Uber ride from Maryville to Kansas International Airport to commence International journey.
    1. Board the cab and go to Airport.
    2. Complete the Check-in Procedure
    6. Board the Flight to Chennai.

1. After reaching the destination, make sure to collect all your baggage from the counter then exit from the Airport and look for a cab to explore the city and try varities of hot spicy foods and enjoy at the beaches.

* Soft Drinks
* Sunscreen
* Umbrella
* volleyball
* Food

[ABout me](Aboutme.md)

***
# FOOD AND DRINKS
Best foods:

|FOOD | PLACE | PRICE
|---|---|---|
|Vanilla fudge ice cream | cream stone |$3
|milkshake| makers of milkshake |$4
|chat|gokul chat|$7

***
 # Best quotes

 > Honesty is the best policy *-william groot*

 >The purpose of the life is to  live happy *- rendem green*


***
 # Code fencing
 > Depth-first search (DFS) is an algorithm for traversing or searching tree or graph data structures. The algorithm starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as far as possible along each branch before backtracking.

 [DFS](https://en.wikipedia.org/wiki/Depth-first_search)

 ```vector<vector<int>> adj; // graph represented as an adjacency list
int n; // number of vertices

vector<bool> visited;

void dfs(int v) {
    visited[v] = true;
    for (int u : adj[v]) {
        if (!visited[u])
            dfs(u);
    }
}
````


[CODE](https://cp-algorithms.com/graph/depth-first-search.html)

