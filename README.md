
# Friendship Pair Analysis
## Notice

This project is a part of my journey of learning data science. As I delve deeper into the field, this project represents a crucial step in understanding how to analyze and visualize data, particularly in the context of social networks. Through this work, I am not only honing my coding skills in Python but also gaining valuable insights into graph theory, and network analysis.

## Overview

This project explores friendships within a group of users, analyzing relationships and visualizing them as a network graph. The project includes the following key elements:

- **User Data Structure**: A list of users, each represented by a unique `id` and `name`.
- **Friendship Pairs**: Pairs of users indicating friendships.
- **Graph Representation**: A visual representation of the friendship network using `networkx` and `matplotlib`.
- **Analysis Functions**: Functions to calculate and analyze the number of friendships each user has.

## Project Structure

- **`Friendship_pair.ipynb`**: The main Jupyter notebook containing the code for analyzing and visualizing friendship pairs.

## Code Overview

### User Data and Friendships
- **Users**: A list of dictionaries where each dictionary represents a user with an `id` and `name`.
- **Friendship Pairs**: A list of tuples where each tuple represents a friendship between two users.

### Graph Representation
- The project uses `networkx` to represent friendships as a graph, where each node corresponds to a user, and each edge represents a friendship.

### Analysis Functions
- Functions are provided to calculate the number of friends each user has and to explore other aspects of the friendship network.

## Example Questions and Solutions

Here are 15 questions that the code in the notebook helps to solve:

1. How many users are there in total?
2. Which perosn has the most relationship?
3. Sort the people by the number of relationship, from most to least
4. Is there anyone with no firends?
5. Are all friendships mutual?
6. Find all people who have exactly 2 friends
7. Who is directly connected to both the most and the fewest people?
8. What is the average number oif friends per person?
9. Which pairs of people share the most mutual friends?
10. Is there any isolated group of friends (subgraph) that is not connected to others?
11. Find all friends of specific person (e.g. User 3) and their friends
12. Create a recommendation list: suggest new friends to each person based on therir friends.
13. Which person is at the center of the network (has the shortest average distance to all other people)?
14. List all pairs of friends that are also mutual friends with a third person.
15. If one friendship is removed at random, what is the probability that the network will still be fully connected?

## Integration with ChatGPT

This project was enhanced with the assistance of ChatGPT. Specifically, the following tasks were facilitated:

- **Generating Code Explanations**: ChatGPT provided detailed explanations for the code structure and logic, helping to create a comprehensive understanding of the project.
- **Creating the README**: The README file, including this markdown content, was generated with the help of ChatGPT to ensure clarity and completeness.
- **Problem-Solving Assistance**: ChatGPT was used to refine the problem-solving questions and ensure the solutions provided in the notebook were accurate.

