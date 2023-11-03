import java.util.Collections;
import java.util.Arrays;

public class Main {
    public static void main(String[] args) {
        Integer[] numbers = {1, 2, 3, 4, 5, 6, 7};
        Collections.shuffle(Arrays.asList(numbers));
        System.out.println(Arrays.toString(numbers));
    }
}
