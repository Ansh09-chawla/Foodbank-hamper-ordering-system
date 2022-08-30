-------------------------------------------------
How to use the HamperOrderingSystem Java Program.
-------------------------------------------------

1. Compile the program:
	- Add a "lib" folder containing (hamcrest-core-1.3.jar, junit-4.13.2.jar, and mysql-connector-java-8.0.23.jar) to the directory containing edu/ucalgary/ensf409.
	
	- In command-line, navigate to the working directory; 
	  
	- In the command-line, execute the following command: javac -cp .;lib/mysql-connector-java-8.0.23.jar edu/ucalgary/ensf409/HamperOrderingSystem.java
	
2. Run the program:
	- In command-line, execute the following command to launch the program: java -cp .;lib/mysql-connector-java-8.0.23.jar edu/ucalgary/ensf409/HamperOrderingSystem

3. How to use the program:
	a) Fill out the family information fields (Number of Males, Number of Females, Number of Children Over8, and Number of Children Under 8),
		for whom the Hamper is being created for.
	b) Click the "Save family information" button to add the Hamper to the current Order.
	c) To add multiple Hampers to an Order, repeat steps (a) and (b).
	d) Click the "Submit order" button when all Hampers are added to the Order.
	e) An OrderSummary output file will be generated and can be found in the directory containing the ENSF409_Project_Group81_FinalPackage directory.
	f) To complete another Order, repeat steps (a) - (e).
	g) To close the program, click the (X) at the top-right corner of the program window.
	
4. How to test the program with JUnit/Hamcrest:
	- In command-line, navigate to the directory containing the following package;
	  (ENSF409_Project_Group81_FinalPackage/edu/ucalgary/ensf409)
	  
	- In command-line, execute the following commands sequentially:
		javac -cp .;lib/hamcrest-core-1.3.jar;lib/junit-4.13.2.jar edu/ucalgary/ensf409/*.java
		java -cp .;lib/hamcrest-core-1.3.jar;lib/junit-4.13.2.jar org.junit.runner.JUnitCore edu.ucalgary.ensf409.TestDesign