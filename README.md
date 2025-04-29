# csci-1933-project-3--code-style-solved
**TO GET THIS SOLUTION VISIT:** [CSCI 1933 project 3 -Code Style Solved](https://www.ankitcodinghub.com/product/csci-1933-project-3-code-style-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;52086&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI 1933 project 3 -Code Style Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
Part of your grade will be decided based on the “code style” demonstrated by your programming. In general, all projects will involve a style component. This should not be intimidating, but it is fundamentally important. The following items represent “good” coding style:

<ul>
<li>Use effective comments to document what important variables, functions, and sections of the code are for. In general, the TA should be able to understand your logic through the comments left in the code.</li>
</ul>
Try to leave comments as you program, rather than adding them all in at the end. Comments should not feel like arbitrary busy work – they should be written assuming the reader is fluent in Java, yet has no idea how your program works or why you chose certain solutions.

<ul>
<li>Use effective and standard indentation.</li>
<li>Use descriptive names for variables. Use standard Java style for your names: ClassName, functionName, variableName for structures in your code, and java for the file names.</li>
</ul>
Try to avoid the following stylistic problems:

<ul>
<li>Missing or highly redundant, useless comments. int a = 5; //Set a to be 5 is not helpful.</li>
<li>Disorganized and messy files. Poor indentation of braces ({ and }).</li>
<li>Incoherent variable names. Names such as m and numberOfIndicesToCount are not useful. The former is too short to be descriptive, while the latter is much too descriptive and redundant.</li>
<li>Slow functions. While some algorithms are more efficient than others, functions that are aggressively inefficient could be penalized even if they are otherwise correct. In general, functions ought to terminate in under 5 seconds for any reasonable input.</li>
</ul>
The programming exercises detailed in the following pages will both be evaluated for code style. This will not be strict – for example, one bad indent or one subjective variable name are hardly a problem. However, if your code seems careless or confusing, or if no significant effort was made to document the code, then points will be deducted.

In further projects we will continue to expect a reasonable attempt at documentation and style as detailed in this section. If you are confused about the style guide, please talk with a TA.

<ol>
<li>INTRODUCTION 1 Introduction</li>
</ol>
IMPORTANT: This project utilizes interfaces and generics. For brevity, this write-up omits discussions of such topics. For more information, please see a TA, review the lecture notes, or review other related literature (e.g. official Java documentation).

In this project you will implement a list in two different ways: as an ArrayList and as a LinkedList. You will then compare the time complexities of each List method when implemented as an ArrayList and as a LinkedList.

<h2>1.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; LinkedList Implementation</h2>
The first part of this project will be to implement a linked list. Create a class LinkedList that implements all the methods in List interface. Recall that to implement the List interface and use the generic compatibility with your code, LinkedList should have following structure:

public class LinkedList&lt;T extends Comparable&lt;T&gt;&gt; implements List&lt;T&gt; { …

}

The underlying structure of a linked list is a node. This means you will have an instance variable that is the first node of the list. The provided Node.java contains a generic node class that you will use for your linked list implementation<sup>∗</sup>.

Your LinkedList class should have a single constructor:

public LinkedList() { …

}

that initializes the list to an empty list.

<h2>Implementation Details</h2>
<ul>
<li>In addition to the methods described in the List interface, the LinkedList class should contain a private class variable isSorted. This should be initialized to true in the constructor (because it is sorted if it has no elements) and updated when the list is sorted, or more elements are added or set. For the purposes of this class, isSorted is only true if the list is sorted in ascending order.</li>
</ul>
∗

You may implement your linked list as a <em>headed </em>list, i.e., the first node in the list is a ‘dummy’ node and the second node is the first element of the list, or a non-headed list, i.e., the first node is the first element of the list.

Depending on how you choose to implement your list, there will be some small nuances.

<ol>
<li>INTRODUCTION</li>
</ol>
<ul>
<li>Initially and after a call to clear(), the size should be zero and your list should be empty.</li>
<li>In sort(), <strong>do not use an array or ArrayList </strong>to sort the elements. You are required to sort the values using only the linked list data structure. You can move nodes or swap values but you cannot use an array to store values while sorting.</li>
<li>Depending on your implementation, remember that after sorting, the former first node may not be the current first node.</li>
</ul>
<h2>1.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Array List Implementation</h2>
The second part of this project will be to implement an array list. Create a class ArrayList that implements all the methods in List interface. Recall that to implement the List interface and use the generic compatibility with your code, ArrayList should have following structure:

public class ArrayList&lt;T extends Comparable&lt;T&gt;&gt; implements List&lt;T&gt; { …

}

The underlying structure of an array list is (obviously) an array. This means you will have an instance variable that is an array. Since our implementation is generic, the type of this array will be T[]. Due to Java’s implementation of generics<sup>†</sup>, you <strong>CANNOT </strong>simply create a generic array with:

T[] a = new T[size];

Rather, you have to create a Comparable (since T extends Comparable)<sup>‡ </sup>array and <em>cast </em>it to an array of type T.

T[] a = (T[]) new Comparable[size];

Your ArrayList class should have a single constructor:

public ArrayList() { …

}

that initializes the underlying array to a length of 2.

<h2>Implementation Details</h2>
<ul>
<li>In addition to the methods described in the List interface, the ArrayList class should contain a private class variable isSorted. This should be initialized to true in the constructor (because it is sorted if it has no elements) and updated when the list is sorted, or more</li>
</ul>
†

specifically because of <a href="https://docs.oracle.com/javase/tutorial/java/generics/erasure.html">type erasure</a>

‡

had T not extended Comparable, you would say T[] a = (T[])new Object[size];

<ol start="2">
<li>UNIT TESTS</li>
</ol>
elements are added or set. For the purposes of this class, isSorted is only true if the list is sorted in ascending order.

<ul>
<li>When the underlying array becomes full, both add methods will automatically add more space by creating a <em>new </em>array that is <strong>twice </strong>the length of the original array, copying over everything from the original array to the new array, and finally setting the instance variable to the new array. <em>Hint: You may find it useful to write a separate </em>private <em>method that does the growing and copying</em></li>
<li>When calling either remove method, the underlying array should <em>no longer have that spot</em>. For example, if the array was [“hi”, “bye”, “hello”, “okay”, …] and you called remove with index 1, the array would be [“hi”, “hello”, “okay”, …]. Basically, the only null elements of the array should be <em>after </em>all the data.</li>
<li>Initially and after a call to clear(), the size method should return 0. The “size” refers to the number of elements in the <em>list </em>, NOT the length of the <em>array</em>. After a call to clear(), the underlying array should be reset to a length of 2 as in the constructor.</li>
</ul>
<h1>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Unit Tests</h1>
As mentioned at the beginning of the project writeup we will be using a program to evaluate your code. Specifically, we will be using JUnit (unit tests) to test each method that you implement. We may release these tests for you to use when they are ready to so you can check that everything in your classes works properly. Expect to hear more information about this in the near future.

<h1>3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Analysis</h1>
Now that you have implemented and used both an array list and linked list, which one is better? Which methods in List are more efficient for each implementation?

For each of the 13 methods in List, compare the runtime (Big-<em>O</em>) for each method and implementation. Ignore any increased efficiency caused by the flag isSorted. Include an analysis.txt or analysis.pdf with your submission structured as follows:

Method&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ArrayList Runtime LinkedList Runtime Explanation boolean add(T element)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; O(…)&nbsp;&nbsp;&nbsp;&nbsp; O(…)&nbsp;&nbsp;&nbsp;&nbsp; … boolean add(int index, T element) O(…)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; O(…)&nbsp;&nbsp;&nbsp;&nbsp; …

…&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; …&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; …&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; …

Your explanation for each method only needs to be a couple sentences briefly justifying your runtimes.

<ol start="4">
<li>HONORS</li>
</ol>
<h1>4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Honors</h1>
Note: This section is <strong>required </strong>for students in Honors section only. Optional for others but no extra credit.

You will have two additional methods to implement. Each method must be implemented in both the ArrayList class and the LinkedList class.

<ol>
<li>getKSmallest(int k) – This method returns a new List object (ArrayList or LinkedList depending on what type of object the method is called on) containting the k smallest elements in the given List. If k is less than 1 then null should be returned. If k is greater than or equal to the size of the list then the entire list should be returned.</li>
<li>getKLargest(int k) – This method returns a new List object (ArrayList or LinkedList depending on what type of object the method is called on) containing the k largest elements in the given List. If k is less than 1 then null should be returned. If k is greater than or equal to the size of the list then the entire list should be returned.</li>
</ol>
You should also include time complexities for these methods in your analysis.txt/analysis.pdf file.
