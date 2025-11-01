# Hotel Management System (BBIM502 Project)

This is a simple Python program made for my BBIM502 – Introduction to Programming course.  
It helps manage hotel rooms, guests, and bookings using the console.

---

## How It Works
1. Run the file **hotel_management.py** once.  
   It will create a text file to store room and booking data.
2. Use the menu to:
   - Add or delete rooms  
   - View all rooms  
   - Book a room for a guest  
   - Checkout a guest and see their bill  
   - Save or read booking data  
   - Make a backup and clear old data
3. When you add rooms and save, the program makes files like:
   - `hotel_data.txt` → main data file with bookings  
   - `hotel_backup_YYYYMMDD_HHMMSS.txt` → backup copy  
4. When you run the program again, it reads your saved data so you can continue from last time.

---

## Files
- `hotel_management.py` → main program  
- `.txt` files → created automatically to store and back up data  

---

## About
This project was made to practice Python basics such as:
- Functions and loops  
- File input/output  
- Error handling  
- Simple menu systems  

It’s a small, easy-to-use console app that shows how a hotel might manage rooms and bookings.
