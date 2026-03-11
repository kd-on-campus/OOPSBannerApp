public class BannerApp {
    public static void main(String[] args) {
        String symbol = "*";
        String space = " ";

        String[] banner = {
            String.join("", symbol.repeat(13)),
            String.join("", symbol, space.repeat(11), symbol),
            String.join("", symbol, space.repeat(2), "WELCOME", space.repeat(2), symbol),
            String.join("", symbol, space.repeat(4), "TO", space.repeat(5), symbol),
            String.join("", symbol, space.repeat(2), "OOPS JAVA", space.repeat(2), symbol),
            String.join("", symbol, space.repeat(11), symbol),
            String.join("", symbol.repeat(13))
        };

        for (String line : banner) {
            System.out.println(line);
        }
    }
}
