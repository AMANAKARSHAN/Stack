package Stack;
import java.util.*;

class Stack_Using_Queue{
	Queue<Integer> q1=new LinkedList<Integer>();
	Queue<Integer> q2=new LinkedList<Integer>();
	
	public void push1(int val) {
		q1.add(val);
	}
	
	public int pop1() {
		if(q1.isEmpty()) {
			return -1;
		}
		
		while(q1.size()>1) {
			q2.add(q1.remove());
		}
		
		int val=q1.remove();
		
		Queue<Integer> t = q1;
		q1=q2;
		q2=t;
		
	return val;	
	}
	
}



public class StackUsingQueue {
	
	public static void main(String[] args) {
		Stack_Using_Queue st = new Stack_Using_Queue();
		st.push1(4);
		st.push1(6);
		st.push1(8);
		st.push1(9);
		
		System.out.println("Popped Element : " + st.pop1());
		
		st.push1(38);
		st.push1(70);
		st.push1(17);
		
		System.out.println("Popped Element : " + st.pop1());
		System.out.println("Popped Element : " + st.pop1());
		
	}
}
