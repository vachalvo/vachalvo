## 👋 Hi there I'm Vojtěch,

### 💻 Student, Developer and Programmer.

- 🔭 I’m currently working at Unicorn.
- 🌱 I’m currently learning React, .NET and other.
- 🏃 I´m interested in climbing, running, traveling and drinking Pilsner beer.
- ⚡ 2022 Goals: finish fourth year of uni, learn new technology and read some books.

```java
class About extends Me {
    
    private static String name = "Vojtěch Váchal";
    private static int age = 23;
    private static String city = "Pilsen";
    
    public Workspace[] getCurrentWorkplaces() {
        return new Workspace[] {
            new Workspace("Unicorn", "Junior Software Developer"),
            new Workspace("University of West Bohemia", "Student")
        };
    }

    public Knowledge[] getKnowledges() {
        return new Knowledge[] {
            new Knowledge("Java"),
            new Knowledge("JavaScript"),
            new Knowledge("React"),
            new Knowledge("C"),
            new Knowledge("Spring Boot"),
            new Knowledge("SQL"),
            new Knowledge("Git"),
            new Knowledge("REST"),
            new Knowledge("OOP")
        };
    }

    public String getMotto() {
        return "Think, plan, execute...";
    }
}
```
