Download Link: https://assignmentchef.com/product/solved-java-code-named-package
<br>
JAVA code. named Package with data fields for wright in ounces, shipping method, and shipping cost. The shipping method is a character: A for air, T for truck, or M for mail. The Package class contains a constructor that requires arguments for weight and shipping method. The constructor calls a calculateCost() method that determines the shipping cost, based on the following table:

Weight (oz.)Air ($)Truck ($)Mail ($)1 to 8

9 to 16

17 and over

2.00

3.00

4.50

1.50

2.35

3.25

.50

1.50

2.15

The package class also contains a display() method that displays the values in all four fields. Have to create subclass named InsuredPackage that adds an insurance cost to the shipping cost, based on the following table:

Shipping Cost Before Insurance ($)Additional Cost ($)0 to 1.00

1.01 to 3.00

3.01 and over

2.45

3.95

5.55

a application named UsePackage that instantiates at least three objects of each type (Package and InsuredPackage) using a variety of weights and shipping method codes. Display the results for each Package and InsuredPackage. Save the files as Package.java, InsuredPackage.java, and UsePackage.java.

program has three classes – a static class, and two non-static classes. Use Package as the main program (static class), Package a base class, and InsuredPackage a derived class. Because InsuredPackage inherits every member from Package, there is no reason to define Package class members again in InsuredPackage. Both base and derived classes have calculateCost() methods with an insurance cost added to the derived class.