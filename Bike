//Super Keyword


class Vehicle {
	int speed = 50;	 
	Vehicle() {
		System.out.println("Vehicle is created.");
	}
}

class Bike extends Vehicle {

	int speed = 100;
	Bike() {
		super();
		System.out.println("Bike is created.");
	}
	Bike(int speed) {
		super();
		System.out.println("New Bike is created.");
		this.speed = speed;
	}
	void display() {
		System.out.println("Vehicle speed : " + super.speed);
		System.out.println("Bike's speed : " + speed);
	}

	public static void main(String args[]) {
		Bike objBike = new Bike();
		objBike.display();

		System.out.println("--------- new Bike Details ----------");
		
		Bike objBikeNew = new Bike(75);
		objBikeNew.display();
	}
}
