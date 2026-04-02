## ⚙️ Inheritance in C# — Top 50 Interview Questions (SDE 1/2)


### 1️⃣ Core Concepts

1. What is inheritance in C#? Why is it used?
2. What are the different types of inheritance supported in C#?
3. Why does C# not support multiple inheritance with classes?
4. How does inheritance promote code reusability?
5. What is the difference between inheritance and composition?
6. What happens when a derived class does not call a base constructor?
7. What is the default constructor behavior in inheritance?
8. Can a class inherit from multiple interfaces and one class?
9. What is the difference between `protected` and `private` in inheritance?
10. What is the order of constructor execution in inheritance?


### 2️⃣ Method Overriding & Polymorphism

11. What is method overriding in C#?
12. Difference between `virtual`, `override`, and `new`
13. What happens if you forget `override` keyword?
14. What is runtime polymorphism?
15. Can you override a non-virtual method?
16. What is method hiding? When should you use `new`?
17. What happens when base reference calls overridden method?
18. Can static methods be overridden?
19. What is the difference between compile-time and runtime binding?
20. How does method dispatch work in inheritance?


### 3️⃣ Constructors & Base Keyword

21. How do you call a base class constructor?
22. What is the use of `base` keyword?
23. What happens if base constructor has parameters but child doesn't call it?
24. Can constructors be inherited?
25. What is constructor chaining?
26. Can you call base class methods using `base`?
27. When should you use `base` vs `this`?
28. Why is base constructor important in dependency injection?
29. Can a derived class skip base constructor?
30. What happens if base constructor throws exception?


### 4️⃣ Real-World Design Scenarios

31. Design a `Vehicle → Car → ElectricCar` hierarchy. What should go where?
32. When should you use inheritance vs interfaces in a payment system?
33. You have `Employee → Manager → Director`. Where do you put salary logic?
34. Why is deep inheritance hierarchy bad?
35. Why do ASP.NET controllers use inheritance?
36. How would you design a logging system using inheritance?
37. You inherit a class but only need partial functionality — what should you do?
38. Why is "favor composition over inheritance" recommended?
39. How would you model a UI component system using inheritance?
40. Should repository pattern use inheritance?


### 5️⃣ Edge Cases & Tricky Questions

41. What happens if both base and derived class have same method (no override)?
42. What happens if base reference points to derived object?
43. Can a sealed class be inherited?
44. What is a sealed method and why use it?
45. Can abstract class have constructors?
46. Can abstract methods have implementation?
47. Can you inherit from a struct?
48. What happens if base class method is private?
49. What is the diamond problem and why doesn't C# have it?
50. Can you cast base object to derived class safely?
