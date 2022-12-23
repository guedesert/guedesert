```python
print("Hello, World!")

name = "Emanuel"
age = 27
location = "Maracanaú, Ceará, Brazil"
languages = ["HTML","CSS","JavaScript","Python","Kotlin"]
course = "Full Stack Development"
college = "Estácio"

person = [name,age,location,languages,course,college]

def presentation(someone) :
  print(f"My name is {someone[0]}, I'm {someone[1]} years old and I live in {someone[2]}.\nI'm interested in some languages I'm trying to learn, as {someone[3][0]}, {someone[3][1]}, {someone[3][2]}, because I really like front-end development, also {someone[3][3]} , because it's a clean language and I'm learning it in college, and lastly, {someone[3][4]}, I haven't started venturing myself into Kotlin yet, but I think it's interesting to learn a language for mobile development for a mobile dedicated operating system, such as Android, used in many devices around the world.\nI started studying Full Stack Development at Estácio in 2022.4 and I'm looking for new meaningful experiences as a developer.\nHere, I'll try to share my studies and on-going projects. Feel free to explore my GitHub!")

presentation(person)
```
<details><summary><strong>Run and Debug</strong></summary>

```
Hello, World!
My name is Emanuel, I'm 27 years old and I live in Maracanaú, Ceará, Brazil.
I'm interested in some languages I'm trying to learn, as HTML, CSS, JavaScript, because I really like front-end development,
also Python , because it's a clean language and I'm learning it in college, and lastly, Kotlin, I haven't started venturing
myself into Kotlin yet, but I think it's interesting to learn a language for mobile development for a mobile dedicated
operating system, such as Android, used in many devices around the world. I started studying Full Stack Development at
Estácio in 2022.4 and I'm looking for new meaningful experiences as a developer.
Here, I'll try to share my studies and on-going projects. Feel free to explore my GitHub!
```

</details>
