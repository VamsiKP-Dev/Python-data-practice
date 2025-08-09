# Python Data Practice Script

This is a beginner-friendly Python script demonstrating how to use variables, strings, tuples, lists, dictionaries, and simple arithmetic in Python. 
The theme of the script is based on a **real-life morning routine** like breakfast, bus stop, and office preparation.

---

## Code Explanation

### 1. Greeting Message
greeting = "good morning"

## 2. Updating Variable Values
momineedcoffee = "Bru coffee"
momineedcoffee = "Tea"
The variable momineedcoffee is first set to "Bru coffee" and then updated to "Tea" — this shows how Python allows reassigning values.

## 3. Stioring Breakfast info
whatisbreakfast = "Idly"
quantity = 5
plate = "5 idly", "Sambar", "Chetney"
# A string (whatisbreakfast) and integer (quantity) store values.
# plate is a tuple, which groups related breakfast items together.

## 4. Basic Arithmetic
youhadidly = quantity + 3

## 5. Tuple Example (Fixed Data Group)
# A tuple is created with 4 items.
lunchbox = "rice", "sambar", "snacks", "fruits"
# lunchbox[2] accesses the third item: "snacks" (Python indexing starts at 0).
lunchbox[2]

## 6. Bus and Office Information
# Basic variables storing daily commute info.
bustop = "ganesha temple new thippasandra"
timing = "8:30 am"
busno = 314
mystop = "Bagmane tech park"
company = "Volvo"

## 7. Using a List
# A list holds office essentials. We add "friend" using .append() — this shows that lists are mutable (changeable).
office = ["Laptop bag", "your id card", "mobilephone", "lunch box"]
office.append("friend")

## 8. Using a Dictionary

dicts = {
    "vamsi": "sde1",
    "venkatesh": "sde2",
    "suresh": "sde3"
}

print(dicts["venkatesh"])

dicts["venkatesh"] = "sde6"
print(dicts)

# A dictionary is used to store names and job roles.
# First, it prints venkatesh's role (sde2).
# Then it updates venkatesh to a new role (sde6) and prints the updated dictionary.


