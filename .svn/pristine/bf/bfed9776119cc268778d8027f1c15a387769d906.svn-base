package in.ashokit.entity;

import javax.persistence.Column;
import javax.persistence.Entity;
import javax.persistence.Id;
import javax.persistence.Table;

@Entity
@Table(name = "CRICKET_PLAYERS")
public class Player {
	
	@Id 
	@Column(name = "Player_ID")
	private Integer plyerId;
	
	@Column(name = "Player_NAMEID")
	private String playerName;
	
	public Integer getPlyerId() {
		return plyerId;
	}

	public void setPlyerId(Integer plyerId) {
		this.plyerId = plyerId;
	}

	@Override
	public String toString() {
		return "Player [plyerId=" + plyerId + ", playerName=" + playerName + ", playerAge=" + playerAge + ", location="
				+ location + "]";
	}

	public String getPlayerName() {
		return playerName;
	}

	public void setPlayerName(String playerName) {
		this.playerName = playerName;
	}

	public Integer getPlayerAge() {
		return playerAge;
	}

	public void setPlayerAge(Integer playerAge) {
		this.playerAge = playerAge;
	}

	public String getLocation() {
		return location;
	}

	public void setLocation(String location) {
		this.location = location;
	}

	@Column(name = "Player_AGE")
	private Integer playerAge;
	
	private String location;

}
