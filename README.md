// Java-University-Labs

public class TestLab {

	public static void main(String[] args) {
		
		// Create a Player object
		
		Player p1 = new Player("Nosheen", "catcher", 3);
		System.out.println(p1.getName());
		System.out.println(p1.getPosition());
		System.out.println(p1.getJerseyNum());
		
		p1.setName("Soha");
		p1.setPosition("defence");
		p1.setJerseyNum(4);
		
		System.out.println(p1.getName());
		System.out.println(p1.getPosition());
		System.out.println(p1.getJerseyNum());
		
		System.out.println(p1);
		
		// Create another Player object
		
		Player p2 = new Player ("Soha", "defence", 4);
		
		if (p1.equals(p2)) {
			System.out.println("Same player");
		} else {
			System.out.println("Different player");
		}
	}

}
