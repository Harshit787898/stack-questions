import java.util.*;
class Solution {
    public boolean isValid(String s) {
    Stack<Character> stack = new Stack<Character>();
	for (char c : s.toCharArray()) {
		if (c == '(')
			stack.push(')');
		else if (c == '{')
			stack.push('}');
		else if (c == '[')
			stack.push(']');
		else if (stack.isEmpty() || stack.pop() != c)
			return false;
	}
	return stack.isEmpty();
    }
    public staic void main(){
    	Scanner sc=new Scanner(System.in);
    	String s;
	System.out.println("Enter The String of parenthesis whose validityis to be checked\n");
	s=sc.next();
	if(isValid(s))
	System.out.println("String is valid");
    	else
	System.out.println("String is not valid");
    }
}
