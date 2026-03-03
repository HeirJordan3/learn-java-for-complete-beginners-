# Day 1: Introduction to Java

Welcome to Day 1 🎉

Today, you officially begin your journey into programming.

If you’ve never written code before, that’s completely okay. This course is built for complete beginners.

Take your time. Move slowly. Focus on understanding — not memorizing.

---

## ❓ Before You Start

You do **NOT** need:

* Any prior coding experience
* Advanced math skills
* A computer science background

All you need is curiosity and patience.

Every developer started exactly where you are right now.

---

# 🎯 Today’s Goals

By the end of today, you will:

* Understand what programming is
* Understand what Java is
* Install and run your first Java program
* Understand the structure of a basic Java program
* Write and run your first `"Hello, World!"` program

---

# 🧠 What is Programming?

Programming is giving instructions to a computer.

That’s it.

Computers are not smart.
They only follow instructions exactly as you write them.

Think of programming like writing a very detailed recipe.

If you tell the computer:

* Print something → it prints it
* Add numbers → it adds them
* Repeat something → it repeats it

Programming = Writing instructions in a language the computer understands.

---

# ☕ What is Java?

Java is a programming language.

Just like humans speak different languages (English, Spanish, French), computers understand different programming languages.

Java is one of the most widely used programming languages in the world.

It is used for:

* Enterprise software
* Banking systems
* Android applications
* Backend systems
* Large-scale platforms

Java is known for being:

* Structured
* Powerful
* Object-Oriented (you will learn this later)
* Widely used in professional environments

Learning Java builds strong programming fundamentals that transfer to many other languages.

---

# 🛠 Installing Java (JDK)

To write Java programs, you need the **Java Development Kit (JDK)**.

If you haven’t installed it yet:

1. Go to: [https://adoptium.net](https://adoptium.net)
2. Download the latest LTS version
3. Install it
4. Confirm installation by opening your terminal and running:

```
java -version
```

If you see a version number printed, you're ready.

---

# 🛠 Installing an IDE

An IDE (Integrated Development Environment) is where you write your code.

Recommended:

**IntelliJ IDEA (Community Edition – Free)**
[https://www.jetbrains.com/idea/download/](https://www.jetbrains.com/idea/download/)

Install it before continuing.

---

# ✍️ Your First Java Program

Now let’s write your first Java program.

Create a new file called:

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

Congratulations 🎉
You just wrote your first Java program.

---

# 🔍 Breaking It Down (Line by Line)

Let’s slow this down and understand what each part does.

---

## 1️⃣ public class Main

This creates a **class**.

For now, think of a class as a container that holds your program.

Important rule:
The file name must match the class name.

```
Main.java → class Main
```

---

## 2️⃣ public static void main(String[] args)

This is where Java starts running your program.

Every Java application needs this method to run.

Think of it as the **“Start” button** for your program.

---

## 3️⃣ System.out.println("Hello, World!");

This tells the computer:

Print the text inside the quotation marks.

Everything inside quotes `" "` is text.

`println` means:

Print this line and move to the next line.

---

# 🏗 Basic Structure of a Java Program

Every Java program follows this pattern:

```java
public class ClassName {

    public static void main(String[] args) {

        // Your instructions go here

    }
}
```

Think of it like this:

* Class → Container
* main() → Entry point
* Inside main → Instructions

Almost every Java program you write will follow this structure.

---

# ⚠️ Common Beginner Errors

Here are mistakes beginners often make:

❌ Forgetting a semicolon `;`
❌ Misspelling `System` (Java is case-sensitive)
❌ Naming the file differently than the class
❌ Removing curly braces `{ }`

If something doesn’t run, read the error message carefully.
Java usually tells you what went wrong.

---

# 🧠 Key Concepts from Today

You learned:

* Programming is writing instructions
* Java is a programming language
* Every Java program needs a class
* Execution begins inside `main()`
* We can print text using `System.out.println()`

That is a major first step.

---

# 🧪 Practice Exercise 1

Modify your program to print:

* Your name
* Your favorite food
* Your dream job

Example output:

```
My name is Jordan.
My favorite food is pizza.
My dream job is Software Engineer.
```

---

# 🧪 Practice Exercise 2

Print 5 lines about yourself.

Each line must use a separate `System.out.println()` statement.

---

# 🚀 Mini Challenge

Create a small “profile card” in the console.

Example output:

```
------------------
Name: Jordan
Age: 17
City: Newark
------------------
```

Try to recreate something similar.

Be creative.

---

# 🏁 End of Day Reflection

Today you:

* Installed Java
* Set up your development environment
* Wrote your first Java program
* Learned how Java programs are structured
* Printed output to the console

This may seem small — but this is exactly how every professional developer starts.

Tomorrow, we will learn how to store information using variables.

And that’s when your programs start becoming interactive and powerful.

---

