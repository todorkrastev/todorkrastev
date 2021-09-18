```java

package gitHub.beinsaDuno.todorKrastev

public class TodorKrastev extends SoftwareDeveloper implements SoftwareUniversity {
    private static final String aboutMe =
            "Languages: Java(Advanced), JavaScript(Fundamentals), C++(Basics)" +
                    "Skills: OOP & SOLID, Data Structures & Algorithms" +
                    "Education: Student @SoftUni";

    public TodorKrastev() {
        super(aboutMe);
    }
}
