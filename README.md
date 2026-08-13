# Week-1
Intro to project
public class Main {

    public static void main(String[] args) {

        Product p1 = new Product(1, "Laptop", 55000);
        Product p2 = new Product(2, "Mobile", 25000);
        Product p3 = new Product(3, "Headphones", 2000);

        System.out.println("===== ONLINE SHOPPING =====");

        p1.display();
        p2.display();
        p3.display();
    }
}

class Product {

    int id;
    String name;
    double price;

    Product(int id, String name, double price) {
        this.id = id;
        this.name = name;
        this.price = price;
    }

    void display() {
        System.out.println(
            id + ". " + name + " - Rs." + price
        );
    }
}
