# Write-a-program-to-input-an-integer-find-the-result-of-the-multiplication-of-that-number-by-the-num
Write a program to input an integer, find the result of the multiplication of that number by the numbers 1 - 20 , then print the result to the screen.
import java.util.Scanner;

public class BaiTapJavaCoBan7 {
   public static void main(String[] args)
   {
      int n;
      int sum = 0;
      System.out.println("Nhập vào số nguyên:");
      Scanner sc = new Scanner(System.in);

      n = sc.nextInt();

      for (int i = 1; i <= 20; i++) // duyệt tất cả phần tử từ 1-20
      {
         System.out.println(n + " x " + i + " = " + n*i);
      }
   }
}
