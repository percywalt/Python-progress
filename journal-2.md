## 📅 2026-04-08

### 🎯 Wat heb ik geleerd?
- if, elif, else statement

### 💻 Wat heb ik gedaan?

level = int(input()) # Don't change this line
has_training = input() == "True" # Don't change this line
level_message = "None" # Don't change this line

# Write your code below
if level <= 0:
    level_message = "Invalid level"
elif level <= 5:
        level_message = "Basic weapons only"
elif level <= 10:
    if has_training:
        level_message = "Access to advanced weapons granted"
    else:
        level_message = "Need weapon training first"
else: 
    level_message = "Access to all weapons granted"

# Don't change below this line
print(level_message)

# Don't change the line below
print(f"status = {status}")

### ❌ Problemen / fouten
- if to start
- than elif and than inside elif can if and else statement
- start from the end so it can make it as an existense

### 🧠 Wat snap ik nog niet?
- when if when elif and how to combine 

### ✅ Wat ging goed?
- nothing 

### 🔁 Morgen ga ik:
 - output with variables
