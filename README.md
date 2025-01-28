```java
package com.todorkrastev

public class TodorKrastev extends SoftwareDeveloper implements SoftwareUniversity {

    private static final String ABOUT_ME = """
                Tech Stack: Java, Spring, C++, MySQL, Angular, JavaScript, HTML & CSS.
                Skills: OOP & SOLID, Data Structures & Algorithms.
                Education: Diploma in Software Engineering, Master of Finance, and Bachelor of Economics.
                Languages: Bulgarian, English, German, and Spanish.
                Interests: AI, Algorithms, and Algorithm Engineering.
                """;
                
    public TodorKrastev() {
        super(ABOUT_ME);
    }
}
```
