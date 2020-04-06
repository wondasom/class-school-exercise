# classSchool
INTERMEDIATE JAVASCRIPT Exercise - Class

[Instruction]<br>
We need to create classes for primary, middle, and high schools. <br>Because these classes share properties and methods, each will inherit from a parent School class. <br>Our parent and three child classes have the following properties, getters, setters, and methods:<br><br>

School<br>
Properties: name (string), level (one of three strings: 'primary', 'middle', or 'high'), and numberOfStudents (number)<br>
Getters: all properties have getters<br>
Setters: the numberOfStudents property has a setter<br>
Methods: .quickFacts() and .pickSubstituteTeacher() (this is a static method)<br><br>
Primary<br>
Includes everything in the School class, plus one additional property<br>
Properties: pickupPolicy (string)<br><br>
Middle<br>
Does not include any additional properties or methods<br><br>
High<br>
Includes everything in the School class, plus one additional property<br>
Properties: sportsTeams (array of strings)<br>
