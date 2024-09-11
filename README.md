HEAD
´´´mermaid 
´´´
---
title: Animal example
---
classDiagram
    note "From Duck till Zebra"
    Animal <|-- Duck
    note for Duck "can fly\ncan swim\ncan dive\ncan help in debugging"
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
        +String beakColor
        +swim()
        +quack()
    }
    class Fish{
        -int sizeInFeet
        -canEat()
    }
    class Zebra{
        +bool is_wild
        +run()
    }

# gitlek2
=======
# gitlek2


This is **bold**

1. First item
2. Second item
3. Third item


---

| Syntax | Description |
| ---------- | ---------- |
| Header | Title |
| Paragraph | Text |
>>>>>>> dfbcbb537692ff637f16030d25fd0f9837e5949b
