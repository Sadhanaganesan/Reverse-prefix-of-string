public class Solution {

    public static void main(String[] args) {
        Scanner s=new Scanner(System.in);
        String str=s.nextLine();
        char ch=s.next().charAt(0);
        int index=str.indexOf(ch);
        char[]c=str.toCharArray();
        for(int i=0;i<=index/2;i++){
            char t=c[i];
            c[i]=c[index-i];
            c[index-i]=t;
        }
        System.out.println(new String(c));
    }
}
