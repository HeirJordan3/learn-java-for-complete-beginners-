# Day 1: Introduction to Java

Welcome to Day 1! 

Today, you are officially starting your journey into programming.

Do not worry if you have never written code before. This lesson is built for complete beginners.

---

# Today’s Goal

By the end of today, you will:

* Understand what programming is
* Understand what Java is
* Install and run your first Java program
* Understand the structure of a basic Java program
* Write and run your first "Hello, World!" program

---

# What is Programming?

Programming is giving instructions to a computer.

That’s it.

Computers are not smart.
They only follow instructions exactly as you write them.

Think of programming like writing a very detailed recipe.

If you tell the computer:

* Print something → it prints it.
* Add numbers → it adds them.
* Repeat something → it repeats it.

Programming = Writing instructions in a language the computer understands.

---

# What is Java?

Java is a programming language.

Just like humans speak different languages (English, Spanish, French), computers understand different programming languages.

Java is one of the most popular programming languages in the world.

It is used for:

* Websites
* Android apps
* Banking systems
* Large enterprise software
* Backend systems
* Desktop applications

Java is known for being:

* Structured
* Powerful
* Used in large companies
* Object-Oriented (we will learn this later)

---

# Step 1: Install Java (JDK)

To write Java, you need something called the JDK (Java Development Kit).

If you haven’t installed it yet:

1. Go to: [https://adoptium.net](https://adoptium.net)
2. Download the latest LTS version
3. Install it
4. Confirm installation by running this in your terminal:

```
java -version
```

If it prints a version number, you're ready.

---

# Step 2: Install an IDE

An IDE is a program where you write code.

Recommended:

* IntelliJ IDEA (Community Edition – Free)

Download:
[https://www.jetbrains.com/idea/download/](https://www.jetbrains.com/idea/download/)

---

# Your First Java Program

Now let’s write your first program.

Create a new Java file called:

```
Main.java
```

Add this code:

```java
public class Main {
    public static void main(String[] args) {

        System.out.println("Hello, World!");

    }
}
```

Run the program.

You should see:

```
Hello, World!
```

Congratulations 
You just wrote your first Java program.

---

# Breaking It Down (Line by Line)

Let’s slow this down.

## public class Main

This creates something called a class.

For now, think of a class as a container that holds your program.

The file name must match the class name.

Main.java → class Main

---

## public static void main(String[] args)

This is where Java starts running your program.

Every Java program needs this line to run.

Think of it like the “Start” button.

---

## System.out.println("Hello, World!");

This tells the computer:

Print the text inside the quotes.

Everything inside quotation marks is text.

println means:

“Print this line and move to the next line.”

---

# Key Concepts from Today

You learned:

* Programming is writing instructions
* Java is a programming language
* A Java program must have a class
* Every program starts in main()
* We can print text using System.out.println()

That is a BIG first step.

---

# Practice Exercise 1

Modify your program to print:

* Your name
* Your favorite food
* Your dream job

Example:

```
My name is Jordan.
My favorite food is pizza.
My dream job is Software Engineer.
```

---

# Practice Exercise 2

Print 5 lines about yourself.

Each line should use a separate `System.out.println()` statement.

---

# Mini Challenge

Can you print a small “profile card”?

Example output:

```
------------------
Name: Jordan
Age: 17
City: Newark
------------------
```

Try to recreate something like this.

---

# End of Day Reflection

You just:

* Installed Java
* Wrote your first program
* Learned how Java programs are structured
* Printed output to the console

That may seem small, but this is how every developer starts.

Tomorrow, we learn how to store information using variables.

And that’s when things start getting powerful.


