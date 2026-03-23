Here is a detailed breakdown of each component:
public: This is an access modifier that makes the main method accessible from anywhere, allowing the JVM (which is outside the program's class) to call it to start the program.
static: This keyword means the main method belongs to the class itself, rather than an instance (object) of the class. This is crucial because the JVM can call the method directly without needing to create an object first.
void: This is the method's return type, indicating that it does not return any value to the JVM after execution is complete.
main: This is the predefined name that the JVM looks for as the starting point of the program. Changing the name will result in a runtime error.
(String[] args): This is a parameter that accepts an array of String
