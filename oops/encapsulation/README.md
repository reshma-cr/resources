## 🔐 Encapsulation in C# — Top 50 Interview Questions (SDE 1/2)


### 1️⃣ Core Concept Questions

1. What is encapsulation in C#?
2. How is encapsulation different from abstraction?
3. Why is encapsulation important in real-world applications?
4. What are access modifiers in C#?
5. Difference between `private`, `protected`, `internal`, `public`, `protected internal`
6. What is the default access modifier for:
   - class
   - class members
7. Can you achieve encapsulation without properties?
8. What is data hiding?
9. How does encapsulation improve maintainability?
10. Can encapsulation exist without OOP?


### 2️⃣ Properties & Getters/Setters

11. What are properties in C#?
12. Difference between fields and properties
13. Why use properties instead of public fields?
14. What are auto-implemented properties?
15. What is a read-only property?
16. What is a write-only property? Is it used in practice?
17. Can you have private getters and public setters (or vice versa)?
18. What is `init` in C# properties?
19. How do you validate data using properties?
20. What happens if you remove setter from a property?


### 3️⃣ Access Control

21. How do you restrict access to class members?
22. When would you use `internal`?
23. Difference between `protected` and `private`
24. Can a class be private?
25. Can you access private members outside the class?
26. How does encapsulation work across assemblies?
27. What is `InternalsVisibleTo`?
28. How do access modifiers support encapsulation?
29. What happens if everything is public?
30. Can encapsulation be broken?


### 4️⃣ Real-world Scenario Questions

31. You have a `BankAccount` class — how would you ensure balance cannot be set directly?
32. How would you prevent negative salary in an `Employee` class?
33. How do you allow reading a value but restrict modification?
34. You have a config object — how do you make it immutable?
35. How would you expose only necessary fields in a large object?
36. How do you protect sensitive data like passwords?
37. You have a logging system — what should be hidden vs exposed?
38. In an API response model, what should be encapsulated?
39. How would you design a class where only methods can modify state?
40. How do you enforce business rules using encapsulation?


### 5️⃣ Advanced / Edge Case Questions

41. Difference between encapsulation and immutability
42. How does encapsulation relate to SOLID principles?
43. Can encapsulation impact performance?
44. What is defensive copying?
45. How do you encapsulate collections safely?
46. Why should you avoid exposing lists directly?
47. How do you encapsulate dependency injection?
48. How does encapsulation help in multi-threading?
49. Can reflection break encapsulation?
50. How do records in C# relate to encapsulation?
