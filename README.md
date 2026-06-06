# Flower Shop Bouquet Designer 🌸

This is a console-based C++ project that was developed as a **group assignment for university**.
The system works as a simple flower shop management program where customers can create bouquets,
florists manage inventory, and admins handle orders and user accounts. It also uses file handling to store data permanently.



## Project Overview
This system is divided into three main modules:

### Customer
- Login system for customers  
- Create custom bouquets by selecting flowers  
- Add flowers with quantity  
- View bouquet details  
- Place orders (checkout system)  
- View order history  
- Update profile  

### Florist
- Login system for florist  
- Add and update flower stock  
- Update flower prices  
- View all orders  
- Check low stock alerts  
- Update login details  

### Admin
- Login system for admin  
- View all orders  
- Delete or reset order history  
- Manage user accounts (customer, florist, admin)  

---

## File Handling
The project uses text files to store and manage data:

- `flowers.txt` → stores flower inventory (ID, name, price, stock)  
- `orders.txt` → stores all placed orders  
- `order_id.txt` → keeps track of order IDs  
- `customerlogin.txt` → customer login credentials  
- `adminlogin.txt` → admin login credentials  
- `floristlogin.txt` → florist login credentials  

---

## How to Run
1. Clone the repository:
git clone https://github.com/YOUR_USERNAME/Flower-Shop-Bouquet-Designer.git

2. Navigate to the project folder:
cd Flower-Shop-Bouquet-Designer

3. Compile the program:
g++ main.cpp -o flower_shop

4. Run the executable:
flower_shop

## Concepts Used
- C++ functions and modular programming  
- Arrays and string handling  
- File handling (ifstream / ofstream)  
- Menu-driven system  
- Input validation  
- Basic inventory and order management logic  

## Learning Outcome
This project helped us understand how a real-world system like a flower shop
can be built using basic programming concepts. We learned how file handling works
in C++ and how different roles (customer, florist, and admin) can work together within a single system.
