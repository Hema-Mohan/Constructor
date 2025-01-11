# Constructor
Class Customer {
    private String name;
    private long accountNumber;
    private double balance;

    Customer(String name, long accountNumber, double balance) {
        this.name = name;
        this.accountNumber = accountNumber;
        this.balance = balance;
    }

    public void displayDetails() {
        System.out.println("Customer Name: " + name);
        System.out.println("Account Number: " + accountNumber);
        System.out.println("Account Balance: " + balance);
    }

    public static void main(String[] args) {
        Customer c1 = new Customer("Kaviya", 12345, 25000.35);
        Customer c2 = new Customer("Ramya", 14356, 15000.60);

        System.out.println("\n--- Customer 1 ---");
        c1.displayDetails();

        System.out.println("\n--- Customer 2 ---");
        c2.displayDetails();
    }
}

OUTPUT:

--- Customer 1 ---
Customer Name: Kaviya
Account Number: 12345
Account Balance: 25000.35

--- Customer 2 ---
Customer Name: Ramya
Account Number: 14356
Account Balance: 15000.6
