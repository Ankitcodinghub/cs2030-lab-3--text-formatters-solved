# cs2030-lab-3--text-formatters-solved
**TO GET THIS SOLUTION VISIT:** [CS2030 Lab 3- Text Formatters Solved](https://www.ankitcodinghub.com/product/cs2030-text-formatters-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114511&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2030 Lab 3- Text Formatters Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Topic Coverage

Uses of Interfaces

Comparable Interface

PriorityQueue and Natural Ordering

Problem Description

Interfaces are a powerful tool that can be used to increase the maintainability of your codebase. In this lab, we will explore some different uses of interfaces and work with a commonly used interface, Comparable.

You are implementing a text editor. This text editor takes input and formats it according to the rules of a specified text formatter.

A number of different formats are specified below. Given an input string “I love CS2030”, each formatter will output the following:

Snake Case: “i_love_cs2030”

Kebab Case: “i-love-cs2030”

Pascal Case: “ILoveCs2030”

Mixed Format: “i_love_cs2030”, and this is derived from the following rules:

1. Take the first character of the input string, denoted by c. Find r = c % 3, where c is interpreted as the ASCII value of the character.

2. If r = 0, create a formatter s using the Snake Case format.

3. If r = 1, create a formatter s using the Kebab Case format. (The above string would do this)

4. If r = 2, create a formatter s using the Pascal Case format.

5. Additionally, create a Snake Case formatter, t, for the string “I Love CS2030”.

6. If s &gt; t, use the output of s. Otherwise, use the output of t.

Task

Write a program that reads some input strings, where each line is a string to format.

The program will output all the formatted strings in the order defined in each level.

The following assumptions can be made about the input:

They will only contain alphanumeric characters and spaces.

They will not start or end with a space. There will not be 2 spaces in a row.

Level 1

Create the Text Editor and the Snake Case Formatter.

Create the interface TextFormatter with the following code:

interface TextFormatter { // Return a formatted string public String format(); }

Create a class, TextEditor, that has the following constructor:

public TextEditor(List&lt;TextFormatter&gt; formatter)

i.e. the TextEditor is created with a list of provided TextFormatters.

It should have the methods addString(String s), that adds a string into the Text Editor, and a method printAll() to print all formatted strings.

Write a program that reads in the input strings, passes them in order to TextEditor, and then calls printAll() at the end.

The following is a sample run of the program. User input is underlined.

$ java Main I Love CS2030 i_love_cs2030

$ java Main oneword two words Capitalized Text same same But Different

correcT BaTTery stApl3 H0rSe oneword two_words capitalized_text same_same but_different

correct_battery_stapl3_h0rse

Check the format correctness of the output by typing the following Unix command

$ java Main &lt; test.in | diff – test1.out

Make a copy of your Java programs to the level directory by typing the Unix commands

$ jar cvf texteditor1.jar *.java

$ mkdir texteditor1

$ cp *.java texteditor1

$ cp texteditor1.jar texteditor1

Verify your jar archive using

$ jar tf ~/texteditor1/texteditor1.jar

Level 3

Sorting Formatters

In Java, a PriorityQueue can be used to easily sort objects according to some rules of sorting.

In a PriorityQueue, objects are sorted according to their “natural ordering”, i.e. the order that objects would be in if no comparison condition, or Comparator, is provided.

Level 2

Implement the Kebab Case Formatter and the Pascal Case Formatter

Create the two formatters according to the rules defined above. Pass all three formatters to the TextEditor in the order [Snake Case, Kebab Case, Pascal Case], such that when calling `printAll()`, each string is formatted using the 3 TextFormatters in order, and each string is printed in the order that it was inserted.

The following is a sample run of the program. User input is underlined.

$ java Main I Love CS2030 i_love_cs2030 i-love-cs2030 ILoveCs2030

$ java Main oneword two words Capitalized Text same same But Different

correcT BaTTery stApl3 H0rSe oneword oneword Oneword two_words two-words TwoWords capitalized_text capitalized-text CapitalizedText same_same same-same SameSame but_different but-different ButDifferent correct_battery_stapl3_h0rse correct-battery-stapl3-h0rse CorrectBatteryStapl3H0rse

Check the format correctness of the output by typing the following Unix command

$ java Main &lt; test.in | diff – test2.out

Make a copy of your Java programs to the level directory by typing the Unix commands

$ jar cvf texteditor2.jar *.java

$ mkdir texteditor2

$ cp *.java texteditor2

$ cp texteditor2.jar texteditor2

Verify your jar archive using

$ jar tf ~/texteditor2/texteditor2.jar

We can do this by having the formatters implement the Comparable interface, specifically Comparable&lt;TextFormatter&gt;. The

compareTo(T o) method compares the current object to another object. It returns a negative number if it comes before the other object, a positive number if it comes after the other object, and 0 if they are considered of the same ordering. The type T in the argument is a “generic type”. In this case, since we are implementing Comparable&lt;TextFormatter&gt;, T should be TextFormatter. You will learn/have learnt more about it in the lectures.

In your TextEditor, use a PriorityQueue&lt;TextFormatter&gt; to store the various TextFormatters. The comparison condition between TextFormatters should be as follows:

1. Generate the output of the text formatter.

2. Take the ASCII value of each character in the output and sum them up.

3. The formatter with a lower sum should come before the formatter with a higher sum.

printAll() should print all formatted strings according to the ordering defined above.

(Note that we could also use a Comparator to sort output strings, but let’s ignore that for the sake of learning.) The following is a sample run of the program. User input is underlined.

$ java Main

I Love CS2030 ILoveCs2030 i-love-cs2030 i_love_cs2030

$ java Main oneword two words Capitalized Text same same But Different

correcT BaTTery stApl3 H0rSe Oneword oneword oneword SameSame TwoWords same-same same_same two-words two_words ButDifferent but-different but_different CapitalizedText capitalized-text capitalized_text

CorrectBatteryStapl3H0rse correct-battery-stapl3-h0rse correct_battery_stapl3_h0rse

Check the format correctness of the output by typing the following Unix command

$ java Main &lt; test.in | diff – test3.out

Make a copy of your Java programs to the level directory by typing the Unix commands

$ jar cvf texteditor3.jar *.java

$ mkdir texteditor3

$ cp *.java texteditor3

$ cp texteditor3.jar texteditor3

Verify your jar archive using

$ jar tf ~/texteditor3/texteditor3.jar

Level 4

Implement the Mixed Formatter

Implement a Mixed formatter that formats strings according to the rules above. Add it to your TextEditor.

Hint: You might need to implement a new interface that extends from others.

The following is a sample run of the program. User input is underlined.

$ java Main

I Love CS2030 ILoveCs2030 i-love-cs2030 i_love_cs2030 i_love_cs2030

$ java Main oneword two words Capitalized Text same same But Different

correcT BaTTery stApl3 H0rSe Oneword oneword oneword SameSame TwoWords same-same same_same two-words two_words i_love_cs2030 i_love_cs2030 i_love_cs2030 ButDifferent but-different but_different but_different CapitalizedText capitalized-text capitalized-text capitalized_text

CorrectBatteryStapl3H0rse correct-battery-stapl3-h0rse correct_battery_stapl3_h0rse correct_battery_stapl3_h0rse

Check the format correctness of the output by typing the following Unix command

$ java Main &lt; test.in | diff – test4.out

Make a copy of your Java programs to the level directory by typing the Unix commands

$ jar cvf texteditor4.jar *.java

$ mkdir texteditor4

$ cp *.java texteditor4

$ cp texteditor4.jar texteditor4

Verify your jar archive using

$ jar tf ~/texteditor4/texteditor4.jar
