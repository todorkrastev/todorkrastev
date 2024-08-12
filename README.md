```java
package com.todorkrastev

public class TodorKrastev extends SoftwareDeveloper implements SoftwareUniversity {

    private static final String ABOUT_ME = """
                Tech Stack: Java, Spring, C++, MySQL, Angular, JavaScript, HTML, CSS
                Skills: OOP & SOLID, Data Structures & Algorithms
                Education: Software Engineering, Master of Finance, Bachelor of Economics
                Languages: Bulgarian, English, German, Spanish
                Interests: AI
                """;
                
    public TodorKrastev() {
        super(ABOUT_ME);
    }
}
```
