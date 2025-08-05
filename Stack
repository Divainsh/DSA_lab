public class StackExample {
    public static final int max = 4;
    int top;
    int[] arr = new int[max];

    StackExample() {
        top = -1;
    }

    public void push(int data) {
        if (top == max - 1) {
            System.out.println("Stack overflow");
            return;
        }
        top++;
        arr[top] = data;
        System.out.println("Pushed: " + data);
    }

    public int pop() {
        if (top < 0) {
            System.out.println("Stack underflow");
            return -1;
        }
        int value = arr[top];
        top--;
        System.out.println("Popped: " + value);
        return value;
    }

    public int peek() {
        if (top < 0) {
            System.out.println("Stack is empty");
            return -1;
        }
        System.out.println("Top element: " + arr[top]);
        return arr[top];
    }

    public void printStack() {
        if (top < 0) {
            System.out.println("Stack is empty");
            return;
        }
        System.out.print("Stack elements: ");
        for (int i = 0; i <= top; i++) {
            System.out.print(arr[i] + " ");
        }
        System.out.println();
    }

    public static void main(String[] args) {
        StackExample mystack = new StackExample();

        mystack.push(1);
        mystack.push(2);
        mystack.push(3);
        mystack.push(4);
        mystack.push(5);

        mystack.printStack();

        mystack.peek();
        mystack.pop();
        mystack.pop();
        mystack.pop();
        mystack.pop();
        mystack.pop();
    }
}
