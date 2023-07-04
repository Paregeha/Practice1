import java.util.Random;

public class Scrambler {
    public static void main(String[] args) {
        int[] arrayInput = new int[]{0,1,1,0,0,1,0};
        for (int i: arrayInput) {
            System.out.print(i + ", ");
        }
        System.out.println();
        int k = 70;
        int k1 = arrayInput.length;
        int[] inputSignal = new int[k];

        Random random = new Random();

        for (int i = 0; i < k; i++) {
            inputSignal[i] = random.nextInt(2) ;
            System.out.print(inputSignal[i] + ", ");
        }
    }
}