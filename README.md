public class BannerApp {

    public static void main(String[] args) {
        String[] banner = {
            getHeaderFooter(),
            getLetterO(),
            getLetterP(),
            getLetterS(),
            getLetterS(), // Reusing the method for the second 'S'
            getHeaderFooter()
        };

        for (String line : banner) {
            System.out.println(line);
        }
    }

    public static String getHeaderFooter() {
        return "*************";
    }

    public static String getLetterO() {
        return "* OOOOO   *";
    }

    public static String getLetterP() {
        return "* PPPPP   *";
    }

    public static String getLetterS() {
        return "* SSSSS   *";
    }
}
