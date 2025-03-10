```java
package com.todorkrastev

public class TodorKrastev extends SoftwareDeveloper implements SoftwareUniversity {

    private static final String ABOUT_ME = """
            Tech Stack
                • Languages: Java, C++, JavaScript, HTML, CSS
                • Frameworks and Libraries: Spring, JPA/Hibernate, Angular, Thymeleaf
                • Databases: MySQL
                • Tools: Git, Docker, Gradle, Maven
            Skills
                • OOP and SOLID principles
                • Data Structures and Algorithms
            Education
                • Diploma in Software Engineering
                • Master of Finance
                • Bachelor of Economics
            Languages
                • Bulgarian, English, German, Spanish
            Interests
                • AI, Algorithms, Algorithm Engineering
                """;
                
    public TodorKrastev() {
        super(ABOUT_ME);
    }
}
```
