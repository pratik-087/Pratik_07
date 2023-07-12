class Bitwise {
    public static void main(String [] args) {
        byte x,y;
        x=10;
        y=-10;
        System.out.println("Bitwise left shift (x<<2):"+(x<<2));
        System.out.println("Bitwise right shift (x>>2):"+(x>>2));
        System.out.println("Bitwise zero fill right shift (x>>>2):"+(x>>>2));
        System.out.println("Bitwise zero fill left shift (y>>>2):"+(y>>>2));
    }
}
