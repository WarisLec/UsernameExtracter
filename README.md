
# **Java Programming Assignment: Username Processor**

### **Objective**  
Write a Java program to process usernames based on the following rules:  
1. If the username contains a period (`.`), return the uppercase initials of each part.  
   Example: `warisibrahim.h` → `WH`.  
2. If the username is a single word, return the uppercase initial of the word.  
   Example: `Warisibrahim` → `W`.

---

### **Instructions**  
1. Clone this repository to your local machine:  
   ```bash
   git clone <repository-url>
   ```
2. Open the `UsernameProcessor.java` file.  
3. Implement the `processUsername` method to process the usernames.  
4. Test your program using different inputs in the `main` method or with the provided test cases.  

---

### **Test Cases**  

| Input                | Expected Output |  
|----------------------|-----------------|  
| `warisibrahim.h`     | `WH`            |  
| `Warisibrahim`       | `W`             |  
| `john.doe`           | `JD`            |  
| `JaneDoe`            | `J`             |  
| `a.b`                | `AB`            |  

---

### **How to Submit**  
1. Save your changes and commit them:  
   ```bash
   git add .
   git commit -m "Completed assignment"
   git push origin main
   ```

2. Ensure your code passes all test cases before the deadline.  

---

### **Need Help?**  
If you have any questions, contact your instructor or refer to the Java documentation:  
[Java String Documentation](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)
