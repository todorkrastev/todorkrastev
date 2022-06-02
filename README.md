```java
package io.github.todorkrastev

public class TodorKrastev extends SoftwareDeveloper implements SoftwareUniversity {

    private static final String ABOUT_ME = """
                Technologies: Java, C++, Python, SQL, JavaScript, HTML, CSS
                Skills: OOP & SOLID, Data Structures & Algorithms
                Education: Software Engineering, Master of Finance, Bachelor of Economics
                Languages: Bulgarian, English, German, Spanish
                Interests: AI, Algorithms and Algorithm Engineering
                """;
                
    public TodorKrastev() {
        super(ABOUT_ME);
    }
}
```
