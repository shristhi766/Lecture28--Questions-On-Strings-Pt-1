# Lecture28--Questions-On-Strings-Pt-1
package strings;
public class ReverseAString{
   public sttaic void main(String[] args){
     String s1 = "CipherSchool";
     int n = s1.length();
     char arr] = new char[n];
     for (int i =0 ; i<n ; i++)
     {
        arr[i] = s1.charAt(n-1-i);
        //arr has a reversed string
        String rev = new String(arr);
        //what is the tie complexity -> O(n)
        // Is it an In place solution -> no, we create arr[]
        //what is space complexity -> O
        String res = new string();
        for (int i = n-1; i> 0 ; i--)
        {
           res = res.charAt(i); /// TC-> O(n) -> but creating new object again & again 
        }
          System.out.println(res);
        //Approach 3
        char str arr [] = s1.toCharArray();
        int l = 0;
        int r = n-1;
        while (l<r){
        char temp = strArr[1];
        strArr[l] = strArr[r];
        strArr[r] = temp;
        }
           // swapping completed
           String result = new String(strArr);
           }
          }
      }
    
