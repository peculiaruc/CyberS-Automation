
#print(len("125"))

# Access a text file in Python. 
# .read
#file.text = login_attempts.txt # type: ignore
#login_attemps.txt = "jiuhg", "rti879l", "ioiokk0" # type: ignore

#with open(login_attemps.txt, "r")as file: # type: ignore
#    file_text = file.read()
#username = file_text.split()

#def login(login_list, current_user):
 #   counter = 0
#for i in login_list:


#Parse a text file in Python
# Task: 1. Assign `import_file` to the name of the file 
# 2. Assign `remove_list` to a list of IP addresses that are no longer allowed to access restricted information. 
# 3. Display `import_file`
# 4. Display `remove_list`

import_file = "allow_list.txt"
remove_list = ["192.168.97.225", "192.168.158.170", "192.168.201.40", "192.168.58.57"]
print(import_file)
print(remove_list)

# Task 3
# Now, use the .read() method to read the imported file and store it in a variable named ip_addresses.
# Afterwards, display ip_addresses to examine the data in its current format.

#Solution:
# Assign `import_file` to the name of the file 
# Assign `remove_list` to a list of IP addresses that are no longer allowed to access restricted information. 
# Build `with` statement to read in the initial contents of the file
# Use `.read()` to read the imported file and store it in a variable named `ip_addresses`
# Display `ip_addresses`
import_file = "allow_list.txt"
remove_list = ["192.168.97.225", "192.168.158.170", "192.168.201.40", "192.168.58.57"]
with open(import_file, "r") as file:
  ip_addresses = file.read()
print(ip_addresses)