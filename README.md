## ✌️
---
```java
class Me {
    private String name = "Nathan";
    private int age = 16;
    private String[] interests = {"app development", "machine learning"}; 
    private String funFact = "I can speak and code in 3 languages!";

    public String greet() {
        return "Hi, I'm " + name + " and I'm " + age ". " I am currently interested in " + interests[0] + " and " + interests[1] + ".";
    }

    public String aboutMe() {
        return "A fun fact about me is that " + funFact + "!";
    }
    
    public static void main() {
        Me me = new Me();
        System.out.println(me.greet());
        System.out.println(me.aboutMe());
    }
}
```
