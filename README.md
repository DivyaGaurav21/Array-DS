//@(1)@ function to take input element in array by user

	public static int[] takeInputArray() {
		System.out.println("Enter the size of array");
	Scanner scn=new Scanner(System.in);
	int n=scn.nextInt();
	int arr[]=new int[n];
	System.out.println("Enter the element in Array");
	for(int i=0; i<arr.length; i++) {
		arr[i]=scn.nextInt();
	}
	return arr;
	}
	
