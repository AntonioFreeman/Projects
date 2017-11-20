public class Lesson1 {
    public static void main(String[] args) {
        String[] food = {"фенхель", "пармезан", "лапша", "банан", "патока"};
        for (String s : food)
            System.out.println(s);
        for (String s : food) {
            if (s.startsWith("па"))
                System.out.println(s + " начинается с па");
        }
        for (String s : food) {
            if (s.endsWith("ан"))
                System.out.println(s + " заканчивается на ан");
        }

    }
}
