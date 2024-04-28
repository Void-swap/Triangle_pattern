public class triangle {
    static int base = 5;

    public static void main(String arg[]) {
        pattern();
    }

    static void pattern() {
        int mid = base / 2;
        int start = mid;
        int end = mid;
        int level = 1; // starts with lvl 1
        while (start >= 0) {
            for (int i = 0; i <= base; i++) {
                if (i >= start && i <= end)
                    System.out.print("*");
                else
                    System.out.print(" ");
            }
            start--;
            end++;
            level++;
            System.out.println();
        }
    }
}
