# Generate-Password-with-Python
import random
paswrd_len = int(input("Enter the password  length :-"))
v=("abcdefghijklmnopqrstuvwxyz1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ!@#$%^&*()?")
join ="".join(random.sample(v,paswrd_len))
print(join)
