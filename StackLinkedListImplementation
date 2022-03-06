package Stack;

class Node{
	int data;
	Node next;
}

class StackLinkedList{
	
	Node top_ll;
	
	public Node getNewNode (int val){
		Node n = new Node();
		n.data=val;
		n.next=null;
		return n;
	}
	
	public void push_ll(int val) {
		if(top_ll==null) {
			top_ll=getNewNode(val);
			return;
		}
		
		Node t=getNewNode(val);
		t.next=top_ll;
		top_ll=t;
	}
	
	public int pop_ll() {
		if(top_ll==null) {
			System.out.println("Stack is empty");
			return Integer.MIN_VALUE;
		}
		
		Node t=top_ll;
		top_ll=top_ll.next;
		return t.data;
			
	}
	public int peek_ll() {
		if(top_ll==null) {
			System.out.println("Stack is empty");
			return Integer.MIN_VALUE;
		}
		
		return top_ll.data;
		
		
	}
	
	
	
}



public class StackLinkedListImplementation {
	public static void main(String[] args) {
		StackLinkedList a = new StackLinkedList();
		a.push_ll(24);
		a.push_ll(45);
		a.push_ll(5);
		a.push_ll(6);
		a.push_ll(34);
		a.push_ll(100);
		
		System.out.println(a.pop_ll());
		a.push_ll(35);
		a.push_ll(98);
		
		System.out.println(a.peek_ll());
		System.out.println(a.pop_ll());
		System.out.println(a.pop_ll());
		System.out.println(a.pop_ll());
		System.out.println(a.pop_ll());
		System.out.println(a.pop_ll());
		System.out.println(a.pop_ll());
		System.out.println(a.pop_ll());
		System.out.println(a.pop_ll());
	}

}
