# CUS1166G1 (Tahmidul, Goden, Andy, Justin, David, Kevin)
Date: Febuary 7 2023
Project Milestone #2
Description: Our objective for this Milestone is to start implementing vehicular cloud console by using GUI. The program must interact with the Users information which include the following: Determine if it is a Client who wants to submit a job or an Owner, who wants to rent out her/his car by selecting an option on the GUI panel. Enter the information via GUI. We also must include what information each user (Client, Owner) must store to be collected. The important part to remember is that, multiple users who is part of implementing the system should have access to the information. 

import javax.swing.*;
public class GUI {

	public static void main(String[] args) 
	{
		JFrame frame = new JFrame();
		frame.setSize(300, 400);
		frame.setTitle("Vehicular Cloud Real Time System");
		frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		JButton button1 = new JButton("Click me!");
		frame.add(button1);
		frame.setVisible(true);
	}

}
