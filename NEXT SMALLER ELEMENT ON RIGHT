import java.util.*;
class Solution{
  public static int[] nser(int a[]){
    Stack<Integer> st=new Stack<>();
	  int ans[]=new int [a.length];
    for(int i=a.length-1;i>=0;i--)
    {
      while(!st.isEmpty() && st.peek() >= a[i])
      {
        st.pop();
      }
      if(st.isEmpty())
      {
        ans[i]=-1;
      }
      else {
        ans[i]=st.peek();
      }
      st.push(a[i]);
    }
    return ans;
  }
  public static void main(){
    Scanner sc=new Scanner(System.in);
    int n;
    System.out.println("Enter size of arrray\n");
    n=sc.nextInt();
    int a[]=new int[n];
    System.out.println("Enter elements of arrray\n");
    for(int i=0;i<n;i++)
    a[i]=sc.nextInt();
    int ans[]=nger(a);
    for(int i=0;i<n;i++){
    System.out.println(ans[i]);
    }
  }
}
