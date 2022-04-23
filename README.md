```java
package gitHub.todorKrastev

public class TodorKrastev extends SoftwareDeveloper implements SoftwareUniversity {
    private static final String ABOUT_ME = """
                Technologies: Java (advanced), JavaScript (advanced), C++ (fundamentals), Python (basics), SQL, HTML, CSS
                Skills: OOP & SOLID, Data Structures & Algorithms
                Education: Software Engineering (studying now), Master of Finance, Bachelor of Economics
                Languages: English (C1), German (B2 - studying now), Spanish (B1), Bulgarian (C2)
                Interests: AI, Algorithms and Algorithm Engineering""";
                
    public TodorKrastev() {
        super(ABOUT_ME);
    }
}
```
