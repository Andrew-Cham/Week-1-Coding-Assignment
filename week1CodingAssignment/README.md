# Week-1-Coding-Assignment
public class App {

	public static void main(String[] args) {
		// Week 1 Coding Assignment
		double itemPrice = 7.77;
		int ammountOfMoneyInWallet = 20;
		
		//This is where he said how old he is and how many friends he have made in the U.S.
		double newAmmountOfMoney = ammountOfMoneyInWallet - itemPrice;
		int numberOfFriends = 3;
		int myAge = 22;
		
		//This is the part where Andrew said his full name.
		String firstName = "Andrew";
		String lastName = "Cham";
		char middleInitial = 'C';
		
		String fullName = firstName+ " " + middleInitial + " " + lastName;
		
		
		System.out.println("After spending $7.77 I have exactly $" + newAmmountOfMoney + " " +  "left in my Wallet.");
		System.out.println("I am" + " " + myAge + " " + "years old and I've made" + " " + numberOfFriends + " " + "friends since I came to the U.S.");
		System.out.println("My full name is" + " " + fullName);
		
		
		
