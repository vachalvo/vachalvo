### Hi there, I'm Vojtěch 👋

I'm Student, Developer and Programmer.

- 🔭 I’m currently working at Unicorn
- 🌱 I’m currently learning React, .NET and other
- ⚡ 2022 Goals: finish fourth year of school, travel, learn new technology, read books.

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
            new Knowledge("OOP");
        };
    }

    public String getMotto() {
        return "Think, plan, execute...";
    }
}
```
