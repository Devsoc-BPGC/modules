
## **Assignment: Stake Dice Game**

### **Objective:**
Create a Flutter app that simulates a high-risk, high-reward dice game.. The app will allow users to place wagers and roll dice to win or lose coins based on specific game conditions.

---

### **Requirements:**

1. **Core Features (COMPULSORY)** – Implement the following:  
   - A **wallet balance** is displayed and initialized to 10 coins.  
   - Users can enter a **wager** amount and select one of the following game types:  
     - **"2 Alike"**: Win or lose 2x the wager.  
     - **"3 Alike"**: Win or lose 3x the wager.  
     - **"4 Alike"**: Win or lose 4x the wager.  
   - Check if the wager is valid based on the current wallet balance:  
     - Maximum wager for **"2 alike"** = Balance ÷ 2  
     - Maximum wager for **"3 alike"** = Balance ÷ 3  
     - Maximum wager for **"4 alike"** = Balance ÷ 4  
   - When the user presses the **“Go”** button:  
     - Roll four dice (generate random numbers between 1 and 6 for each dice).  
     - Display the result via a **Toast message** (showing the dice rolls and if the player won or lost).  
     - Update the wallet balance based on the result.  
     - Clear the wager input field.  
   (**5 PTS**)

---

### **Additional Features (Optional):**  
   - **Dice Animation**: Add animations when rolling the dice.  
   - **History Screen**: Show a history of past wagers, dice rolls, and outcomes.  
   - **Sound Effects**: Play a sound when the dice are rolled.  
   - **Custom UI**: Design a custom layout with images of dice and a creative interface.  
   (**+5 PTS**)

---

### **Game Logic Example:**  

- **Wallet Balance**: 10 coins  
- **Game Selection**: "3 Alike"  
- **Wager**: 4 coins (INVALID, because 10 ÷ 3 = 3 max wager)  
- **Wager**: 3 coins (VALID)  

When the player hits **“Go”**:  
- Four dice are rolled (e.g., 3, 3, 3, 5).  
- Since there are **three alike**, the player **wins** 3 × 3 = 9 coins.  
- Wallet balance is updated to 10 + 9 = 19 coins.

---


### **Evaluation Criteria:**  
1. Core Features Implementation (5 PTS)  
2. Additional Features (Up to 5 PTS)  
3. Responsive Design (Up to 5 PTS)  
4. Creativity and UI Design (Up to 5 PTS)
5. Brownie (5 points for extra stuff)

---

This assignment will help you practice Flutter concepts like usage of widgets, form validation, random number generation, and UI design.
