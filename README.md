- 👋 Hi, I’m @2053330278
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
2053330278/2053330278 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
s = input()
l = list(s)
x = []
for i in l:
    if i=="A" or i=="a" or i=="E" or i == 'e' or i=='i' or i=="I" or i=="o" or i=="O" or i=="u" or i=="U":
        continue
    else:
        x.append(i)
for i in x:
    print(i,end="")
