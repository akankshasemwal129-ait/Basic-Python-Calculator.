# Basic-Python-Calculator.
# Basic Calculator - Add and Subtract

num1 = float(input("Pehla number daalo: "))
num2 = float(input("Dusra number daalo: "))

print("Kya karna hai? 1 = Add, 2 = Subtract")
choice = input("Apna choice daalo (1/2): ")

if choice == '1':
    result = num1 + num2
    print("Answer hai:", result)
elif choice == '2':
    result = num1 - num2
    print("Answer hai:", result)
else:
    print("Galat choice daala bhai!")

Line-by-line समझाई (Hinglish analogies ke saath):

1) num1 = float(input(...)) — Ye line user se pehla number poochti hai, jaise dukaan waala poochta hai "kitna saaman chahiye?" float() isliye lagaya hai taaki decimal number (jaise 5.5) bhi le sake, sirf whole number nahi.
2) num2 = float(input(...)) — Same cheez, bas dusra number le raha hai. Socho tum do dost ke paas paise maang rahe ho, ek-ek karke.
3) print("Kya karna hai?...") — Ye ek menu dikha raha hai, bilkul restaurant ke menu card jaisa — "Add chahiye ya Subtract?"
4) Choice = input(...) — User apna order de raha hai, jaise waiter ko bolte ho "1 number 2 please.”
5)if choice == '1': — Ye check kar raha hai ki user ne "1" bola ya nahi. Socho ek darwaza hai jisme sirf sahi password se hi entry milti hai.
6) result = num1 + num2 — Agar "1" bola, toh dono number jod diye — jaise do glass paani ek bade jug mein daal diya.
7)elif choice == '2': — Agar pehla darwaza match nahi hua, toh ye doosra darwaza check karta hai — "2" wala.
8) result = num1 - num2 — Yahan pehle number mein se dusra ghata diya — jaise tumhare paas 10 rupaye the, dost ne 3 le liye, bacha 7.
9)else: — Agar user ne 1 ya 2 chhodkar kuch aur daala, toh ye "galat entry" wala message dikhata hai — security guard bol raha hai "bhai, yahan entry nahi hai.”
