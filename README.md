// Java-University-Labs

/**
 * This class will represent hockey players.
 * @author NOSHEEN
 */
public class Player {
	
	/*
	 * This is the constructor so we will be
	 * initializing the number variables here
	 */
	
	private String name;
	private String position;
	private int jerseyNum;
	

/*
 * Constructor called Player with the given name, position, and jersey Number
 * @param name is name
 * @param position is position
 * @param jerseyNum is jersey Number
 */
public Player(String name, String position, int jerseyNum) {
	this.name = name;
	this.position = position;
	this.jerseyNum = jerseyNum;
}

/*
 * Accessor method to get the name of the player
 * @return name of the player
 */

public String getName () {
	// Get the player's name.
	return name;
}

/*
 * Accessor method to get the position of the player
 * @return position of the player
 */

public String getPosition () {
	return position;
}

/*
 * Accessor method to get the jersey number of the player
 * @return JerseyNum of the player
 */

public int getJerseyNum () {
	return jerseyNum;
}

/*
 * Accessor method to set the name of the player
 * @param newName to set the name of the player to newName
 */

public void setName (String newName) {
	name = newName;
}

/*
 * Accessor method to set the position of the player
 * @param newPosition to set the position of the player to newPosition
 */

public void setPosition (String newPosition) {
	position = newPosition;
}

/*
 * Accessor method to set the jersey number of the player
 * @param newJerseyNum to set the JerseyNum of the player to newJerseyNum
 */

public void setJerseyNum (int newJerseyNum) {
	jerseyNum = newJerseyNum;
}


public String toString (){
	return this.name + ": #" + this.jerseyNum;
}


public boolean equals (Player other) {
	if (this.name.equals(other.name) && this.jerseyNum == other.jerseyNum) {
		return true;
	} else {
		return false;
	}
} 

}
