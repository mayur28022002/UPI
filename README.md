package Polymorphism;

public class UPI extends Payment {
	void pay(double amount) {
		System.out.println("Payment of "+amount+" done by UPI");
	}

}
package Polymorphism;

public class NetBanking extends Payment {
  void pay(double amount) {
	  System.out.println("payment is done "+amount+" with netbanking...");
  }
}
package Polymorphism;

public class DebitCard extends Payment {
public void pay(double amount) {
	System.out.println("Payment is done "+amount+" with Debit card...");
}
}
