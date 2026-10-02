Table of Contents
- [Vocab](#vocab)
- [Important blocks](#important-blocks)
- [On the AP Exam](#on-the-ap-exam)
- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)
  - [Headings](#headings)
  - [Text Formatting](#text-formatting)







## Vocab
<details>
  <summary>Abstraction</summary>
    The most fundamental idea in computer science, giving a name to something in a program to make it more readable.
</details>

<details>
  <summary>Procedural abstraction</summary>
    Using a procedure to name an idea, ex. the procedure "who" to the idea of picking an item from the list of people or cats.
</details>

<details>
  <summary>Transparency</summary>
  The transparency of an image is how much you can see what's behind it. For example, here is the Alonzo sprite shown with three different transparencies (which have been set using the ghost effect block).<img width="480" height="237" alt="transparency2" src="https://github.com/user-attachments/assets/57240fcf-fe01-4c66-b337-52dfbc4a5b01" />
</details>

<details>
  <summary>Expression</summary>
  An expression is a either a constant value (such as "4" or "winter") or a call to a reporter block including its inputs (such as<img width="201" height="33" alt="5+(4x3)" src="https://github.com/user-attachments/assets/59f88d10-4a88-42a7-8162-144fabd129c4" />,
<img width="85" height="22" alt="number" src="https://github.com/user-attachments/assets/c8e4e12a-ebe5-4726-ab61-72561bfe9be9" />,
  or<img width="351" height="28" alt="join-who-doeswhat-who" src="https://github.com/user-attachments/assets/578471d0-56d1-4039-9d7e-6747fb230474" /> ).
Expressions are evaluated to produce a single value (a value can be a number, a string, a sprite, a costume, a script, a list—anything). For example, <img width="201" height="33" alt="5+(4x3)" src="https://github.com/user-attachments/assets/1b47ef84-20fc-42c8-886b-9798d5466a84" /> will be evaluated to 17.
</details>

<details>
  <summary>Procedures</summary>
  A procedure is a named sequence of instructions that may take inputs and may report a value. Some languages call procedures methods or functions. Here are two types of procedures you have seen in Snap!
</details>

<details>
  <summary>Reporters</summary>
  Reporters have an oval shape. They report a value.
  <img width="212" height="27" alt="pick-random-empty-full-size" src="https://github.com/user-attachments/assets/564a2a9b-f412-4178-b17d-a0ee8cd876ca" />
</details>

<details>
  <summary>Commands</summary>
  Commands have a jigsaw puzzle shape. They tell the computer to do something without reporting a value.
  <img width="147" height="37" alt="broadcast" src="https://github.com/user-attachments/assets/b9680ba7-70df-42dd-99b6-f0aa5413e91b" />
</details>

<details>
  <summary>List</summary>
  A list is an ordered sequence of items. You've seen this example:
  <img width="496" height="169" alt="list-from-who-result" src="https://github.com/user-attachments/assets/d65a6b9b-79be-4733-b01a-a9da6cffbbc3" />
</details>

<details>
  <summary>Strings</summary>
  The items of this list are strings. A string is a sequence of characters (letters, digits, punctuation, etc.). A substring is just a piece of some existing string. For example, "Hanna," "anna", and "nnah" are each substrings of the string "Hannah." (The empty string as well as the original string are both also substrings.)
</details>

<details>
  <summary>Concatenation</summary>
  To concatenate strings means to make a bigger string by connecting two or more smaller strings. In Snap!, the <img width="116" height="27" alt="join()()" src="https://github.com/user-attachments/assets/8cfc2d42-c1fd-4343-8bd5-0800d4d37c50" />block lets you concatenate strings.
</details>

<details>
 <summary>Algorithm</summary>
  An algorithm is a sequence of steps that are usually performed by a computer. The algorithm doesn't have to be written in any particular programming language or even in a programming language at all; you can write your algorithm in English or any other human language.
</details>

<details>
  <summary>Pseudocode</summary>
  Some people call an algorithm written in human language pseudocode. Once you know the steps that the computer will take, you can code your algorithm in the programming language of your choice.
What's the purpose of "pseudocode"? Why write an algorithm vaguely in English when you could write it precisely in Snap!? If you were programming in a punctuation-heavy language, designing your program in pseudocode would help you focus on the important ideas instead of on details like quotation marks and semicolons. But pseudocode isn't as necessary with a language like Snap!, and pseudocode can make it easy for you to fall into wishful thinking about what the computer is capable of (such as writing "Pick tomorrow's winning lottery numbers" or "Here's the melody; write the harmony").
</details>

<details>
  <summary>Parameter</summary>
  A parameter (or formal parameter) is the input name, such as number of branches. The input name is set in the block definition. It never changes.<img width="600" height="223" alt="example-parameter" src="https://github.com/user-attachments/assets/c197a8f3-ea99-4fc7-a75d-575a78ac424d" />
</details>

<details>
  <summary>Argument</summary>
  An argument (or actual argument) is the input value, such as 6 for a hexagonal pinwheel. The input value is given each time the block is run; it can be a different value each time.<img width="331" height="36" alt="example-argument" src="https://github.com/user-attachments/assets/848c1d43-6d35-4d8b-8b2e-09871909e62f" />We use the word "input" both for parameters (input names) and for arguments (input values).
</details>

<details>
  <summary>Personally Identifiable Information (PII)</summary>
  Information that can identify you as an individual is called personally identifiable information (PII). It includes details that could reveal who you are—such as your Social Security number, age, race, phone number(s), medical information, financial information, or biometric data like a thumbprint or face scan.
</details>

<details>
  <summary>Values</summary>
  Expressions are evaluated to produce a single value (a value can be a number, a string, a sprite, a costume, a script, a list—anything). For example, <img width="201" height="33" alt="5+(4x3)" src="https://github.com/user-attachments/assets/62b6c68c-05d8-4465-a225-166473b5c791" />will be evaluated to 17.
</details>

<details>
  <summary>Iteration</summary>
  Computer scientists describe a repeating program structure as looping, repetition, or iteration.
The code can be repeated forever, a specific number of times (such as when using repeat), or until something specific happens (such as when using repeat until as you'll see in Lab 5).<img width="324" height="121" alt="move-tiny-no-hat" src="https://github.com/user-attachments/assets/472b458c-685a-49b2-8192-59f57dcbddf8" />
<img width="209" height="115" alt="repeat-4(move-100-turn-right-90)" src="https://github.com/user-attachments/assets/1b7250af-b5c4-447b-aef1-6cca5bfb177e" />
</details>

<details>
  <summary>Sound Sensor</summary>
  A sensor that outputs an analog signal based on the amount of ambient sound present. It is programmed using a value between 0 and 100, where 0 is the softest sound that can be detected and 100 is the loudest.
</details>

<details>
  <summary>Position Servo</summary>
   Is a motor will turn to a specific angle from 0 to 270 degrees.
</details>

<details>
  <summary>Rotation Servo</summary>
  Is a motor that will rotate continuously until turned off. Servo motors are very precise motors.
</details>

<details>
  <summary>Light Sensor</summary>
  Is a sensor that detects ambient light. Light Sensors can be either digital or analog. The Light Sensor in your ITEEA ExCITE Robotics System is Digital and will report a value of 1 or 0 (on or off).
</details>

<details>
  <summary>Algorithm</summary>
  A finite set of instructions used to accomplish a task. Ex.	The instructions that move a robot to its final position.
</details>

<details>
  <summary>Sequencing</summary>
  	Statements execute in the order they appear unless the flow of control changes. EX. ROTATE_LEFT() followed by MOVE_FORWARD()
</details>

<details>
  <summary>Selection</summary>
  	Uses a condition to determine which part of an algorithm is executed. Ex.IF (x < 3)
</details>

<details>
  <summary>Iteration</summary>
  Repeating a set of instructions in an algorithm. Ex. 	REPEAT 3 TIMES
</details>

<details>
  <summary>Variable</summary>
  	A named value that can change while a program runs. Ex. i in i ← 3
</details>

<details>
  <summary>Assignment</summary>
  Stores a value in a variable. Ex. i ← 3
</details>

<details>
  <summary>Expression</summary>
  A combination of values, variables, and operators that evaluates to a value. Ex.i - 1
</details>

<details>
  <summary>Condition</summary>
  	An expression that evaluates to either true or false. Ex. x < 3
</details>


<details>
  <summary>Boolean</summary>
  A value that is either true or false. Ex. The result of x ≤ 1
</details>

<details>
  <summary>Relational Operator</summary>
  Compares two values and produces a Boolean result. Ex. <, >, ≤, ≥, =, ≠
</details>

<details>
  <summary>Procedure</summary>
  A named group of programming instructions that performs a task. Ex. 	PROCEDURE FancyMove(x)
</details>

<details>
  <summary>Procedure Call</summary>
  Tells the program to execute a procedure. Ex.	FancyMove(i)
</details>

<details>
  <summary>Parameter</summary>
  A variable in a procedure definition that receives a value when the procedure is called. Ex. x in PROCEDURE FancyMove(x)
</details>

<details>
  <summary>Flow of Control</summary>
  The order in which statements in a program are executed. Ex. An IF determines which branch runs.
</details>

<details>
  <summary>Nested Selection</summary>
  A selection statement contained inside another selection statement. Ex.	An IF inside an ELSE block.
</details>

<details>
  <summary>Nested Iteration</summary>
  An iteration statement contained inside another iteration statement. Ex. 	REPEAT i TIMES inside REPEAT 3 TIMES
</details>

<details>
  <summary> Variable</summary>
  A variable is like a labeled box that can hold one value at a time, such as one word, one costume, or one list (which can contain many things). You can look at what's inside as many times as you want.
</details>

<details>
  <summary>Local Variable</summary>
  A local variable can be set or used only in the environment in which it is defined. This term includes inputs to procedures and variables created by the for or script variables block.
</details>

<details>
  <summary>Predicate</summary>
  A predicate is a hexagon-shaped reporter that asks a true/false question such as these examples:<img width="201" height="44" alt="6-gt-7-reporting-false" src="https://github.com/user-attachments/assets/ccf713b1-1996-4169-bf8a-ea5d29f301a7" /><img width="201" height="44" alt="8-gt-7-reporting-true" src="https://github.com/user-attachments/assets/497ac1f3-d423-4e65-9c47-f9fecf9b08d2" />
</details>

<details>
  <summary> Boolean value</summary>
  Predicates report a Boolean value (either<img width="104" height="29" alt="true" src="https://github.com/user-attachments/assets/5be3ccce-8086-4a1c-8a1b-ed511121fd79" /> or<img width="104" height="29" alt="false" src="https://github.com/user-attachments/assets/3a66b3d9-8209-4c7e-8ec7-9b92a57eb737" /> ).
</details>

<details>
  <summary>If else Block</summary>
  The if and if-else blocks are called conditionals because they control the code based on a true-or-false condition.
</details>

<details>
  <summary>Global Variable</summary>
  A global variable is a variable that is usable by all scripts in the program.
</details>










## Important Blocks
<details>
  <summary>broadcast</summary>
     Sends a message to all the sprites. To set the message, click the down arrow and select "new..."
</details>

<details>
  <summary>when I receive</summary>
     (Click help on the block to learned more about it in order to complete this definition)
</details>





## On the AP Exam
<img width="1006" height="120" alt="image-2" src="https://github.com/user-attachments/assets/17476633-14c8-4c2e-af40-3f61c8655215" />

  - Many languages (and the AP CS Principles Exam) use return instead of report as the name of the command to give a value back at the end of a function call.
  - The exam uses "value of a procedure" to mean the value the procedure returns when called. For example, "the value of double(5)" means 10.
  - There is nothing exactly like <img width="127" height="37" alt="say-gossip" src="https://github.com/user-attachments/assets/97f534df-fb9c-41ca-bc51-8f0744a7458b" /> or <img width="240" height="37" alt="say-gossip-for-3-secs" src="https://github.com/user-attachments/assets/2d1ce2b6-c8d3-4f30-a1e7-603ef933d7a8" /> on the AP Exam because they don't have sprites and speech balloons, but their way of showing this text to the user is DISPLAY(gossip()) if it's written as text or <img width="130" height="27" alt="display(gossip)" src="https://github.com/user-attachments/assets/e7447dca-3e7c-4dc3-b410-87f8668006c2" /> if it's shown as blocks.
You won't have to be able to write code in this notation on the AP exam. You just have to be able to read it so you can answer questions about it.
  - The procedure <img width="263" height="105" alt="double-block-definition" src="https://github.com/user-attachments/assets/5d75162c-e179-4e1a-b317-ea83c5c00a80" /> would be written as 
PROCEDURE double(x)
{
    RETURN(2 * x)
}
or <img width="163" height="83" alt="double-blocktran" src="https://github.com/user-attachments/assets/82c3717e-0c16-4b7a-adc9-d49cfa941549" />Many languages (and the AP CS Principles Exam) use return instead of report as the name of the command to give a value back at the end of a function call.
The exam uses "value of a procedure" to mean the value the procedure returns when called. For example, "the value of double(5)" means 10.

  -The expression <img width="235" height="27" alt="pick-random-1-to-10-full-size" src="https://github.com/user-attachments/assets/ce325e60-c284-46db-b2a1-37be9e5e3548" />would be written as RANDOM(1, 10) or <img width="92" height="16" alt="random-blocktran" src="https://github.com/user-attachments/assets/d5acdf2f-548a-413b-aea5-640b73024047" /> Every time you run this code, you will get a different random number between 1 and 10.

  -The procedure definition for the custom pinwheel command<img width="450" height="222" alt="pinwheel-definition" src="https://github.com/user-attachments/assets/8db7122d-5832-48e4-85be-6bcc42bd9420" /> Would be written as<img width="377" height="180" alt="pinwheel-blocktran" src="https://github.com/user-attachments/assets/7ca3dc6d-d9e5-4bc2-8179-5d61d2e687a5" />

-The procedures move() and turn_clockwise() aren't built in to the AP's language so they are written in lower case like other programmer-defined procedures.
Notice that the hat block, <img width="408" height="75" alt="pinwheel-hat-block" src="https://github.com/user-attachments/assets/700f9786-bfa5-468b-ae32-938f8a5fd25b" /> would be written as PROCEDURE pinwheel(numberOfBranches). The word PROCEDURE tells you that that line of the code is like a hat block; the variable name in the parentheses on that line is the input that the procedure takes.

  -This instruction <img width="390" height="36" alt="U1L3-PinwheelwithInputs1" src="https://github.com/user-attachments/assets/e987cff3-b8f7-4072-8a76-d6381cf06c9f" /> would be written as Pinwheel(6, 80, 20) or You may hear people use the term "pseudocode" to refer to this pseudo-language used on the AP CS Principles exam, but it's not pseudocode. Pseudocode isn't a programming language at all, it's the use of normal human language to describe an algorithm.

  - <img width="214" height="37" alt="set-secret-number-to-7" src="https://github.com/user-attachments/assets/f9dc79a1-d9fc-4943-8f0e-3367545658f7" />would be written as <img width="124" height="18" alt="secret-number-assignment-blocktran" src="https://github.com/user-attachments/assets/14741f4a-83aa-4847-a63f-004834a72d8e" />.

  - The code <img width="384" height="69" alt="chicken-script" src="https://github.com/user-attachments/assets/2d39c374-a994-4c05-ad93-fe8c4d121a50" />would be written as <img width="341" height="53" alt="chicken-script-blocktran" src="https://github.com/user-attachments/assets/5886e978-bcec-493a-88fc-192420e9af98" />Notice that the procedure INPUT() accepts the value from the user and returns that input value, which is then assigned to the variable userResponse with the ← syntax. In Snap!, this is just like how answer accepts a value from the user and reports it, and that report is what the computer sets the variable user response to.

  - <img width="210" height="37" alt="change-score-by-1" src="https://github.com/user-attachments/assets/92ab173d-952b-4f1d-b533-22eac6382355" />(which means <img width="288" height="43" alt="set-score-to-score-plus-one" src="https://github.com/user-attachments/assets/cc81427b-7a71-49f4-9f81-d900805d7578" />) would be written as<img width="132" height="19" alt="score-increment-blocktran" src="https://github.com/user-attachments/assets/299de65d-b3ce-41d7-b00a-8d37b39b6cd1" />










  




























































## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  

This ensures your notes are easy for you (and others) to read later.

---

## Headings

**When to use:** Organize your notebook into sections (like days, topics, or projects).  

- `#` for the notebook title (use once at the top).  

- `##` for each day or major topic.  

- `###` for subsections (like "Notes", "Practice", "Reflections").  

# Example:

# My Coding Notebook

## Day 1

### Notes

### Practice

# Text Formatting

When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

# Example:

**Class** = a blueprint for objects  

*Remember:* always test your code  

Use `System.out.println()` to print

 

# Code Blocks

When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

# Example:

```java

public class Hello {

    public static void main(String[] args) {

        System.out.println("Hello World!");

    }

}

```

# Lists

When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

# Example:

Define the class
Write the main method
Test your program
Variables

- Loops

- Conditionals

 

# Checklists

When to use: Track progress on assignments or tasks.

# Example:

[x] Complete coding warm-up

- [ ] Finish project draft

- [ ] Reflect on learning

 

# Blockquotes

When to use: Call out notes, reminders, or teacher comments.

# Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

# Tables

When to use: Compare values, track progress, or organize data neatly.

# Example:

| Task        | Status   | Notes          |

|--------------|------------|-----------------| 

| Homework 1  | Done #  | Submitted      |

| Homework 2  | Pending  | Needs review   |

 

# Links & Images

When to use: Add references, resources, or visuals.

# Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

To make an image that is a link, paste the image, then add the following before it, replacing website address with the link:

<a href="website address">

And after the image info, add: </a>

# Collapsible Sections

When to use: Hide solutions, extended notes, or extra details.

# Example:

<details>

  <summary>Click to reveal solution</summary>

  

System.out.println("Answer: 42");

</details>

 

# Footnotes

When to use: Add references or side notes without cluttering the page.

# Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

# Style Rules

Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

# Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.
