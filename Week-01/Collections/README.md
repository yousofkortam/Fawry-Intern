# Collections

## Resources

- #### From [Java-T-Point](https://www.javatpoint.com/collections-in-java) Website
- #### From [GeeksForGeeks](https://www.geeksforgeeks.org/collections-in-java-2/) Website
- #### Eng. Asmaa [GitHub Repo](https://github.com/AsmaaIR/java-topics) & [2023JUL Session](https://drive.google.com/file/d/1eJQr-JnOhET2pmU21lBQOhprVoyeFAEk/view?usp=drive_link)

## Task:

### We should read and discuss the following use-cases and see the suitable java collection for every use-case:

1. When working with a large collection where frequent insertion and deletion operations are expected, and random access is not a primary concern, what is the best choice ?


2. Suppose you are building an inventory management system for an online store. You need to keep track of the available stock of products. Each product has a unique identifier (product ID) and a corresponding quantity in stock. Which Collection can we use to solve this?


3. Suppose you are developing a user activity tracking system where you need to maintain the order of user actions. You want to store the actions in a collection while ensuring uniqueness?


4. In a social media application, there are millions of user posts generated every day. How can Java Collections help you handle and display the latest posts efficiently? Which collection would you use to maintain a sorted order of posts based on their timestamps?


5. You are developing a game, and you want to keep track of the top 10 players' high scores. Which Java Collection would be most appropriate for maintaining this leaderboard?


6. You are building a movie recommendation system. How would you store the movie data and user preferences using Java Collections? How would you efficiently retrieve and suggest movie recommendations based on a user's previous choices?


7. You are implementing a caching mechanism where each cached item must be unique and in the order of its insertion. Which Java collection would you use, and what advantages does it offer for this use case?


8. You need to store user session data where each user has a unique session ID, and you need quick retrieval by session ID. Which Java collection would you use, and what advantages does it offer for this use case?


9. You need to maintain a list of user comments on a blog post where duplicates are allowed and the order of insertion is preserved. Which Java collection would you use and why?


10. You need to implement a task scheduler where tasks are executed based on their priority. Which Java collection would you use, and what advantages does it offer for this scenario?

## My Solution

1. **Linked List**: Ideal for frequent insertions and deletions, as elements can be added or removed without shifting elements, though it sacrifices random access speed.


2. **HashMap**: Provides fast retrieval, insertion, and deletion of product stock using unique product IDs as keys.


3. **LinkedHashSet or LinkedHashMap**: Ensures uniqueness and maintains the insertion order of user actions, making it suitable for tracking ordered, non-duplicate events.


4. **TreeSet**: Automatically sorts posts by timestamp, providing efficient handling and display of the latest posts in a sorted order.


5. **PriorityQueue**: Maintains the top 10 players' scores in a sorted order, with efficient retrieval and updating of the leaderboard.


6. **ArrayList + HashMap**: ArrayList can store user preferences, while HashMap can map user IDs to their preferences, allowing efficient retrieval and suggestion based on previous choices.


7. **LinkedHashMap**: Maintains insertion order and ensures uniqueness, making it suitable for caching mechanisms where order and uniqueness are crucial.


8. **HashMap**: Provides quick retrieval of session data using unique session IDs, offering O(1) complexity for access, insertion, and deletion.


9. **LinkedList or ArrayList**: Both allow duplicates and preserve insertion order, with LinkedList being more efficient for frequent insertions/deletions and ArrayList for faster random access.


10. **PriorityQueue**: Executes tasks based on priority, ensuring that the highest priority tasks are always processed first, suitable for a task scheduler.
