public class ArraySearch {
    public static void main(String[] args) {
        int [] simpleArray = {1, 3, 4, 5, 6, 7, 8, 23, 56, 64, 24, 61, 76};
        int [] randomlyGeneratedArray = {12, 32, 13, 43, 24, 54, 46, 75, 45, 80, 34, 27, 83, 76, 83, 95, 100};
        calculateArrayMaxElement(simpleArray);
        calculateArrayMaxElement(randomlyGeneratedArray);
    }

    static void calculateArrayMaxElement(int [] array) {
        int max = array[0];
        int maxIndex = 0;
        int comparisons = 0;
        int replacements = 0;

        System.out.println();
        for(int i = 0; i < array.length; i++) {
            if(array[i] > max) {
                max = array[i];
                maxIndex = i;
                replacements++;
            }
            comparisons++;
        }
        System.out.println("The largest element of the array: " + max);
        System.out.println("The index of the largest element in current array: " + maxIndex);
        System.out.println("The amount of comparisons: " + comparisons);
        System.out.println("The number of replacements " + replacements);
    }
}
