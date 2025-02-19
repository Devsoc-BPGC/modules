# **📈 Stock Return Calculator**

## **Requirements:**

### **1. API Integration (5 points)**
- Integrate the **Alpha Vantage API** to fetch historical stock price data.  
- Since the API does not provide exact minute-level data, you can:
  - Use the average stock values for the day: **(high + low) / 2**  
  - OR allow users to choose between the **high** or **low** price range.  
  - The implementation details are left to you.  
- Allow users to input **stock symbols, purchase dates, sell dates, and quantities** to retrieve relevant data.

### **2. User Authentication (5 points)**
- Implement **Firebase Authentication** for user **sign-up** and **login**.  
- Ensure **secure and personalized** access to user portfolios and transaction history.  

### **3. Profit/Loss Calculation (10 points)**
- Develop logic to **calculate profit or loss** based on fetched stock data and user inputs.  
- Display **investment returns** prominently to users after calculations.  

### **4. User Interface (5 points)**
- Design an **intuitive and responsive UI** using **Flutter widgets**.  
- Include **input fields** for:  
  - Stock symbol  
  - Purchase date  
  - Sell date  
  - Quantity  
- Display the **calculated profit or loss** clearly and attractively.  

### **5. Data Storage (5 points)**
- Store the **last 5 calculated returns** in **Firestore**, including:  
  - Stock name  
  - Buy date / Sell date  
- Ensure the stored data reflects **recent calculations** chosen by the user.  
