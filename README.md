# OOP Assignment - Inky Class

## Overview

This is the first assignment of the Object-Oriented Programming (OOP) module. The task was to create a simple Java class, `Inky`, which includes two constructors. We also learned the process of creating a GitHub repository and pushing our files to it.

## Project Details

### Class: `Inky`

The `Inky` class demonstrates basic object-oriented concepts such as constructors and method calls. The class contains two constructors:

1. **Constructor 1:**
   - Takes one parameter (`pinky` of type `String`) and prints its value.
   
2. **Constructor 2:**
   - Takes three parameters (`pinky`, `blinky`, `rinky` of type `String`) and prints several combinations of these parameters.

### Code Explanation:

```java
// Class Inky
public class Inky {

    // Constructor of the class Inky
    public Inky(String pinky){
        System.out.println(pinky);
    }

    // Constructor 2
    public Inky(String pinky, String blinky, String rinky){
        System.out.println(blinky + " " + pinky);
        System.out.println(pinky + " " + rinky);
        System.out.println(blinky + " " + pinky + " " + rinky);
        System.out.println("This is for check");
    }

    // Main method
    public static void main(String args []){
        String pinky = "Donky";
        String blinky = "Pinky";
        String rinky = "Monkey";
        
        // Creating objects of Inky class
        Inky ponky = new Inky(pinky);
        Inky ponky2 = new Inky(pinky, blinky, rinky);
    }
}
```

### Main Features:

- **Constructor Overloading:** We demonstrated constructor overloading with two constructors in the `Inky` class. One accepts a single parameter, while the other accepts three.
- **Printing Combinations:** The second constructor prints various combinations of the input strings, showcasing how parameters can be manipulated in Java.
- **Basic Output:** The program outputs different combinations of input strings for demonstration purposes.

### Example Output:

```
Donky
Pinky Donky
Donky Monkey
Pinky Donky Monkey
This is for check
```

## GitHub Repository

In addition to the Java coding task, we also learned how to create a GitHub repository and push files to it. This included:
- **Creating a new GitHub repository** for the assignment.
- **Pushing the files** from our local machine to the GitHub repository using Git commands.

## Steps for Pushing Files to GitHub:

1. **Initialize a Git Repository:**
   ```bash
   git init
   ```
2. **Add Files to the Staging Area:**
   ```bash
   git add .
   ```
3. **Commit the Changes:**
   ```bash
   git commit -m "Initial commit"
   ```
4. **Connect to the GitHub Repository:**
   ```bash
   git remote add origin <repository-url>
   ```
5. **Push the Changes to GitHub:**
   ```bash
   git push -u origin master
   ```

## Learning Outcomes

- Gained hands-on experience in writing Java code with constructors.
- Learned the importance of constructor overloading and how it works.
- Familiarized ourselves with basic Git and GitHub operations, including repository creation and file pushing.

## Conclusion

This assignment was a great introduction to OOP concepts, particularly constructors and object instantiation. We also gained valuable experience in version control with Git and GitHub.
