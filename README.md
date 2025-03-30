
# goit-js-hw-05  

This repository contains JavaScript functions for working with user data.  

## `task-1.js` - `getUserNames(users)`  
Extracts and returns an array of user names from a given list of user objects.  

**Params:**  
- `users` (array) – an array of user objects, each containing a `name` property  

**Example:**  
```js
getUserNames([
  { name: 'Moore Hensley', email: 'moorehensley@indexia.com', balance: 2811 },
  { name: 'Sharlene Bush', email: 'sharlenebush@tubesys.com', balance: 3821 }
]); 
// ["Moore Hensley", "Sharlene Bush"]
```

---
## `task-2.js` - `getUsersWithFriend(users, friendName)`

Filters users who have a specific friend in their friends list.  

**Params:**
-   `users` (array) – an array of user objects, each containing a `friends` property (array)
-   `friendName` (string) – the name of the friend to search for
    

**Example:**
```js
getUsersWithFriend(allUsers, 'Briana Decker'); // Returns users who have 'Briana Decker' as a friend
```
---
## `task-3.js` - `sortByDescendingFriendCount(users)`

Sorts users in descending order based on the number of friends they have.  

**Params:**
-   `users` (array) – an array of user objects, each containing a `friends` property (array)

**Example:**
```js
sortByDescendingFriendCount(allUsers); // Users sorted from most to least friends
``` 

---

## `task-4.js` - `getTotalBalanceByGender(users, gender)`

Calculates the total balance for all users of a specific gender.  

**Params:**
-   `users` (array) – an array of user objects, each containing `gender` and `balance` properties
-   `gender` (string) – the gender to filter by (`"male"` or `"female"`)

**Example:**
```js
getTotalBalanceByGender(clients, 'male'); // 12053  getTotalBalanceByGender(clients, 'female'); // 8863
```