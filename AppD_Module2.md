### Assignment 2: Stake Dice Game with Firebase Integration

**Objective:**  
Extend the Stake Dice Game by incorporating Firebase for user authentication, real-time database functionality, and additional features to enhance the app's capabilities.

---

### **Requirements**

#### **Core Features (COMPULSORY)**
1. **User Authentication**:  
   - Implement Firebase Authentication to allow users to sign up, log in, and log out.
   - Use email and password for authentication.
   - Display the user's email on the main screen after logging in.

2. **Wallet Syncing with Firebase**:  
   - Store each user's wallet balance in Firebase Realtime Database or Firestore.
   - Fetch the wallet balance upon login and display it.
   - Update the wallet balance in Firebase after each game round.

3. **Game History Storage**:  
   - Save each user's game history (wager, dice rolls, outcome, and updated balance) in Firebase.
   - Display the history in a dedicated screen.

4. **UI Updates**:  
   - Restrict access to the main game screen if the user is not logged in.
   - Add a logout button that returns the user to the login screen.

---

#### **Additional Stuff (Optional)**
Some ideas for additional things you might want to add to your app :p

1. **Leaderboards**:  
   - Create a global leaderboard showing top users with the highest wallet balances.
   - Fetch and display the leaderboard data from Firebase.

2. **Google Sign-In**:  
   - Allow users to log in using Google Sign-In as an alternative to email/password authentication.

3. **Daily Rewards**:  
   - Implement a feature to grant users daily login rewards (e.g., +5 coins).
   - Use Firebase to track when the reward was last claimed.

You can get creative and add any other fun stuff that you feel is a good addition to the app :)

