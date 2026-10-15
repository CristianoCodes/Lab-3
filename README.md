# To get to correct directory
cd /workspaces/Lab-3/my-app

# To compile main program
mvn clean compile

# To run tests
mvm test

# To run main program
mvn exec:java -Dexec.mainClass="p.PizzaStore"