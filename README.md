```java
package com.todorkrastev

public class TodorKrastev extends SoftwareDeveloper implements SoftwareUniversity {

    private static final String ABOUT_ME = """
            Tech Stack
                • Languages: Java, C++, JavaScript, HTML, and CSS
                • Frameworks and Libraries: Spring, JPA/Hibernate, Angular, and Thymeleaf
                • Databases: MySQL
                • Tools: Git, Docker, Gradle, and Maven
            Skills
                • OOP and SOLID principles
                • Data Structures and Algorithms
            Education
                • Diploma in Java Full-Stack Development
                • Master of Finance
                • Bachelor of Economics
            Languages
                • English, German, and Spanish
            Interests
                • Algorithms and Algorithm Engineering
                """;
                
    public TodorKrastev() {
        super(ABOUT_ME);
    }
}
```
