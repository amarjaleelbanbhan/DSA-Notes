# DSA-Notes


##### Amar Jaleel 


---


 

### **Hello AI,**  

I am preparing for my upcoming **Data Structures and Algorithms (DSA)** midterm exam and need your assistance to cover the following topics thoroughly, with **Java** as the primary programming language.

---

## **Topics to Cover:**  
1. **Arrays**  
   - Basics of Arrays in Java (declaration, initialization, usage)  
   - Operations: Insertion, Deletion, Traversal, Searching, and Sorting  
   - Time and Space Complexity of Array Operations  
   - Two-dimensional Arrays and Applications  
   - Practical Examples (e.g., Matrix Multiplication, Sliding Window problems)  

2. **Linked Lists**  
   - Types of Linked Lists (Singly, Doubly, Circular)  
   - Implementation of Linked Lists in Java  
   - Operations: Insert, Delete, Search, Reverse, Merge  
   - Differences between Arrays and Linked Lists  
   - Time and Space Complexity for Different Operations  

3. **Stacks**  
   - Concept of Stack (LIFO)  
   - Java Implementation Using Arrays or Linked Lists  
   - Key Operations: Push, Pop, Peek, isEmpty  
   - Applications: Balanced Parentheses, Infix to Postfix Conversion  
   - Time and Space Complexity  

4. **Queues**  
   - Concept of Queue (FIFO)  
   - Types: Simple Queue, Circular Queue, Deque, and Priority Queue  
   - Implementation in Java using Arrays and Linked Lists  
   - Operations: Enqueue, Dequeue, Peek, isEmpty  
   - Time and Space Complexity  

5. **Sorting Algorithms**  
   - Overview and Importance of Sorting  
   - Types:  
     - **Bubble Sort:** Simple but inefficient  
     - **Selection Sort:** Finding the smallest element in each iteration  
     - **Insertion Sort:** Good for small datasets  
     - **Merge Sort:** Divide and conquer approach  
     - **Quick Sort:** Pivot-based sorting with partitioning  
     - **Heap Sort:** Using a heap to sort efficiently  
   - Java Implementations for Each Algorithm  
   - Time and Space Complexity of Different Sorting Techniques  
   - Real-world Use Cases (e.g., Leaderboards, Searching after Sorting)  

6. **Time and Space Complexity**  
   - Big-O, Big-Θ, Big-Ω Notations  
   - How to Analyze Time and Space Complexity of Code  
   - Best, Average, and Worst Case Scenarios  
   - Time Complexity of Loops, Recursion, and Nested Loops  

7. **Recursion**  
   - Concept of Recursion with Base and Recursive Case  
   - Converting Recursion to Iteration and Vice-Versa  
   - Applications: Factorial, Fibonacci, Tower of Hanoi  
   - Time and Space Complexity of Recursive Code  

---

## **📚 Study Objectives:**  
1. **Comprehensive Summaries:**  
   Provide detailed but concise overviews of each topic, focusing on theory and implementation.  

2. **Code Implementation in Java:**  
   Include well-commented code snippets for all data structures and algorithms.  

3. **Comparative Analysis:**  
   Compare different approaches, such as **Recursive vs. Iterative algorithms** and **Quick Sort vs. Merge Sort**.  

4. **Practical Applications:**  
   Provide real-world use cases (e.g., **priority queues in task scheduling** and **stacks in function call management**).  

5. **Diagrams and Visual Aids:**  
   Include diagrams or flowcharts for algorithms, data structures, and recursion flows.  

6. **Flashcards:**  
   Create flashcards with key terms, concepts, and code-related questions to aid quick recall.  

7. **Practice Questions:**  
   Develop a set of multiple-choice questions, coding problems, and conceptual questions for each topic.  

8. **Study Schedule:**  
   Propose an efficient study plan to allocate time for each topic before the exam.  

9. **Active Learning Techniques:**  
   Suggest coding exercises, teaching back, and debugging practice to reinforce learning.  

10. **Resource Recommendations:**  
   Provide additional books, articles, or videos to explore complex concepts further.  

---

## **📝 Specific Requests:**  
For **Each Topic:**  
- **Summary:** 200-300 words explaining the key points and theory.  
- **Key Points:** Bullet points of the most critical ideas.  
- **Code Example:** Provide at least one working code snippet with detailed comments.  
- **Visuals:** Use diagrams or pseudocode to illustrate concepts where necessary.  
- **Flashcards:** Create 5-10 flashcards for important concepts and operations.  
- **Practice Questions:** Include 3-5 questions per topic with varying difficulty.  
- **Tips and Tricks:** Provide memory aids or shortcuts to remember complex topics.  

---

## **💡 Overall Study Plan:**  
1. **Divide Study Time:** Allocate time across all topics based on difficulty.  
2. **Practice Daily:** Write at least one code solution per day to build confidence.  
3. **Review and Revise:** Use spaced repetition to recall key concepts.  
4. **Mock Tests:** Attempt coding and theory mock exams under timed conditions.  
5. **Debug Practice:** Identify and fix common mistakes through debugging exercises.  

---

## **🎯 Goals:**  
- Develop a **clear understanding of DSA concepts** with practical knowledge in Java.  
- Be able to **write and debug Java code confidently** during the exam.  
- Gain familiarity with **time and space complexity analysis** for efficient coding.  
- Achieve **30/30 in the midterm** by mastering all topics and answering questions effectively.  

---

## **💡 Additional Instructions:**  
- Ensure explanations are **simple and easy to understand**, avoiding unnecessary jargon.  
- Highlight **connections between data structures and algorithms** to show their interdependence.  
- Pose **"why" and "how" questions** to encourage deeper thinking and insight into problem-solving approaches.  

---

Let’s get started with the first topic: **Arrays!**  



---

 
<h3><strong>1. Arrays in Java</strong></h3><hr><h4><strong>Summary:</strong></h4><p>An <strong>array</strong> is a data structure that stores elements of the same type in contiguous memory locations. In Java, arrays are <strong>static structures</strong> where the size is fixed during initialization. Arrays provide <strong>fast access</strong> to elements using an index, but insertion and deletion can be time-consuming due to the need to shift elements. Arrays can be <strong>one-dimensional</strong> or <strong>multi-dimensional</strong> (e.g., 2D matrices). Operations like <strong>insertion, deletion, searching, sorting, and traversal</strong> are frequently used on arrays in coding problems. Arrays are widely used for <strong>implementing lists, heaps, matrices</strong>, and many other structures.</p><hr><h4><strong>Key Points:</strong></h4><ul><li><strong>Declaration:</strong> <code>int[] arr;</code></li><li><strong>Initialization:</strong> <code>int[] arr = new int[5];</code> or <code>int[] arr = {1, 2, 3};</code></li><li><strong>Indexing:</strong> Elements are accessed by <code>arr[index]</code>.</li><li><strong>Fixed Size:</strong> Array size cannot be changed after initialization.</li><li><strong>Types:</strong> 1D arrays and 2D arrays (like a matrix).</li><li><strong>Complexity:</strong><ul><li><strong>Access:</strong> O(1)</li><li><strong>Search:</strong> O(n) (linear search), O(log n) (binary search)</li><li><strong>Insertion/Deletion:</strong> O(n) (due to shifting elements)</li></ul></li></ul><hr><h4><strong>Java Code Example – Array Operations:</strong></h4><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">public</span> <span class="hljs-keyword">class</span> <span class="hljs-title class_">ArrayOperations</span> {

    <span class="hljs-keyword">public</span> <span class="hljs-keyword">static</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">main</span><span class="hljs-params">(String[] args)</span> {
        <span class="hljs-comment">// Initialize an array</span>
        <span class="hljs-type">int</span>[] arr = {<span class="hljs-number">1</span>, <span class="hljs-number">2</span>, <span class="hljs-number">3</span>, <span class="hljs-number">4</span>, <span class="hljs-number">5</span>};
        
        <span class="hljs-comment">// Traverse array</span>
        System.out.print(<span class="hljs-string">"Array Elements: "</span>);
        <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>; i &lt; arr.length; i++) {
            System.out.print(arr[i] + <span class="hljs-string">" "</span>);
        }

        <span class="hljs-comment">// Insert an element (at index 2)</span>
        arr = insert(arr, <span class="hljs-number">6</span>, <span class="hljs-number">2</span>);
        System.out.println(<span class="hljs-string">"\nAfter Insertion: "</span> + java.util.Arrays.toString(arr));

        <span class="hljs-comment">// Delete an element (at index 3)</span>
        arr = delete(arr, <span class="hljs-number">3</span>);
        System.out.println(<span class="hljs-string">"After Deletion: "</span> + java.util.Arrays.toString(arr));
    }

    <span class="hljs-comment">// Insert element into the array at a specific index</span>
    <span class="hljs-keyword">public</span> <span class="hljs-keyword">static</span> <span class="hljs-type">int</span>[] insert(<span class="hljs-type">int</span>[] arr, <span class="hljs-type">int</span> value, <span class="hljs-type">int</span> index) {
        <span class="hljs-type">int</span>[] newArr = <span class="hljs-keyword">new</span> <span class="hljs-title class_">int</span>[arr.length + <span class="hljs-number">1</span>];
        <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>; i &lt; index; i++) {
            newArr[i] = arr[i];
        }
        newArr[index] = value;
        <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> index; i &lt; arr.length; i++) {
            newArr[i + <span class="hljs-number">1</span>] = arr[i];
        }
        <span class="hljs-keyword">return</span> newArr;
    }

    <span class="hljs-comment">// Delete element from the array at a specific index</span>
    <span class="hljs-keyword">public</span> <span class="hljs-keyword">static</span> <span class="hljs-type">int</span>[] delete(<span class="hljs-type">int</span>[] arr, <span class="hljs-type">int</span> index) {
        <span class="hljs-type">int</span>[] newArr = <span class="hljs-keyword">new</span> <span class="hljs-title class_">int</span>[arr.length - <span class="hljs-number">1</span>];
        <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>; i &lt; index; i++) {
            newArr[i] = arr[i];
        }
        <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> index; i &lt; newArr.length; i++) {
            newArr[i] = arr[i + <span class="hljs-number">1</span>];
        }
        <span class="hljs-keyword">return</span> newArr;
    }
}
</code></div></div></pre><hr><h4><strong>2D Arrays Example – Matrix Multiplication:</strong></h4><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">public</span> <span class="hljs-keyword">class</span> <span class="hljs-title class_">MatrixMultiplication</span> {

    <span class="hljs-keyword">public</span> <span class="hljs-keyword">static</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">main</span><span class="hljs-params">(String[] args)</span> {
        <span class="hljs-type">int</span>[][] A = { {<span class="hljs-number">1</span>, <span class="hljs-number">2</span>}, {<span class="hljs-number">3</span>, <span class="hljs-number">4</span>} };
        <span class="hljs-type">int</span>[][] B = { {<span class="hljs-number">5</span>, <span class="hljs-number">6</span>}, {<span class="hljs-number">7</span>, <span class="hljs-number">8</span>} };

        <span class="hljs-type">int</span>[][] result = multiply(A, B);

        System.out.println(<span class="hljs-string">"Product of Matrices:"</span>);
        <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span>[] row : result) {
            <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> element : row) {
                System.out.print(element + <span class="hljs-string">" "</span>);
            }
            System.out.println();
        }
    }

    <span class="hljs-keyword">public</span> <span class="hljs-keyword">static</span> <span class="hljs-type">int</span>[][] multiply(<span class="hljs-type">int</span>[][] A, <span class="hljs-type">int</span>[][] B) {
        <span class="hljs-type">int</span> <span class="hljs-variable">rows</span> <span class="hljs-operator">=</span> A.length;
        <span class="hljs-type">int</span> <span class="hljs-variable">cols</span> <span class="hljs-operator">=</span> B[<span class="hljs-number">0</span>].length;
        <span class="hljs-type">int</span>[][] result = <span class="hljs-keyword">new</span> <span class="hljs-title class_">int</span>[rows][cols];

        <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>; i &lt; rows; i++) {
            <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">j</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>; j &lt; cols; j++) {
                <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">k</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>; k &lt; A[<span class="hljs-number">0</span>].length; k++) {
                    result[i][j] += A[i][k] * B[k][j];
                }
            }
        }
        <span class="hljs-keyword">return</span> result;
    }
}
</code></div></div></pre><hr><h4><strong>Flashcards:</strong></h4><ol><li><p><strong>Q:</strong> What is the time complexity of accessing an element in an array?<br><strong>A:</strong> O(1) (constant time).</p></li><li><p><strong>Q:</strong> What is the difference between a 1D and 2D array?<br><strong>A:</strong> A 1D array is a single list, while a 2D array is a table-like structure with rows and columns.</p></li><li><p><strong>Q:</strong> Can you change the size of an array after initialization in Java?<br><strong>A:</strong> No, arrays are of fixed size.</p></li><li><p><strong>Q:</strong> What is the time complexity of inserting an element in the middle of an array?<br><strong>A:</strong> O(n) due to shifting elements.</p></li><li><p><strong>Q:</strong> What type of memory is used to store arrays in Java?<br><strong>A:</strong> Heap memory.</p></li></ol><hr><h4><strong>Practice Questions:</strong></h4><ol><li>Write a Java program to find the maximum element in an array.</li><li>Implement a function that reverses a given array in-place.</li><li>Given an array, find all pairs of numbers that add up to a given sum.</li><li>Explain the difference between a <strong>linear search</strong> and a <strong>binary search</strong> in arrays.</li><li>How would you implement a <strong>circular array</strong> in Java?</li></ol><hr><h4><strong>Tips and Tricks:</strong></h4><ul><li>Use <strong>binary search</strong> instead of <strong>linear search</strong> on <strong>sorted arrays</strong> to reduce search time from O(n) to O(log n).</li><li>Practice <strong>sliding window problems</strong> (like finding the max sum of a subarray) to get comfortable with array operations.</li><li><strong>Matrix multiplication</strong> is a common interview problem—understand how row-column multiplications work.</li></ul><hr><h4><strong>Study Plan for Arrays:</strong></h4><ul><li><strong>Day 1:</strong> Understand basic array operations and implement a few examples.</li><li><strong>Day 2:</strong> Work with <strong>2D arrays</strong> and matrix-related problems.</li><li><strong>Day 3:</strong> Solve <strong>sliding window</strong> and <strong>searching</strong> problems in arrays.</li><li><strong>Daily Practice:</strong> Write code to <strong>insert, delete, search, and traverse</strong> arrays to gain confidence.</li></ul><hr><p>This is a <strong>solid start</strong> with <strong>Arrays</strong>. Once you're comfortable, we can move to <strong>Linked Lists</strong> next! Let me know how you feel about this, and if you want adjustments or more examples!</p>

---




---

 
<h3><strong>Linked Lists</strong></h3><h4><strong>1. Summary:</strong></h4><p>A <strong>linked list</strong> is a linear data structure where elements, called nodes, are linked together using pointers. Each node contains <strong>two parts</strong>:</p><ol><li><strong>Data:</strong> Stores the element's value.</li><li><strong>Reference (Pointer):</strong> Points to the next node (or both next and previous nodes in some types).<br>Unlike arrays, linked lists do not store elements in contiguous memory, making insertion and deletion operations more efficient but requiring extra memory for pointers.</li></ol><p>There are <strong>three main types</strong> of linked lists:</p><ul><li><strong>Singly Linked List:</strong> Each node points to the next node only.</li><li><strong>Doubly Linked List:</strong> Each node has pointers to both previous and next nodes.</li><li><strong>Circular Linked List:</strong> The last node points back to the first node.</li></ul><hr><h4><strong>2. Key Points:</strong></h4><ul><li><strong>Efficient insertion and deletion:</strong> No need to shift elements like arrays.</li><li><strong>Dynamic size:</strong> Can grow or shrink during runtime.</li><li><strong>Types:</strong> Singly, Doubly, Circular Linked Lists.</li><li><strong>Use Case:</strong> Useful for stacks, queues, and graph implementations.</li><li><strong>Drawback:</strong> Higher memory usage due to pointers and slower access than arrays (no random access).</li></ul><hr><h4><strong>3. Code Example in Java:</strong></h4><p><strong>Singly Linked List – Java Implementation</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">Node</span> {
    <span class="hljs-type">int</span> data;
    Node next;  <span class="hljs-comment">// Pointer to the next node</span>

    <span class="hljs-comment">// Constructor to initialize node data</span>
    Node(<span class="hljs-type">int</span> data) {
        <span class="hljs-built_in">this</span>.data = data;
        <span class="hljs-built_in">this</span>.next = <span class="hljs-literal">null</span>;
    }
}

<span class="hljs-keyword">class</span> <span class="hljs-title class_">SinglyLinkedList</span> {
    <span class="hljs-type">Node</span> <span class="hljs-variable">head</span> <span class="hljs-operator">=</span> <span class="hljs-literal">null</span>;  <span class="hljs-comment">// First node (head)</span>

    <span class="hljs-comment">// Insert a new node at the beginning</span>
    <span class="hljs-keyword">public</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">insertAtBeginning</span><span class="hljs-params">(<span class="hljs-type">int</span> data)</span> {
        <span class="hljs-type">Node</span> <span class="hljs-variable">newNode</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">Node</span>(data);
        newNode.next = head;
        head = newNode;
    }

    <span class="hljs-comment">// Delete a node from the beginning</span>
    <span class="hljs-keyword">public</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">deleteFromBeginning</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (head != <span class="hljs-literal">null</span>) {
            head = head.next;
        }
    }

    <span class="hljs-comment">// Display all elements in the linked list</span>
    <span class="hljs-keyword">public</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">display</span><span class="hljs-params">()</span> {
        <span class="hljs-type">Node</span> <span class="hljs-variable">current</span> <span class="hljs-operator">=</span> head;
        <span class="hljs-keyword">while</span> (current != <span class="hljs-literal">null</span>) {
            System.out.print(current.data + <span class="hljs-string">" -&gt; "</span>);
            current = current.next;
        }
        System.out.println(<span class="hljs-string">"null"</span>);
    }

    <span class="hljs-keyword">public</span> <span class="hljs-keyword">static</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">main</span><span class="hljs-params">(String[] args)</span> {
        <span class="hljs-type">SinglyLinkedList</span> <span class="hljs-variable">list</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">SinglyLinkedList</span>();
        list.insertAtBeginning(<span class="hljs-number">10</span>);
        list.insertAtBeginning(<span class="hljs-number">20</span>);
        list.insertAtBeginning(<span class="hljs-number">30</span>);
        System.out.println(<span class="hljs-string">"Linked List:"</span>);
        list.display();

        list.deleteFromBeginning();
        System.out.println(<span class="hljs-string">"After Deletion:"</span>);
        list.display();
    }
}
</code></div></div></pre><hr><h4><strong>4. Visual Aid (Pseudocode):</strong></h4><p><strong>Insert at the Beginning:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">bash</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-bash">Create newNode(data)
newNode.next = <span class="hljs-built_in">head</span>
<span class="hljs-built_in">head</span> = newNode
</code></div></div></pre><hr><h4><strong>5. Flashcards:</strong></h4><ol><li><p><strong>Q:</strong> What is the difference between a singly and doubly linked list?<br><strong>A:</strong> A singly linked list has one pointer to the next node, while a doubly linked list has pointers to both previous and next nodes.</p></li><li><p><strong>Q:</strong> What is the advantage of linked lists over arrays?<br><strong>A:</strong> Insertion and deletion are easier since no shifting is required.</p></li><li><p><strong>Q:</strong> What type of linked list allows the last node to point to the first node?<br><strong>A:</strong> Circular Linked List.</p></li><li><p><strong>Q:</strong> What is the space complexity for storing a linked list?<br><strong>A:</strong> <strong>O(n)</strong> for data and <strong>O(n)</strong> for pointers.</p></li><li><p><strong>Q:</strong> Which linked list type is used in a queue implementation?<br><strong>A:</strong> Singly Linked List (for Simple Queue).</p></li></ol><hr><h4><strong>6. Practice Questions:</strong></h4><ol><li>Implement a <strong>doubly linked list</strong> in Java.</li><li>Write a method to <strong>reverse</strong> a singly linked list.</li><li>How would you detect <strong>cycles</strong> in a linked list? Implement it in Java.</li><li>Compare the time complexities of searching in an <strong>array vs. a linked list</strong>.</li><li>Write a program to <strong>merge two sorted linked lists</strong> into one.</li></ol><hr><h4><strong>7. Tips and Tricks:</strong></h4><ul><li><strong>Pointer Confusion:</strong> Draw diagrams while implementing linked lists to avoid pointer errors.</li><li><strong>Reverse Linked List:</strong> Use <strong>two-pointer</strong> techniques to swap pointers without extra space.</li><li><strong>Avoid Memory Leaks:</strong> Always set unused pointers to <strong>null</strong>.</li></ul><hr><h4><strong>8. Time and Space Complexities:</strong></h4><ul><li><strong>Insert at beginning:</strong> O(1)</li><li><strong>Delete from beginning:</strong> O(1)</li><li><strong>Search an element:</strong> O(n)</li><li><strong>Space Complexity:</strong> O(n) due to data and pointers</li></ul><hr><h4><strong>9. Practical Applications:</strong></h4><ul><li><strong>Music Playlists:</strong> Circular linked lists manage playlists with a loop.</li><li><strong>Undo/Redo Operations:</strong> Doubly linked lists store previous and next states.</li><li><strong>Queue Implementation:</strong> Linked lists are used for queues in operating systems.</li></ul><hr><h4><strong>10. Comparative Analysis:</strong></h4><ul><li><strong>Arrays vs. Linked Lists:</strong><ul><li>Arrays offer <strong>faster access (O(1))</strong>, while linked lists provide <strong>easier insertion and deletion (O(1))</strong>.</li><li>Arrays are better for <strong>fixed-size data</strong>, whereas linked lists are ideal for <strong>dynamic data</strong>.</li></ul></li></ul><hr><p>Would you like to move on to <strong>Stacks</strong>, or explore more about <strong>linked lists</strong>?</p>

---


---

 
<h3><strong>Deep Dive into Linked Lists</strong></h3><h4><strong>What is a Linked List?</strong></h4><p>A <strong>linked list</strong> is a linear data structure where elements (nodes) are linked using pointers. Unlike arrays, elements are not stored in contiguous memory, making linked lists flexible in size and efficient for insertions and deletions.</p><hr><h2><strong>1. Types of Linked Lists:</strong></h2><ol><li><p><strong>Singly Linked List:</strong></p><ul><li>Each node has a <strong>data field</strong> and a <strong>pointer to the next node</strong>.</li><li><strong>Use Case:</strong> Basic lists, simple stacks, or queues.</li></ul><p><strong>Structure Example:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">rust</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-rust"><span class="hljs-number">10</span> <span class="hljs-punctuation">-&gt;</span> <span class="hljs-number">20</span> <span class="hljs-punctuation">-&gt;</span> <span class="hljs-number">30</span> <span class="hljs-punctuation">-&gt;</span> null
</code></div></div></pre></li><li><p><strong>Doubly Linked List (DLL):</strong></p><ul><li>Each node has <strong>two pointers</strong>: one to the previous node and one to the next node.</li><li><strong>Use Case:</strong> Undo/Redo operations, music playlists.</li></ul><p><strong>Structure Example:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">rust</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-rust">null &lt;- <span class="hljs-number">10</span> &lt;<span class="hljs-punctuation">-&gt;</span> <span class="hljs-number">20</span> &lt;<span class="hljs-punctuation">-&gt;</span> <span class="hljs-number">30</span> <span class="hljs-punctuation">-&gt;</span> null
</code></div></div></pre></li><li><p><strong>Circular Linked List (Singly Circular):</strong></p><ul><li>The <strong>last node points back to the first node</strong>, creating a circular structure.</li><li><strong>Use Case:</strong> Round-robin scheduling, playlists.</li></ul><p><strong>Structure Example:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">rust</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-rust"><span class="hljs-number">10</span> <span class="hljs-punctuation">-&gt;</span> <span class="hljs-number">20</span> <span class="hljs-punctuation">-&gt;</span> <span class="hljs-number">30</span> <span class="hljs-punctuation">-&gt;</span> <span class="hljs-number">10</span> (back to the start)
</code></div></div></pre></li><li><p><strong>Doubly Circular Linked List:</strong></p><ul><li>Like a doubly linked list, but the <strong>last node points to the first</strong> and vice-versa.</li></ul></li></ol><hr><h2><strong>2. Operations on Linked Lists</strong></h2><h3><strong>Singly Linked List Operations:</strong></h3><h4><strong>Insertion:</strong></h4><ul><li><p><strong>At the Beginning:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">void</span> <span class="hljs-title function_">insertAtBeginning</span><span class="hljs-params">(<span class="hljs-type">int</span> data)</span> {
    <span class="hljs-type">Node</span> <span class="hljs-variable">newNode</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">Node</span>(data);
    newNode.next = head;
    head = newNode;
}
</code></div></div></pre><p><strong>Time Complexity:</strong> O(1)</p></li><li><p><strong>At the End:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">void</span> <span class="hljs-title function_">insertAtEnd</span><span class="hljs-params">(<span class="hljs-type">int</span> data)</span> {
    <span class="hljs-type">Node</span> <span class="hljs-variable">newNode</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">Node</span>(data);
    <span class="hljs-keyword">if</span> (head == <span class="hljs-literal">null</span>) {
        head = newNode;
    } <span class="hljs-keyword">else</span> {
        <span class="hljs-type">Node</span> <span class="hljs-variable">temp</span> <span class="hljs-operator">=</span> head;
        <span class="hljs-keyword">while</span> (temp.next != <span class="hljs-literal">null</span>) temp = temp.next;
        temp.next = newNode;
    }
}
</code></div></div></pre><p><strong>Time Complexity:</strong> O(n)</p></li></ul><h4><strong>Deletion:</strong></h4><ul><li><p><strong>From the Beginning:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">void</span> <span class="hljs-title function_">deleteFromBeginning</span><span class="hljs-params">()</span> {
    <span class="hljs-keyword">if</span> (head != <span class="hljs-literal">null</span>) head = head.next;
}
</code></div></div></pre><p><strong>Time Complexity:</strong> O(1)</p></li><li><p><strong>From the End:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">void</span> <span class="hljs-title function_">deleteFromEnd</span><span class="hljs-params">()</span> {
    <span class="hljs-keyword">if</span> (head == <span class="hljs-literal">null</span> || head.next == <span class="hljs-literal">null</span>) {
        head = <span class="hljs-literal">null</span>;
        <span class="hljs-keyword">return</span>;
    }
    <span class="hljs-type">Node</span> <span class="hljs-variable">temp</span> <span class="hljs-operator">=</span> head;
    <span class="hljs-keyword">while</span> (temp.next.next != <span class="hljs-literal">null</span>) temp = temp.next;
    temp.next = <span class="hljs-literal">null</span>;
}
</code></div></div></pre><p><strong>Time Complexity:</strong> O(n)</p></li></ul><h4><strong>Search Operation:</strong></h4><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">boolean</span> <span class="hljs-title function_">search</span><span class="hljs-params">(<span class="hljs-type">int</span> key)</span> {
    <span class="hljs-type">Node</span> <span class="hljs-variable">temp</span> <span class="hljs-operator">=</span> head;
    <span class="hljs-keyword">while</span> (temp != <span class="hljs-literal">null</span>) {
        <span class="hljs-keyword">if</span> (temp.data == key) <span class="hljs-keyword">return</span> <span class="hljs-literal">true</span>;
        temp = temp.next;
    }
    <span class="hljs-keyword">return</span> <span class="hljs-literal">false</span>;
}
</code></div></div></pre><p><strong>Time Complexity:</strong> O(n)</p><hr><h3><strong>Doubly Linked List Operations:</strong></h3><h4><strong>Insertion at the Beginning:</strong></h4><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">void</span> <span class="hljs-title function_">insertAtBeginning</span><span class="hljs-params">(<span class="hljs-type">int</span> data)</span> {
    <span class="hljs-type">Node</span> <span class="hljs-variable">newNode</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">Node</span>(data);
    newNode.next = head;
    <span class="hljs-keyword">if</span> (head != <span class="hljs-literal">null</span>) head.prev = newNode;
    head = newNode;
}
</code></div></div></pre><p><strong>Time Complexity:</strong> O(1)</p><h4><strong>Deletion from the End:</strong></h4><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">void</span> <span class="hljs-title function_">deleteFromEnd</span><span class="hljs-params">()</span> {
    <span class="hljs-keyword">if</span> (head == <span class="hljs-literal">null</span>) <span class="hljs-keyword">return</span>;
    <span class="hljs-keyword">if</span> (head.next == <span class="hljs-literal">null</span>) {
        head = <span class="hljs-literal">null</span>;
    } <span class="hljs-keyword">else</span> {
        <span class="hljs-type">Node</span> <span class="hljs-variable">temp</span> <span class="hljs-operator">=</span> head;
        <span class="hljs-keyword">while</span> (temp.next != <span class="hljs-literal">null</span>) temp = temp.next;
        temp.prev.next = <span class="hljs-literal">null</span>;
    }
}
</code></div></div></pre><p><strong>Time Complexity:</strong> O(n)</p><hr><h3><strong>Circular Linked List Operations:</strong></h3><h4><strong>Insert at the End:</strong></h4><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">void</span> <span class="hljs-title function_">insertAtEnd</span><span class="hljs-params">(<span class="hljs-type">int</span> data)</span> {
    <span class="hljs-type">Node</span> <span class="hljs-variable">newNode</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">Node</span>(data);
    <span class="hljs-keyword">if</span> (head == <span class="hljs-literal">null</span>) {
        head = newNode;
        newNode.next = head;
    } <span class="hljs-keyword">else</span> {
        <span class="hljs-type">Node</span> <span class="hljs-variable">temp</span> <span class="hljs-operator">=</span> head;
        <span class="hljs-keyword">while</span> (temp.next != head) temp = temp.next;
        temp.next = newNode;
        newNode.next = head;
    }
}
</code></div></div></pre><hr><h2><strong>3. Differences Between Arrays and Linked Lists:</strong></h2><table><thead><tr><th><strong>Feature</strong></th><th><strong>Arrays</strong></th><th><strong>Linked Lists</strong></th></tr></thead><tbody><tr><td><strong>Memory</strong></td><td>Contiguous</td><td>Non-contiguous</td></tr><tr><td><strong>Access Time</strong></td><td>O(1) (Random Access)</td><td>O(n) (Sequential Access)</td></tr><tr><td><strong>Insertion/Deletion</strong></td><td>O(n)</td><td>O(1) at head, O(n) at tail</td></tr><tr><td><strong>Size</strong></td><td>Fixed</td><td>Dynamic</td></tr><tr><td><strong>Extra Memory</strong></td><td>No</td><td>Requires extra memory for pointers</td></tr></tbody></table><hr><h2><strong>4. Time and Space Complexities of Linked List Operations</strong></h2><table><thead><tr><th><strong>Operation</strong></th><th><strong>Singly Linked List</strong></th><th><strong>Doubly Linked List</strong></th></tr></thead><tbody><tr><td>Insert at Head</td><td>O(1)</td><td>O(1)</td></tr><tr><td>Insert at Tail</td><td>O(n)</td><td>O(n)</td></tr><tr><td>Delete from Head</td><td>O(1)</td><td>O(1)</td></tr><tr><td>Delete from Tail</td><td>O(n)</td><td>O(n)</td></tr><tr><td>Search</td><td>O(n)</td><td>O(n)</td></tr><tr><td>Space Complexity</td><td>O(n)</td><td>O(n)</td></tr></tbody></table><hr><h2><strong>5. Recursive Operations on Linked Lists</strong></h2><h3><strong>Reversing a Singly Linked List (Recursive Approach):</strong></h3><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java">Node <span class="hljs-title function_">reverse</span><span class="hljs-params">(Node head)</span> {
    <span class="hljs-keyword">if</span> (head == <span class="hljs-literal">null</span> || head.next == <span class="hljs-literal">null</span>) <span class="hljs-keyword">return</span> head;
    <span class="hljs-type">Node</span> <span class="hljs-variable">newHead</span> <span class="hljs-operator">=</span> reverse(head.next);
    head.next.next = head;
    head.next = <span class="hljs-literal">null</span>;
    <span class="hljs-keyword">return</span> newHead;
}
</code></div></div></pre><p><strong>Time Complexity:</strong> O(n)<br><strong>Space Complexity:</strong> O(n) (due to recursion stack)</p><hr><h2><strong>6. Detecting a Cycle in a Linked List (Floyd’s Cycle Detection Algorithm):</strong></h2><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">boolean</span> <span class="hljs-title function_">hasCycle</span><span class="hljs-params">(Node head)</span> {
    <span class="hljs-keyword">if</span> (head == <span class="hljs-literal">null</span>) <span class="hljs-keyword">return</span> <span class="hljs-literal">false</span>;
    <span class="hljs-type">Node</span> <span class="hljs-variable">slow</span> <span class="hljs-operator">=</span> head, fast = head;
    <span class="hljs-keyword">while</span> (fast != <span class="hljs-literal">null</span> &amp;&amp; fast.next != <span class="hljs-literal">null</span>) {
        slow = slow.next;
        fast = fast.next.next;
        <span class="hljs-keyword">if</span> (slow == fast) <span class="hljs-keyword">return</span> <span class="hljs-literal">true</span>;
    }
    <span class="hljs-keyword">return</span> <span class="hljs-literal">false</span>;
}
</code></div></div></pre><p><strong>Time Complexity:</strong> O(n)<br><strong>Space Complexity:</strong> O(1)</p><hr><h2><strong>7. Memory Management Tips for Linked Lists:</strong></h2><ul><li><strong>Set unused pointers to null</strong> to avoid memory leaks.</li><li><strong>Garbage collection</strong> in Java will handle unreferenced nodes, but always ensure that you remove unnecessary references.</li></ul><hr><h2><strong>8. Practical Applications of Linked Lists:</strong></h2><ul><li><strong>Operating Systems:</strong> Manage tasks using circular linked lists.</li><li><strong>Browser History:</strong> Doubly linked lists store forward and backward navigation states.</li><li><strong>Graph Implementations:</strong> Use adjacency lists for graph representation.</li><li><strong>Undo/Redo Functionality:</strong> Doubly linked lists store previous and next states.</li></ul><hr><h2><strong>9. Flashcards:</strong></h2><ol><li><p><strong>Q:</strong> What is the time complexity for inserting at the beginning of a singly linked list?<br><strong>A:</strong> O(1).</p></li><li><p><strong>Q:</strong> What is the difference between singly and circular linked lists?<br><strong>A:</strong> In a circular linked list, the last node points to the first node.</p></li><li><p><strong>Q:</strong> How can you reverse a linked list recursively?<br><strong>A:</strong> Use recursion to traverse to the end and swap the pointers while returning.</p></li><li><p><strong>Q:</strong> What algorithm detects cycles in linked lists?<br><strong>A:</strong> Floyd's Cycle Detection Algorithm.</p></li></ol><hr><h2><strong>10. Practice Questions:</strong></h2><ol><li>Implement a <strong>doubly circular linked list</strong> in Java.</li><li>Write a function to <strong>merge two sorted linked lists</strong>.</li><li>Explain the <strong>advantages of linked lists over arrays</strong>.</li><li>Implement <strong>Floyd's cycle detection</strong> algorithm.</li><li>Write a method to <strong>detect and remove cycles</strong> from a linked list.</li></ol><hr><p>That covers everything about <strong>linked lists</strong>! Would you like to proceed to <strong>stacks</strong>, or do you have any specific questions about linked lists?</p>

---



---

 
<h3><strong>Stacks: Complete Overview</strong></h3><h4><strong>What is a Stack?</strong></h4><p>A <strong>stack</strong> is a linear data structure that follows the <strong>LIFO (Last In, First Out)</strong> principle. The last element added is the first one to be removed. It is analogous to a stack of plates, where the top plate is removed first.</p><hr><h2><strong>1. Basic Operations on a Stack</strong></h2><ol><li><strong>Push</strong> – Add an element to the top of the stack.</li><li><strong>Pop</strong> – Remove and return the top element from the stack.</li><li><strong>Peek (Top)</strong> – View the top element without removing it.</li><li><strong>isEmpty</strong> – Check if the stack is empty.</li><li><strong>isFull</strong> – Check if the stack is full (in fixed-size stacks).</li></ol><hr><h2><strong>2. Implementation of Stack</strong></h2><h3><strong>A. Stack using Arrays</strong></h3><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">Stack</span> {
    <span class="hljs-type">int</span> size;
    <span class="hljs-type">int</span> top;
    <span class="hljs-type">int</span>[] stackArray;

    Stack(<span class="hljs-type">int</span> size) {
        <span class="hljs-built_in">this</span>.size = size;
        stackArray = <span class="hljs-keyword">new</span> <span class="hljs-title class_">int</span>[size];
        top = -<span class="hljs-number">1</span>;
    }

    <span class="hljs-keyword">void</span> <span class="hljs-title function_">push</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-keyword">if</span> (top == size - <span class="hljs-number">1</span>) {
            System.out.println(<span class="hljs-string">"Stack Overflow"</span>);
        } <span class="hljs-keyword">else</span> {
            stackArray[++top] = value;
        }
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">pop</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (top == -<span class="hljs-number">1</span>) {
            System.out.println(<span class="hljs-string">"Stack Underflow"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        } <span class="hljs-keyword">else</span> {
            <span class="hljs-keyword">return</span> stackArray[top--];
        }
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">peek</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (top == -<span class="hljs-number">1</span>) {
            System.out.println(<span class="hljs-string">"Stack is empty"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        } <span class="hljs-keyword">else</span> {
            <span class="hljs-keyword">return</span> stackArray[top];
        }
    }

    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isEmpty</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> top == -<span class="hljs-number">1</span>;
    }
}
</code></div></div></pre><hr><h3><strong>B. Stack using Linked List</strong></h3><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">StackNode</span> {
    <span class="hljs-type">int</span> data;
    StackNode next;

    StackNode(<span class="hljs-type">int</span> data) {
        <span class="hljs-built_in">this</span>.data = data;
        <span class="hljs-built_in">this</span>.next = <span class="hljs-literal">null</span>;
    }
}

<span class="hljs-keyword">class</span> <span class="hljs-title class_">Stack</span> {
    StackNode top;

    <span class="hljs-keyword">void</span> <span class="hljs-title function_">push</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-type">StackNode</span> <span class="hljs-variable">newNode</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">StackNode</span>(value);
        newNode.next = top;
        top = newNode;
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">pop</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (top == <span class="hljs-literal">null</span>) {
            System.out.println(<span class="hljs-string">"Stack Underflow"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        }
        <span class="hljs-type">int</span> <span class="hljs-variable">value</span> <span class="hljs-operator">=</span> top.data;
        top = top.next;
        <span class="hljs-keyword">return</span> value;
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">peek</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (top == <span class="hljs-literal">null</span>) {
            System.out.println(<span class="hljs-string">"Stack is empty"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        }
        <span class="hljs-keyword">return</span> top.data;
    }

    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isEmpty</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> top == <span class="hljs-literal">null</span>;
    }
}
</code></div></div></pre><hr><h2><strong>3. Time and Space Complexity of Stack Operations</strong></h2><table><thead><tr><th><strong>Operation</strong></th><th><strong>Array Implementation</strong></th><th><strong>Linked List Implementation</strong></th></tr></thead><tbody><tr><td>Push</td><td>O(1)</td><td>O(1)</td></tr><tr><td>Pop</td><td>O(1)</td><td>O(1)</td></tr><tr><td>Peek</td><td>O(1)</td><td>O(1)</td></tr><tr><td>isEmpty</td><td>O(1)</td><td>O(1)</td></tr><tr><td>Space</td><td>O(n)</td><td>O(n)</td></tr></tbody></table><hr><h2><strong>4. Applications of Stacks</strong></h2><ol><li><strong>Function Call Stack:</strong> Manages function calls and recursive operations.</li><li><strong>Expression Evaluation:</strong> Used to evaluate postfix expressions.</li><li><strong>Undo/Redo Operations:</strong> In text editors and IDEs.</li><li><strong>Parenthesis Matching:</strong> Check for balanced brackets in code.</li><li><strong>Browser History:</strong> Backtracking pages visited.</li></ol><hr><h2><strong>5. Infix to Postfix Conversion using Stack</strong></h2><ul><li><strong>Infix Expression:</strong> <code>A + B * C</code></li><li><strong>Postfix Expression:</strong> <code>A B C * +</code></li></ul><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">int</span> <span class="hljs-title function_">precedence</span><span class="hljs-params">(<span class="hljs-type">char</span> operator)</span> {
    <span class="hljs-keyword">switch</span> (operator) {
        <span class="hljs-keyword">case</span> <span class="hljs-string">'+'</span>:
        <span class="hljs-keyword">case</span> <span class="hljs-string">'-'</span>:
            <span class="hljs-keyword">return</span> <span class="hljs-number">1</span>;
        <span class="hljs-keyword">case</span> <span class="hljs-string">'*'</span>:
        <span class="hljs-keyword">case</span> <span class="hljs-string">'/'</span>:
            <span class="hljs-keyword">return</span> <span class="hljs-number">2</span>;
        <span class="hljs-keyword">default</span>:
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
    }
}

String <span class="hljs-title function_">infixToPostfix</span><span class="hljs-params">(String expression)</span> {
    Stack&lt;Character&gt; stack = <span class="hljs-keyword">new</span> <span class="hljs-title class_">Stack</span>&lt;&gt;();
    <span class="hljs-type">StringBuilder</span> <span class="hljs-variable">result</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">StringBuilder</span>();

    <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>; i &lt; expression.length(); i++) {
        <span class="hljs-type">char</span> <span class="hljs-variable">c</span> <span class="hljs-operator">=</span> expression.charAt(i);

        <span class="hljs-keyword">if</span> (Character.isLetterOrDigit(c)) {
            result.append(c);
        } <span class="hljs-keyword">else</span> <span class="hljs-keyword">if</span> (c == <span class="hljs-string">'('</span>) {
            stack.push(c);
        } <span class="hljs-keyword">else</span> <span class="hljs-keyword">if</span> (c == <span class="hljs-string">')'</span>) {
            <span class="hljs-keyword">while</span> (!stack.isEmpty() &amp;&amp; stack.peek() != <span class="hljs-string">'('</span>) {
                result.append(stack.pop());
            }
            stack.pop();
        } <span class="hljs-keyword">else</span> {
            <span class="hljs-keyword">while</span> (!stack.isEmpty() &amp;&amp; precedence(c) &lt;= precedence(stack.peek())) {
                result.append(stack.pop());
            }
            stack.push(c);
        }
    }

    <span class="hljs-keyword">while</span> (!stack.isEmpty()) {
        result.append(stack.pop());
    }
    <span class="hljs-keyword">return</span> result.toString();
}
</code></div></div></pre><hr><h2><strong>6. Expression Evaluation (Postfix Evaluation using Stack)</strong></h2><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">int</span> <span class="hljs-title function_">evaluatePostfix</span><span class="hljs-params">(String expression)</span> {
    Stack&lt;Integer&gt; stack = <span class="hljs-keyword">new</span> <span class="hljs-title class_">Stack</span>&lt;&gt;();

    <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>; i &lt; expression.length(); i++) {
        <span class="hljs-type">char</span> <span class="hljs-variable">c</span> <span class="hljs-operator">=</span> expression.charAt(i);

        <span class="hljs-keyword">if</span> (Character.isDigit(c)) {
            stack.push(c - <span class="hljs-string">'0'</span>); <span class="hljs-comment">// Convert char to int</span>
        } <span class="hljs-keyword">else</span> {
            <span class="hljs-type">int</span> <span class="hljs-variable">val1</span> <span class="hljs-operator">=</span> stack.pop();
            <span class="hljs-type">int</span> <span class="hljs-variable">val2</span> <span class="hljs-operator">=</span> stack.pop();

            <span class="hljs-keyword">switch</span> (c) {
                <span class="hljs-keyword">case</span> <span class="hljs-string">'+'</span>:
                    stack.push(val2 + val1);
                    <span class="hljs-keyword">break</span>;
                <span class="hljs-keyword">case</span> <span class="hljs-string">'-'</span>:
                    stack.push(val2 - val1);
                    <span class="hljs-keyword">break</span>;
                <span class="hljs-keyword">case</span> <span class="hljs-string">'*'</span>:
                    stack.push(val2 * val1);
                    <span class="hljs-keyword">break</span>;
                <span class="hljs-keyword">case</span> <span class="hljs-string">'/'</span>:
                    stack.push(val2 / val1);
                    <span class="hljs-keyword">break</span>;
            }
        }
    }
    <span class="hljs-keyword">return</span> stack.pop();
}
</code></div></div></pre><hr><h2><strong>7. Balanced Parenthesis Matching using Stack</strong></h2><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">boolean</span> <span class="hljs-title function_">isBalanced</span><span class="hljs-params">(String expression)</span> {
    Stack&lt;Character&gt; stack = <span class="hljs-keyword">new</span> <span class="hljs-title class_">Stack</span>&lt;&gt;();

    <span class="hljs-keyword">for</span> (<span class="hljs-type">char</span> c : expression.toCharArray()) {
        <span class="hljs-keyword">if</span> (c == <span class="hljs-string">'('</span> || c == <span class="hljs-string">'{'</span> || c == <span class="hljs-string">'['</span>) {
            stack.push(c);
        } <span class="hljs-keyword">else</span> <span class="hljs-keyword">if</span> (c == <span class="hljs-string">')'</span> || c == <span class="hljs-string">'}'</span> || c == <span class="hljs-string">']'</span>) {
            <span class="hljs-keyword">if</span> (stack.isEmpty()) <span class="hljs-keyword">return</span> <span class="hljs-literal">false</span>;
            <span class="hljs-type">char</span> <span class="hljs-variable">top</span> <span class="hljs-operator">=</span> stack.pop();
            <span class="hljs-keyword">if</span> ((c == <span class="hljs-string">')'</span> &amp;&amp; top != <span class="hljs-string">'('</span>) || (c == <span class="hljs-string">'}'</span> &amp;&amp; top != <span class="hljs-string">'{'</span>) || (c == <span class="hljs-string">']'</span> &amp;&amp; top != <span class="hljs-string">'['</span>)) {
                <span class="hljs-keyword">return</span> <span class="hljs-literal">false</span>;
            }
        }
    }
    <span class="hljs-keyword">return</span> stack.isEmpty();
}
</code></div></div></pre><hr><h2><strong>8. Flashcards</strong></h2><ol><li><p><strong>Q:</strong> What is the time complexity for <code>push()</code> in a stack?<br><strong>A:</strong> O(1).</p></li><li><p><strong>Q:</strong> How does a stack follow the LIFO principle?<br><strong>A:</strong> The last element pushed is the first to be popped.</p></li><li><p><strong>Q:</strong> Which data structure helps convert infix to postfix expressions?<br><strong>A:</strong> Stack.</p></li><li><p><strong>Q:</strong> What is a common use of a stack in programming?<br><strong>A:</strong> Function call management.</p></li></ol><hr><h2><strong>9. Practice Questions</strong></h2><ol><li>Implement a <strong>stack using a linked list</strong>.</li><li>Write a <strong>function to evaluate postfix expressions</strong>.</li><li>Use a <strong>stack to check if a string has balanced parentheses</strong>.</li><li>Convert <strong>infix to postfix using stack</strong>.</li><li>Explain the <strong>advantages of linked list-based stacks over arrays</strong>.</li></ol><hr><p>Would you like to move on to <strong>queues</strong> next or go deeper into any concept related to stacks?</p>

---


---

 
<h3><strong>Queues: Complete Overview</strong></h3><h4><strong>What is a Queue?</strong></h4><p>A <strong>queue</strong> is a linear data structure that follows the <strong>FIFO (First In, First Out)</strong> principle. This means the element inserted first is the first one to be removed, similar to a line at a ticket counter.</p><hr><h2><strong>1. Types of Queues</strong></h2><ol><li><p><strong>Simple Queue (Linear Queue):</strong></p><ul><li>Insertion at the rear (end).</li><li>Deletion from the front (beginning).</li><li>If the rear reaches the end of the array, no more insertions are allowed even if there is space at the front.</li></ul></li><li><p><strong>Circular Queue:</strong></p><ul><li>The rear wraps around to the front when it reaches the end, reusing available space.</li></ul></li><li><p><strong>Deque (Double-Ended Queue):</strong></p><ul><li>Insertion and deletion are allowed from both the front and rear.</li></ul></li><li><p><strong>Priority Queue:</strong></p><ul><li>Each element has a priority, and the highest priority element is served first.</li></ul></li></ol><hr><h2><strong>2. Basic Operations on a Queue</strong></h2><ol><li><strong>Enqueue:</strong> Add an element to the rear of the queue.</li><li><strong>Dequeue:</strong> Remove and return the front element from the queue.</li><li><strong>Peek (Front):</strong> View the element at the front without removing it.</li><li><strong>isEmpty:</strong> Check if the queue is empty.</li><li><strong>isFull:</strong> Check if the queue is full (in fixed-size queues).</li></ol><hr><h2><strong>3. Queue Implementation</strong></h2><h3><strong>A. Queue using Arrays</strong></h3><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">Queue</span> {
    <span class="hljs-type">int</span> front, rear, size;
    <span class="hljs-type">int</span>[] queueArray;

    Queue(<span class="hljs-type">int</span> capacity) {
        size = capacity;
        front = rear = -<span class="hljs-number">1</span>;
        queueArray = <span class="hljs-keyword">new</span> <span class="hljs-title class_">int</span>[size];
    }

    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isFull</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> rear == size - <span class="hljs-number">1</span>;
    }

    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isEmpty</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> front == -<span class="hljs-number">1</span> || front &gt; rear;
    }

    <span class="hljs-keyword">void</span> <span class="hljs-title function_">enqueue</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-keyword">if</span> (isFull()) {
            System.out.println(<span class="hljs-string">"Queue Overflow"</span>);
        } <span class="hljs-keyword">else</span> {
            <span class="hljs-keyword">if</span> (front == -<span class="hljs-number">1</span>) front = <span class="hljs-number">0</span>; <span class="hljs-comment">// First element being inserted</span>
            queueArray[++rear] = value;
        }
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">dequeue</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Queue Underflow"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        }
        <span class="hljs-keyword">return</span> queueArray[front++];
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">peek</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Queue is empty"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        }
        <span class="hljs-keyword">return</span> queueArray[front];
    }
}
</code></div></div></pre><hr><h3><strong>B. Circular Queue Implementation</strong></h3><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">CircularQueue</span> {
    <span class="hljs-type">int</span> front, rear, size;
    <span class="hljs-type">int</span>[] queueArray;

    CircularQueue(<span class="hljs-type">int</span> capacity) {
        size = capacity;
        front = rear = -<span class="hljs-number">1</span>;
        queueArray = <span class="hljs-keyword">new</span> <span class="hljs-title class_">int</span>[size];
    }

    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isFull</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> (rear + <span class="hljs-number">1</span>) % size == front;
    }

    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isEmpty</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> front == -<span class="hljs-number">1</span>;
    }

    <span class="hljs-keyword">void</span> <span class="hljs-title function_">enqueue</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-keyword">if</span> (isFull()) {
            System.out.println(<span class="hljs-string">"Queue Overflow"</span>);
        } <span class="hljs-keyword">else</span> {
            <span class="hljs-keyword">if</span> (front == -<span class="hljs-number">1</span>) front = <span class="hljs-number">0</span>;
            rear = (rear + <span class="hljs-number">1</span>) % size;
            queueArray[rear] = value;
        }
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">dequeue</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Queue Underflow"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        }
        <span class="hljs-type">int</span> <span class="hljs-variable">value</span> <span class="hljs-operator">=</span> queueArray[front];
        <span class="hljs-keyword">if</span> (front == rear) { <span class="hljs-comment">// Queue becomes empty after this operation</span>
            front = rear = -<span class="hljs-number">1</span>;
        } <span class="hljs-keyword">else</span> {
            front = (front + <span class="hljs-number">1</span>) % size;
        }
        <span class="hljs-keyword">return</span> value;
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">peek</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Queue is empty"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        }
        <span class="hljs-keyword">return</span> queueArray[front];
    }
}
</code></div></div></pre><hr><h3><strong>C. Queue using Linked List</strong></h3><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">Node</span> {
    <span class="hljs-type">int</span> data;
    Node next;

    Node(<span class="hljs-type">int</span> data) {
        <span class="hljs-built_in">this</span>.data = data;
        <span class="hljs-built_in">this</span>.next = <span class="hljs-literal">null</span>;
    }
}

<span class="hljs-keyword">class</span> <span class="hljs-title class_">LinkedListQueue</span> {
    Node front, rear;

    <span class="hljs-keyword">void</span> <span class="hljs-title function_">enqueue</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-type">Node</span> <span class="hljs-variable">newNode</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">Node</span>(value);
        <span class="hljs-keyword">if</span> (rear == <span class="hljs-literal">null</span>) {
            front = rear = newNode;
        } <span class="hljs-keyword">else</span> {
            rear.next = newNode;
            rear = newNode;
        }
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">dequeue</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (front == <span class="hljs-literal">null</span>) {
            System.out.println(<span class="hljs-string">"Queue Underflow"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        }
        <span class="hljs-type">int</span> <span class="hljs-variable">value</span> <span class="hljs-operator">=</span> front.data;
        front = front.next;
        <span class="hljs-keyword">if</span> (front == <span class="hljs-literal">null</span>) rear = <span class="hljs-literal">null</span>;
        <span class="hljs-keyword">return</span> value;
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">peek</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (front == <span class="hljs-literal">null</span>) {
            System.out.println(<span class="hljs-string">"Queue is empty"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        }
        <span class="hljs-keyword">return</span> front.data;
    }

    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isEmpty</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> front == <span class="hljs-literal">null</span>;
    }
}
</code></div></div></pre><hr><h2><strong>4. Time and Space Complexity of Queue Operations</strong></h2><table><thead><tr><th><strong>Operation</strong></th><th><strong>Array Implementation</strong></th><th><strong>Linked List Implementation</strong></th></tr></thead><tbody><tr><td>Enqueue</td><td>O(1)</td><td>O(1)</td></tr><tr><td>Dequeue</td><td>O(1)</td><td>O(1)</td></tr><tr><td>Peek</td><td>O(1)</td><td>O(1)</td></tr><tr><td>isEmpty</td><td>O(1)</td><td>O(1)</td></tr><tr><td>Space</td><td>O(n)</td><td>O(n)</td></tr></tbody></table><hr><h2><strong>5. Applications of Queues</strong></h2><ol><li><strong>CPU Scheduling:</strong> Processes are scheduled in the order they arrive.</li><li><strong>Printer Queue:</strong> Jobs are handled in the order they are added.</li><li><strong>Breadth-First Search (BFS):</strong> Used in graph traversal.</li><li><strong>Messaging Systems:</strong> Messages are queued for delivery.</li><li><strong>Call Center Systems:</strong> Calls are answered in the order they arrive.</li></ol><hr><h2><strong>6. Real-World Example: Ticketing System</strong></h2><ul><li><strong>Queue</strong> maintains customers waiting for tickets.</li><li>When a ticket is available, <strong>dequeue</strong> the customer from the front of the queue.</li></ul><hr><h2><strong>7. Priority Queue Implementation Example</strong></h2><p>In a <strong>priority queue</strong>, elements are dequeued based on priority rather than the order of insertion.</p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">PriorityQueue</span> {
    <span class="hljs-keyword">class</span> <span class="hljs-title class_">Node</span> {
        <span class="hljs-type">int</span> data, priority;
        Node next;

        Node(<span class="hljs-type">int</span> data, <span class="hljs-type">int</span> priority) {
            <span class="hljs-built_in">this</span>.data = data;
            <span class="hljs-built_in">this</span>.priority = priority;
            <span class="hljs-built_in">this</span>.next = <span class="hljs-literal">null</span>;
        }
    }

    Node front;

    <span class="hljs-keyword">void</span> <span class="hljs-title function_">enqueue</span><span class="hljs-params">(<span class="hljs-type">int</span> value, <span class="hljs-type">int</span> priority)</span> {
        <span class="hljs-type">Node</span> <span class="hljs-variable">newNode</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">Node</span>(value, priority);
        <span class="hljs-keyword">if</span> (front == <span class="hljs-literal">null</span> || front.priority &gt; priority) {
            newNode.next = front;
            front = newNode;
        } <span class="hljs-keyword">else</span> {
            <span class="hljs-type">Node</span> <span class="hljs-variable">temp</span> <span class="hljs-operator">=</span> front;
            <span class="hljs-keyword">while</span> (temp.next != <span class="hljs-literal">null</span> &amp;&amp; temp.next.priority &lt;= priority) {
                temp = temp.next;
            }
            newNode.next = temp.next;
            temp.next = newNode;
        }
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">dequeue</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (front == <span class="hljs-literal">null</span>) {
            System.out.println(<span class="hljs-string">"Queue Underflow"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        }
        <span class="hljs-type">int</span> <span class="hljs-variable">value</span> <span class="hljs-operator">=</span> front.data;
        front = front.next;
        <span class="hljs-keyword">return</span> value;
    }
}
</code></div></div></pre><hr><h2><strong>8. Flashcards</strong></h2><ol><li><p><strong>Q:</strong> What is the difference between a linear queue and a circular queue?<br><strong>A:</strong> A circular queue reuses space by wrapping the rear to the front when the end is reached.</p></li><li><p><strong>Q:</strong> How does a priority queue differ from a regular queue?<br><strong>A:</strong> In a priority queue, elements are dequeued based on priority instead of insertion order.</p></li><li><p><strong>Q:</strong> What is the time complexity of <code>enqueue()</code> and <code>dequeue()</code> in a queue?<br><strong>A:</strong> O(1).</p></li></ol><hr><h2><strong>9. Practice Questions</strong></h2><ol><li>Implement a <strong>circular queue</strong> using arrays.</li><li>Write a <strong>linked list-based queue</strong> implementation.</li><li>Implement a <strong>priority queue</strong> and explain how it works.</li><li>Compare <strong>circular and linear queues</strong>. Which is more efficient?</li><li>Explain how <strong>BFS</strong> uses a queue in graph traversal.</li></ol><hr><p>Would you like to dive deeper into <strong>circular queues</strong> or proceed to the next data structure?</p>

---



---

 
<p>Got it! Let’s dive deeper into <strong>Queues</strong> with more examples, concepts, and tricky scenarios to ensure you're fully prepared for tough exam questions.</p><hr><h2><strong>Circular Queue: Why It’s Important and Tricky Points</strong></h2><h3><strong>Circular Queue Deep Dive</strong></h3><p>A <strong>circular queue</strong> solves the problem of wasted space in a linear queue. When the rear reaches the end of the array, it wraps around to use the space at the front.</p><hr><h3><strong>Circular Queue Key Concept</strong></h3><ul><li><strong>Enqueue (Insertion)</strong>: If the rear reaches the last index, it wraps around to index 0.</li><li><strong>Dequeue (Deletion)</strong>: When the front moves forward, it wraps around to the start after the end is reached.</li><li><strong>Full Queue Condition:</strong> When <code>(rear + 1) % size == front</code></li><li><strong>Empty Queue Condition:</strong> When <code>front == -1</code></li></ul><hr><h3><strong>Circular Queue Code with Edge Cases</strong></h3><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">CircularQueue</span> {
    <span class="hljs-type">int</span> front, rear, size;
    <span class="hljs-type">int</span>[] queueArray;

    CircularQueue(<span class="hljs-type">int</span> capacity) {
        size = capacity;
        front = rear = -<span class="hljs-number">1</span>;
        queueArray = <span class="hljs-keyword">new</span> <span class="hljs-title class_">int</span>[size];
    }

    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isFull</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> (rear + <span class="hljs-number">1</span>) % size == front;
    }

    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isEmpty</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> front == -<span class="hljs-number">1</span>;
    }

    <span class="hljs-keyword">void</span> <span class="hljs-title function_">enqueue</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-keyword">if</span> (isFull()) {
            System.out.println(<span class="hljs-string">"Queue Overflow"</span>);
            <span class="hljs-keyword">return</span>;
        }
        <span class="hljs-keyword">if</span> (front == -<span class="hljs-number">1</span>) front = <span class="hljs-number">0</span>; <span class="hljs-comment">// First element insertion</span>
        rear = (rear + <span class="hljs-number">1</span>) % size;   <span class="hljs-comment">// Wrap rear if needed</span>
        queueArray[rear] = value;
        System.out.println(<span class="hljs-string">"Inserted "</span> + value);
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">dequeue</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Queue Underflow"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        }
        <span class="hljs-type">int</span> <span class="hljs-variable">value</span> <span class="hljs-operator">=</span> queueArray[front];
        <span class="hljs-keyword">if</span> (front == rear) { <span class="hljs-comment">// Queue becomes empty</span>
            front = rear = -<span class="hljs-number">1</span>;
        } <span class="hljs-keyword">else</span> {
            front = (front + <span class="hljs-number">1</span>) % size; <span class="hljs-comment">// Wrap front if needed</span>
        }
        System.out.println(<span class="hljs-string">"Removed "</span> + value);
        <span class="hljs-keyword">return</span> value;
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">peek</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Queue is empty"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        }
        <span class="hljs-keyword">return</span> queueArray[front];
    }
    
    <span class="hljs-keyword">void</span> <span class="hljs-title function_">displayQueue</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Queue is empty"</span>);
            <span class="hljs-keyword">return</span>;
        }
        System.out.print(<span class="hljs-string">"Queue elements: "</span>);
        <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> front; i != rear; i = (i + <span class="hljs-number">1</span>) % size) {
            System.out.print(queueArray[i] + <span class="hljs-string">" "</span>);
        }
        System.out.println(queueArray[rear]); <span class="hljs-comment">// Print the last element</span>
    }
}
</code></div></div></pre><hr><h3><strong>Edge Cases and Solutions</strong></h3><ol><li><p><strong>What happens if both front and rear point to the same index?</strong></p><ul><li>If <code>front == rear</code>, it means only one element is in the queue.</li></ul></li><li><p><strong>How to detect a full queue correctly?</strong></p><ul><li>Use <code>(rear + 1) % size == front</code> to detect a full queue.</li><li>This approach ensures no element overwrites another.</li></ul></li><li><p><strong>What if <code>dequeue()</code> is called on an empty queue?</strong></p><ul><li>Handle this gracefully by checking <code>isEmpty()</code>.</li></ul></li></ol><hr><h3><strong>Time and Space Complexity in Circular Queue</strong></h3><ul><li><strong>Enqueue:</strong> O(1)</li><li><strong>Dequeue:</strong> O(1)</li><li><strong>Space:</strong> O(n) (where n is the size of the queue)</li></ul><hr><h3><strong>Trick Question for Exam: Detecting Circular Queue Overflow</strong></h3><ul><li>If your queue size is <strong>5</strong>, inserting <strong>6</strong> elements will overflow.</li><li>This is tricky because, in a circular queue, <strong>rear wraps around</strong>, so students often forget to handle overflow conditions.</li></ul><hr><h2><strong>Deque (Double-Ended Queue) Deep Dive</strong></h2><p>A <strong>Deque</strong> (pronounced as "deck") allows insertion and deletion from both ends, unlike a simple queue.</p><hr><h3><strong>Types of Deques</strong></h3><ol><li><strong>Input-Restricted Deque:</strong> Insertion allowed only at one end, but deletion from both ends.</li><li><strong>Output-Restricted Deque:</strong> Deletion allowed only at one end, but insertion at both ends.</li></ol><hr><h3><strong>Code Example for Deque Using Arrays</strong></h3><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">Deque</span> {
    <span class="hljs-type">int</span> front, rear, size;
    <span class="hljs-type">int</span>[] dequeArray;

    Deque(<span class="hljs-type">int</span> capacity) {
        size = capacity;
        front = -<span class="hljs-number">1</span>;
        rear = <span class="hljs-number">0</span>;
        dequeArray = <span class="hljs-keyword">new</span> <span class="hljs-title class_">int</span>[size];
    }

    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isFull</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> (front == <span class="hljs-number">0</span> &amp;&amp; rear == size - <span class="hljs-number">1</span>) || (front == rear + <span class="hljs-number">1</span>);
    }

    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isEmpty</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> front == -<span class="hljs-number">1</span>;
    }

    <span class="hljs-keyword">void</span> <span class="hljs-title function_">insertFront</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-keyword">if</span> (isFull()) {
            System.out.println(<span class="hljs-string">"Deque Overflow"</span>);
            <span class="hljs-keyword">return</span>;
        }
        <span class="hljs-keyword">if</span> (front == -<span class="hljs-number">1</span>) { <span class="hljs-comment">// First element</span>
            front = rear = <span class="hljs-number">0</span>;
        } <span class="hljs-keyword">else</span> <span class="hljs-keyword">if</span> (front == <span class="hljs-number">0</span>) {
            front = size - <span class="hljs-number">1</span>; <span class="hljs-comment">// Wrap around</span>
        } <span class="hljs-keyword">else</span> {
            front--;
        }
        dequeArray[front] = value;
        System.out.println(<span class="hljs-string">"Inserted "</span> + value + <span class="hljs-string">" at front"</span>);
    }

    <span class="hljs-keyword">void</span> <span class="hljs-title function_">insertRear</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-keyword">if</span> (isFull()) {
            System.out.println(<span class="hljs-string">"Deque Overflow"</span>);
            <span class="hljs-keyword">return</span>;
        }
        <span class="hljs-keyword">if</span> (front == -<span class="hljs-number">1</span>) { <span class="hljs-comment">// First element</span>
            front = rear = <span class="hljs-number">0</span>;
        } <span class="hljs-keyword">else</span> <span class="hljs-keyword">if</span> (rear == size - <span class="hljs-number">1</span>) {
            rear = <span class="hljs-number">0</span>; <span class="hljs-comment">// Wrap around</span>
        } <span class="hljs-keyword">else</span> {
            rear++;
        }
        dequeArray[rear] = value;
        System.out.println(<span class="hljs-string">"Inserted "</span> + value + <span class="hljs-string">" at rear"</span>);
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">deleteFront</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Deque Underflow"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        }
        <span class="hljs-type">int</span> <span class="hljs-variable">value</span> <span class="hljs-operator">=</span> dequeArray[front];
        <span class="hljs-keyword">if</span> (front == rear) { <span class="hljs-comment">// Queue becomes empty</span>
            front = rear = -<span class="hljs-number">1</span>;
        } <span class="hljs-keyword">else</span> <span class="hljs-keyword">if</span> (front == size - <span class="hljs-number">1</span>) {
            front = <span class="hljs-number">0</span>; <span class="hljs-comment">// Wrap around</span>
        } <span class="hljs-keyword">else</span> {
            front++;
        }
        System.out.println(<span class="hljs-string">"Removed "</span> + value + <span class="hljs-string">" from front"</span>);
        <span class="hljs-keyword">return</span> value;
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">deleteRear</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Deque Underflow"</span>);
            <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>;
        }
        <span class="hljs-type">int</span> <span class="hljs-variable">value</span> <span class="hljs-operator">=</span> dequeArray[rear];
        <span class="hljs-keyword">if</span> (front == rear) { <span class="hljs-comment">// Queue becomes empty</span>
            front = rear = -<span class="hljs-number">1</span>;
        } <span class="hljs-keyword">else</span> <span class="hljs-keyword">if</span> (rear == <span class="hljs-number">0</span>) {
            rear = size - <span class="hljs-number">1</span>; <span class="hljs-comment">// Wrap around</span>
        } <span class="hljs-keyword">else</span> {
            rear--;
        }
        System.out.println(<span class="hljs-string">"Removed "</span> + value + <span class="hljs-string">" from rear"</span>);
        <span class="hljs-keyword">return</span> value;
    }
}
</code></div></div></pre><hr><h2><strong>Applications of Deques</strong></h2><ul><li><strong>Palindrome Checker:</strong> Use a deque to compare characters from both ends of a string.</li><li><strong>Sliding Window Problems:</strong> Deque is used to track maximum/minimum values in a sliding window.</li></ul><hr><h2><strong>Advanced Exam Question Example</strong></h2><p><strong>Q:</strong> Implement a circular queue that holds only prime numbers. If a non-prime number is enqueued, reject it.</p><hr><h2><strong>How to Ace Tough Exam Questions?</strong></h2><ol><li><p><strong>Understand Queue Behavior Thoroughly:</strong></p><ul><li>Know how both linear and circular queues behave.</li><li>Be able to explain wrapping around logic clearly in code.</li></ul></li><li><p><strong>Practice Deque Operations:</strong></p><ul><li>Many tough exam questions combine queue logic with stacks or deques.</li></ul></li><li><p><strong>Time Management in Exams:</strong></p><ul><li>Keep solutions to O(1) for each queue operation to avoid unnecessary overhead.</li></ul></li></ol><hr><h2><strong>Next Steps</strong></h2><p>Would you like to:</p><ol><li><strong>Practice tricky queue-based problems</strong> from competitive coding?</li><li><strong>Move on to the next data structure</strong>, like <strong>Stacks</strong>, or go even deeper into Priority Queues?</li></ol><p>Let me know how you want to proceed!</p>

---



---

 
<p>Great! Let’s continue covering <strong>Queues</strong> deeply so you're fully prepared. After all topics are done, we’ll dive into <strong>tricky questions</strong> for review.</p><hr><h2><strong>Queues</strong></h2><h3>1. <strong>Concept of Queues</strong></h3><p>A <strong>queue</strong> is a linear data structure that follows the <strong>FIFO (First In, First Out)</strong> principle. The first element inserted is the first to be removed, similar to standing in a line.</p><hr><h3>2. <strong>Types of Queues</strong></h3><ol><li><p><strong>Simple Queue:</strong></p><ul><li>Standard queue with insertion at the <strong>rear</strong> and deletion from the <strong>front</strong>.</li></ul></li><li><p><strong>Circular Queue:</strong></p><ul><li>The last position connects to the first, forming a <strong>circle</strong>. Efficient in managing memory by reusing emptied spaces.</li></ul></li><li><p><strong>Deque (Double-ended Queue):</strong></p><ul><li>Insertion and deletion can occur at <strong>both ends</strong> (front and rear).</li></ul></li><li><p><strong>Priority Queue:</strong></p><ul><li>Each element has a <strong>priority</strong>, and elements are dequeued based on their priority instead of arrival time.</li></ul></li></ol><hr><h3>3. <strong>Operations in a Queue</strong></h3><ul><li><strong>Enqueue:</strong> Add an element to the rear of the queue.</li><li><strong>Dequeue:</strong> Remove an element from the front.</li><li><strong>Peek/Front:</strong> View the element at the front without removing it.</li><li><strong>isEmpty:</strong> Check if the queue is empty.</li></ul><hr><h3>4. <strong>Queue Implementation in Java (Using Arrays)</strong></h3><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">Queue</span> {
    <span class="hljs-keyword">private</span> <span class="hljs-type">int</span>[] arr;
    <span class="hljs-keyword">private</span> <span class="hljs-type">int</span> front, rear, size, capacity;

    <span class="hljs-keyword">public</span> <span class="hljs-title function_">Queue</span><span class="hljs-params">(<span class="hljs-type">int</span> capacity)</span> {
        <span class="hljs-built_in">this</span>.capacity = capacity;
        arr = <span class="hljs-keyword">new</span> <span class="hljs-title class_">int</span>[capacity];
        front = size = <span class="hljs-number">0</span>;
        rear = capacity - <span class="hljs-number">1</span>;
    }

    <span class="hljs-comment">// Check if the queue is full</span>
    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isFull</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> size == capacity;
    }

    <span class="hljs-comment">// Check if the queue is empty</span>
    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isEmpty</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> size == <span class="hljs-number">0</span>;
    }

    <span class="hljs-comment">// Enqueue operation</span>
    <span class="hljs-keyword">void</span> <span class="hljs-title function_">enqueue</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-keyword">if</span> (isFull()) {
            System.out.println(<span class="hljs-string">"Queue is full"</span>);
            <span class="hljs-keyword">return</span>;
        }
        rear = (rear + <span class="hljs-number">1</span>) % capacity;
        arr[rear] = value;
        size++;
        System.out.println(value + <span class="hljs-string">" enqueued"</span>);
    }

    <span class="hljs-comment">// Dequeue operation</span>
    <span class="hljs-type">int</span> <span class="hljs-title function_">dequeue</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Queue is empty"</span>);
            <span class="hljs-keyword">return</span> Integer.MIN_VALUE;
        }
        <span class="hljs-type">int</span> <span class="hljs-variable">value</span> <span class="hljs-operator">=</span> arr[front];
        front = (front + <span class="hljs-number">1</span>) % capacity;
        size--;
        <span class="hljs-keyword">return</span> value;
    }

    <span class="hljs-comment">// Peek operation</span>
    <span class="hljs-type">int</span> <span class="hljs-title function_">peek</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Queue is empty"</span>);
            <span class="hljs-keyword">return</span> Integer.MIN_VALUE;
        }
        <span class="hljs-keyword">return</span> arr[front];
    }
}
</code></div></div></pre><hr><h3>5. <strong>Queue Implementation in Java (Using Linked List)</strong></h3><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">import</span> java.util.NoSuchElementException;

<span class="hljs-keyword">class</span> <span class="hljs-title class_">Node</span> {
    <span class="hljs-type">int</span> data;
    Node next;

    <span class="hljs-keyword">public</span> <span class="hljs-title function_">Node</span><span class="hljs-params">(<span class="hljs-type">int</span> data)</span> {
        <span class="hljs-built_in">this</span>.data = data;
        <span class="hljs-built_in">this</span>.next = <span class="hljs-literal">null</span>;
    }
}

<span class="hljs-keyword">class</span> <span class="hljs-title class_">LinkedQueue</span> {
    <span class="hljs-keyword">private</span> Node front, rear;

    <span class="hljs-keyword">public</span> <span class="hljs-title function_">LinkedQueue</span><span class="hljs-params">()</span> {
        front = rear = <span class="hljs-literal">null</span>;
    }

    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isEmpty</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> front == <span class="hljs-literal">null</span>;
    }

    <span class="hljs-keyword">void</span> <span class="hljs-title function_">enqueue</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-type">Node</span> <span class="hljs-variable">newNode</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">Node</span>(value);
        <span class="hljs-keyword">if</span> (rear != <span class="hljs-literal">null</span>) {
            rear.next = newNode;
        }
        rear = newNode;
        <span class="hljs-keyword">if</span> (front == <span class="hljs-literal">null</span>) {
            front = rear;
        }
        System.out.println(value + <span class="hljs-string">" enqueued"</span>);
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">dequeue</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) <span class="hljs-keyword">throw</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">NoSuchElementException</span>(<span class="hljs-string">"Queue is empty"</span>);
        <span class="hljs-type">int</span> <span class="hljs-variable">value</span> <span class="hljs-operator">=</span> front.data;
        front = front.next;
        <span class="hljs-keyword">if</span> (front == <span class="hljs-literal">null</span>) rear = <span class="hljs-literal">null</span>;
        <span class="hljs-keyword">return</span> value;
    }

    <span class="hljs-type">int</span> <span class="hljs-title function_">peek</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) <span class="hljs-keyword">throw</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">NoSuchElementException</span>(<span class="hljs-string">"Queue is empty"</span>);
        <span class="hljs-keyword">return</span> front.data;
    }
}
</code></div></div></pre><hr><h3>6. <strong>Time and Space Complexity</strong></h3><ul><li><strong>Enqueue:</strong> O(1)</li><li><strong>Dequeue:</strong> O(1)</li><li><strong>Peek:</strong> O(1)</li><li><strong>isEmpty:</strong> O(1)</li></ul><p>Space Complexity: O(n) for n elements in the queue.</p><hr><h3>7. <strong>Applications of Queues</strong></h3><ul><li><strong>Task Scheduling:</strong> Process scheduling in operating systems.</li><li><strong>Breadth-First Search (BFS):</strong> In graph algorithms.</li><li><strong>Printer Queues:</strong> Handling multiple print jobs.</li><li><strong>Handling Requests:</strong> Web servers manage client requests using queues.</li></ul><hr><h3>8. <strong>Comparing Queue Types</strong></h3><table><thead><tr><th><strong>Queue Type</strong></th><th><strong>Insertion</strong></th><th><strong>Deletion</strong></th><th><strong>Special Feature</strong></th></tr></thead><tbody><tr><td>Simple Queue</td><td>Rear</td><td>Front</td><td>Basic FIFO functionality</td></tr><tr><td>Circular Queue</td><td>Rear (Wraps Around)</td><td>Front</td><td>Efficient use of memory</td></tr><tr><td>Deque</td><td>Front and Rear</td><td>Front and Rear</td><td>Two-way insertion/deletion</td></tr><tr><td>Priority Queue</td><td>Based on priority</td><td>Based on priority</td><td>Prioritizes certain elements</td></tr></tbody></table><hr><h3>9. <strong>Flashcards</strong></h3><ol><li><p><strong>What is the principle of a queue?</strong></p><ul><li>First In, First Out (FIFO).</li></ul></li><li><p><strong>How does a circular queue differ from a simple queue?</strong></p><ul><li>In a circular queue, the last position wraps around to the first.</li></ul></li><li><p><strong>What is the time complexity of enqueue and dequeue operations?</strong></p><ul><li>O(1).</li></ul></li><li><p><strong>Name a real-world example where queues are used.</strong></p><ul><li>Process scheduling in operating systems.</li></ul></li><li><p><strong>How is a priority queue different from a regular queue?</strong></p><ul><li>Elements are dequeued based on priority, not order of arrival.</li></ul></li></ol><hr><h3>10. <strong>Practice Questions</strong></h3><ol><li><strong>What happens if you try to enqueue an element into a full queue?</strong></li><li><strong>Write a Java program to implement a circular queue.</strong></li><li><strong>Explain how a queue can be used to perform a Breadth-First Search (BFS).</strong></li><li><strong>What is the difference between a Deque and a Priority Queue?</strong></li><li><strong>Implement a priority queue in Java.</strong></li></ol><hr><h3>11. <strong>Tips and Tricks</strong></h3><ul><li>Use <strong>modulus operation</strong> for circular queues to wrap around the rear pointer.</li><li>For priority queues, always think of <strong>heap-based implementations</strong> for better efficiency.</li><li>In BFS problems, <strong>think of each node as an element in a queue</strong> to visualize the traversal.</li></ul><hr><p>Queue concepts are often tricky but essential for <strong>OS, networking, and algorithm-related questions</strong>. Make sure to practice coding both <strong>array-based and linked-list-based queues</strong> to handle any twist your teacher might throw your way!</p><p>Let me know if you’re ready to move to <strong>Sorting Algorithms</strong>!</p>

---


---

 
<p>Great! Now let's dive into <strong>Stacks</strong> in depth, ensuring you have a complete understanding. After that, we’ll proceed with a tricky question review.</p><hr><h2><strong>Stacks</strong></h2><h3>1. <strong>Concept of Stacks</strong></h3><p>A <strong>stack</strong> is a linear data structure that follows the <strong>LIFO (Last In, First Out)</strong> principle. The last element added is the first to be removed. It’s like stacking plates: the last plate placed on top is the first one to be removed.</p><hr><h3>2. <strong>Applications of Stacks</strong></h3><ul><li><strong>Function Call Management:</strong> Used in recursion to store function calls.</li><li><strong>Expression Evaluation and Conversion:</strong> Infix to Postfix/Prefix conversion and evaluation.</li><li><strong>Undo Operations:</strong> In editors or applications to reverse previous actions.</li><li><strong>Browser Back/Forward Navigation:</strong> Keeps history of visited pages.</li></ul><hr><h3>3. <strong>Operations on a Stack</strong></h3><ol><li><strong>Push:</strong> Add an element to the top of the stack.</li><li><strong>Pop:</strong> Remove the top element from the stack.</li><li><strong>Peek/Top:</strong> View the top element without removing it.</li><li><strong>isEmpty:</strong> Check if the stack is empty.</li></ol><hr><h3>4. <strong>Types of Stacks</strong></h3><ol><li><strong>Array-based Stack:</strong><ul><li>Uses a fixed-size array for storing elements.</li></ul></li><li><strong>Linked List-based Stack:</strong><ul><li>Uses a linked list where each node contains an element and a reference to the next node.</li></ul></li></ol><hr><h3>5. <strong>Stack Implementation in Java (Array-based)</strong></h3><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">Stack</span> {
    <span class="hljs-keyword">private</span> <span class="hljs-type">int</span> arr[];
    <span class="hljs-keyword">private</span> <span class="hljs-type">int</span> top;
    <span class="hljs-keyword">private</span> <span class="hljs-type">int</span> capacity;

    <span class="hljs-comment">// Constructor to initialize the stack</span>
    Stack(<span class="hljs-type">int</span> size) {
        arr = <span class="hljs-keyword">new</span> <span class="hljs-title class_">int</span>[size];
        capacity = size;
        top = -<span class="hljs-number">1</span>;
    }

    <span class="hljs-comment">// Push operation</span>
    <span class="hljs-keyword">void</span> <span class="hljs-title function_">push</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-keyword">if</span> (isFull()) {
            System.out.println(<span class="hljs-string">"Stack Overflow"</span>);
            <span class="hljs-keyword">return</span>;
        }
        arr[++top] = value;
        System.out.println(value + <span class="hljs-string">" pushed to stack"</span>);
    }

    <span class="hljs-comment">// Pop operation</span>
    <span class="hljs-type">int</span> <span class="hljs-title function_">pop</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Stack Underflow"</span>);
            <span class="hljs-keyword">return</span> Integer.MIN_VALUE;
        }
        <span class="hljs-keyword">return</span> arr[top--];
    }

    <span class="hljs-comment">// Peek operation</span>
    <span class="hljs-type">int</span> <span class="hljs-title function_">peek</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Stack is empty"</span>);
            <span class="hljs-keyword">return</span> Integer.MIN_VALUE;
        }
        <span class="hljs-keyword">return</span> arr[top];
    }

    <span class="hljs-comment">// Check if the stack is empty</span>
    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isEmpty</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> top == -<span class="hljs-number">1</span>;
    }

    <span class="hljs-comment">// Check if the stack is full</span>
    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isFull</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> top == capacity - <span class="hljs-number">1</span>;
    }
}
</code></div></div></pre><hr><h3>6. <strong>Stack Implementation in Java (Linked List-based)</strong></h3><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">Node</span> {
    <span class="hljs-type">int</span> data;
    Node next;

    Node(<span class="hljs-type">int</span> data) {
        <span class="hljs-built_in">this</span>.data = data;
        next = <span class="hljs-literal">null</span>;
    }
}

<span class="hljs-keyword">class</span> <span class="hljs-title class_">LinkedStack</span> {
    <span class="hljs-keyword">private</span> Node top;

    <span class="hljs-comment">// Constructor</span>
    LinkedStack() {
        top = <span class="hljs-literal">null</span>;
    }

    <span class="hljs-comment">// Push operation</span>
    <span class="hljs-keyword">void</span> <span class="hljs-title function_">push</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-type">Node</span> <span class="hljs-variable">newNode</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">Node</span>(value);
        newNode.next = top;
        top = newNode;
        System.out.println(value + <span class="hljs-string">" pushed to stack"</span>);
    }

    <span class="hljs-comment">// Pop operation</span>
    <span class="hljs-type">int</span> <span class="hljs-title function_">pop</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Stack Underflow"</span>);
            <span class="hljs-keyword">return</span> Integer.MIN_VALUE;
        }
        <span class="hljs-type">int</span> <span class="hljs-variable">value</span> <span class="hljs-operator">=</span> top.data;
        top = top.next;
        <span class="hljs-keyword">return</span> value;
    }

    <span class="hljs-comment">// Peek operation</span>
    <span class="hljs-type">int</span> <span class="hljs-title function_">peek</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Stack is empty"</span>);
            <span class="hljs-keyword">return</span> Integer.MIN_VALUE;
        }
        <span class="hljs-keyword">return</span> top.data;
    }

    <span class="hljs-comment">// Check if the stack is empty</span>
    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isEmpty</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> top == <span class="hljs-literal">null</span>;
    }
}
</code></div></div></pre><hr><h3>7. <strong>Time and Space Complexity</strong></h3><ul><li><strong>Push:</strong> O(1)</li><li><strong>Pop:</strong> O(1)</li><li><strong>Peek:</strong> O(1)</li></ul><p>Space Complexity:</p><ul><li><strong>Array-based Stack:</strong> O(n)</li><li><strong>Linked List-based Stack:</strong> O(n)</li></ul><hr><h3>8. <strong>Infix, Prefix, and Postfix Expressions</strong></h3><ul><li><strong>Infix Expression:</strong> Operators are between operands, e.g., <code>A + B</code>.</li><li><strong>Prefix Expression:</strong> Operators are before operands, e.g., <code>+ A B</code>.</li><li><strong>Postfix Expression:</strong> Operators are after operands, e.g., <code>A B +</code>.</li></ul><p><strong>Stack</strong> plays a crucial role in converting infix expressions to postfix or prefix and evaluating them.</p><hr><h3>9. <strong>Practical Example – Balancing Parentheses</strong></h3><p>Stacks are used to check if <strong>parentheses</strong> in an expression are balanced.<br>Example:</p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">import</span> java.util.Stack;

<span class="hljs-keyword">class</span> <span class="hljs-title class_">BalancedParentheses</span> {
    <span class="hljs-keyword">static</span> <span class="hljs-type">boolean</span> <span class="hljs-title function_">isBalanced</span><span class="hljs-params">(String expr)</span> {
        Stack&lt;Character&gt; stack = <span class="hljs-keyword">new</span> <span class="hljs-title class_">Stack</span>&lt;&gt;();

        <span class="hljs-keyword">for</span> (<span class="hljs-type">char</span> c : expr.toCharArray()) {
            <span class="hljs-keyword">if</span> (c == <span class="hljs-string">'('</span> || c == <span class="hljs-string">'{'</span> || c == <span class="hljs-string">'['</span>) {
                stack.push(c);
            } <span class="hljs-keyword">else</span> <span class="hljs-keyword">if</span> (c == <span class="hljs-string">')'</span> || c == <span class="hljs-string">'}'</span> || c == <span class="hljs-string">']'</span>) {
                <span class="hljs-keyword">if</span> (stack.isEmpty()) <span class="hljs-keyword">return</span> <span class="hljs-literal">false</span>;
                <span class="hljs-type">char</span> <span class="hljs-variable">open</span> <span class="hljs-operator">=</span> stack.pop();
                <span class="hljs-keyword">if</span> ((c == <span class="hljs-string">')'</span> &amp;&amp; open != <span class="hljs-string">'('</span>) ||
                    (c == <span class="hljs-string">'}'</span> &amp;&amp; open != <span class="hljs-string">'{'</span>) ||
                    (c == <span class="hljs-string">']'</span> &amp;&amp; open != <span class="hljs-string">'['</span>)) {
                    <span class="hljs-keyword">return</span> <span class="hljs-literal">false</span>;
                }
            }
        }
        <span class="hljs-keyword">return</span> stack.isEmpty();
    }

    <span class="hljs-keyword">public</span> <span class="hljs-keyword">static</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">main</span><span class="hljs-params">(String[] args)</span> {
        <span class="hljs-type">String</span> <span class="hljs-variable">expr</span> <span class="hljs-operator">=</span> <span class="hljs-string">"{[()]}"</span>;
        System.out.println(isBalanced(expr) ? <span class="hljs-string">"Balanced"</span> : <span class="hljs-string">"Not Balanced"</span>);
    }
}
</code></div></div></pre><hr><h3>10. <strong>Flashcards</strong></h3><ol><li><p><strong>What is the principle of a stack?</strong></p><ul><li>Last In, First Out (LIFO).</li></ul></li><li><p><strong>What is the time complexity of push and pop operations?</strong></p><ul><li>O(1).</li></ul></li><li><p><strong>How does a linked list-based stack differ from an array-based stack?</strong></p><ul><li>The linked list stack uses dynamic memory, while the array stack has a fixed size.</li></ul></li><li><p><strong>What is the use of the <code>peek()</code> operation?</strong></p><ul><li>It returns the top element without removing it.</li></ul></li><li><p><strong>How can you use a stack to check balanced parentheses?</strong></p><ul><li>Push opening brackets onto the stack, and pop them when a matching closing bracket appears.</li></ul></li></ol><hr><h3>11. <strong>Tips and Tricks</strong></h3><ul><li>In recursive functions, think of <strong>function calls being managed on a call stack</strong>.</li><li><strong>For expression evaluation</strong>, understand postfix and prefix conversions using stacks.</li><li><strong>Use linked-list-based stacks</strong> if memory needs to be dynamically managed.</li></ul><hr><h3>12. <strong>Practice Questions</strong></h3><ol><li><strong>What happens if you try to pop from an empty stack?</strong></li><li><strong>Write a Java program to reverse a string using a stack.</strong></li><li><strong>Explain the role of a stack in function calls and recursion.</strong></li><li><strong>Convert the infix expression <code>(A + B) * (C - D)</code> to postfix and prefix.</strong></li><li><strong>Implement an undo operation using a stack.</strong></li></ol><hr><h3>Summary</h3><p>Stacks are crucial for <strong>expression evaluation, memory management, and handling recursion</strong>. Make sure to practice both <strong>array-based and linked-list-based implementations</strong>, as they may appear in coding tasks and theoretical questions.</p><hr><p>Let me know if you're ready to proceed to <strong>recursion</strong>, or if you'd like to go over any tricky questions on stacks and queues!</p>

---


---

 
<h3><strong>Queues</strong> – A Deep Dive</h3><hr><h2>1. <strong>What is a Queue?</strong></h2><p>A <strong>queue</strong> is a linear data structure that follows the <strong>FIFO (First In, First Out)</strong> principle. This means the first element inserted into the queue will be the first one to be removed, just like people standing in a line.</p><hr><h2>2. <strong>Applications of Queues</strong></h2><ul><li><strong>Operating System:</strong> Process scheduling in CPU (Round-Robin scheduling).</li><li><strong>Network Data:</strong> Handling packets in routers.</li><li><strong>Print Queue:</strong> Managing print jobs sent to a printer.</li><li><strong>Breadth-First Search (BFS):</strong> Used in graph and tree traversal algorithms.</li></ul><hr><h2>3. <strong>Operations in a Queue</strong></h2><ol><li><strong>Enqueue:</strong> Add an element to the rear (end) of the queue.</li><li><strong>Dequeue:</strong> Remove an element from the front of the queue.</li><li><strong>Peek/Front:</strong> View the front element without removing it.</li><li><strong>isEmpty:</strong> Check if the queue is empty.</li></ol><hr><h2>4. <strong>Types of Queues</strong></h2><ol><li><p><strong>Simple Queue:</strong></p><ul><li>Elements are inserted at the rear and removed from the front.</li></ul></li><li><p><strong>Circular Queue:</strong></p><ul><li>The rear of the queue wraps around to the front when it reaches the end, reusing empty spaces.</li></ul></li><li><p><strong>Priority Queue:</strong></p><ul><li>Elements are processed based on priority rather than insertion order.</li></ul></li><li><p><strong>Deque (Double-Ended Queue):</strong></p><ul><li>Insertion and deletion can happen from both ends (front and rear).</li></ul></li></ol><hr><h2>5. <strong>Queue Implementation in Java (Array-based)</strong></h2><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">Queue</span> {
    <span class="hljs-keyword">private</span> <span class="hljs-type">int</span> arr[];
    <span class="hljs-keyword">private</span> <span class="hljs-type">int</span> front, rear, capacity;

    <span class="hljs-comment">// Constructor to initialize the queue</span>
    Queue(<span class="hljs-type">int</span> size) {
        arr = <span class="hljs-keyword">new</span> <span class="hljs-title class_">int</span>[size];
        capacity = size;
        front = <span class="hljs-number">0</span>;
        rear = -<span class="hljs-number">1</span>;
    }

    <span class="hljs-comment">// Enqueue operation</span>
    <span class="hljs-keyword">void</span> <span class="hljs-title function_">enqueue</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-keyword">if</span> (isFull()) {
            System.out.println(<span class="hljs-string">"Queue Overflow"</span>);
            <span class="hljs-keyword">return</span>;
        }
        arr[++rear] = value;
        System.out.println(value + <span class="hljs-string">" added to the queue"</span>);
    }

    <span class="hljs-comment">// Dequeue operation</span>
    <span class="hljs-type">int</span> <span class="hljs-title function_">dequeue</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Queue Underflow"</span>);
            <span class="hljs-keyword">return</span> Integer.MIN_VALUE;
        }
        <span class="hljs-keyword">return</span> arr[front++];
    }

    <span class="hljs-comment">// Peek operation</span>
    <span class="hljs-type">int</span> <span class="hljs-title function_">peek</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Queue is empty"</span>);
            <span class="hljs-keyword">return</span> Integer.MIN_VALUE;
        }
        <span class="hljs-keyword">return</span> arr[front];
    }

    <span class="hljs-comment">// Check if the queue is empty</span>
    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isEmpty</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> front &gt; rear;
    }

    <span class="hljs-comment">// Check if the queue is full</span>
    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isFull</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> rear == capacity - <span class="hljs-number">1</span>;
    }
}
</code></div></div></pre><hr><h2>6. <strong>Queue Implementation in Java (Linked List-based)</strong></h2><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">Node</span> {
    <span class="hljs-type">int</span> data;
    Node next;

    Node(<span class="hljs-type">int</span> data) {
        <span class="hljs-built_in">this</span>.data = data;
        <span class="hljs-built_in">this</span>.next = <span class="hljs-literal">null</span>;
    }
}

<span class="hljs-keyword">class</span> <span class="hljs-title class_">LinkedQueue</span> {
    <span class="hljs-keyword">private</span> Node front, rear;

    <span class="hljs-comment">// Constructor</span>
    LinkedQueue() {
        front = rear = <span class="hljs-literal">null</span>;
    }

    <span class="hljs-comment">// Enqueue operation</span>
    <span class="hljs-keyword">void</span> <span class="hljs-title function_">enqueue</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-type">Node</span> <span class="hljs-variable">newNode</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">Node</span>(value);
        <span class="hljs-keyword">if</span> (rear == <span class="hljs-literal">null</span>) {
            front = rear = newNode;
            <span class="hljs-keyword">return</span>;
        }
        rear.next = newNode;
        rear = newNode;
    }

    <span class="hljs-comment">// Dequeue operation</span>
    <span class="hljs-type">int</span> <span class="hljs-title function_">dequeue</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Queue Underflow"</span>);
            <span class="hljs-keyword">return</span> Integer.MIN_VALUE;
        }
        <span class="hljs-type">int</span> <span class="hljs-variable">value</span> <span class="hljs-operator">=</span> front.data;
        front = front.next;

        <span class="hljs-keyword">if</span> (front == <span class="hljs-literal">null</span>) rear = <span class="hljs-literal">null</span>; <span class="hljs-comment">// Reset rear when queue becomes empty</span>
        <span class="hljs-keyword">return</span> value;
    }

    <span class="hljs-comment">// Peek operation</span>
    <span class="hljs-type">int</span> <span class="hljs-title function_">peek</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (isEmpty()) {
            System.out.println(<span class="hljs-string">"Queue is empty"</span>);
            <span class="hljs-keyword">return</span> Integer.MIN_VALUE;
        }
        <span class="hljs-keyword">return</span> front.data;
    }

    <span class="hljs-comment">// Check if the queue is empty</span>
    <span class="hljs-type">boolean</span> <span class="hljs-title function_">isEmpty</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">return</span> front == <span class="hljs-literal">null</span>;
    }
}
</code></div></div></pre><hr><h2>7. <strong>Circular Queue Implementation in Java</strong></h2><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">CircularQueue</span> {
    <span class="hljs-keyword">private</span> <span class="hljs-type">int</span> arr[], front, rear, size;

    <span class="hljs-comment">// Constructor</span>
    CircularQueue(<span class="hljs-type">int</span> capacity) {
        arr = <span class="hljs-keyword">new</span> <span class="hljs-title class_">int</span>[capacity];
        size = capacity;
        front = rear = -<span class="hljs-number">1</span>;
    }

    <span class="hljs-comment">// Enqueue operation</span>
    <span class="hljs-keyword">void</span> <span class="hljs-title function_">enqueue</span><span class="hljs-params">(<span class="hljs-type">int</span> value)</span> {
        <span class="hljs-keyword">if</span> ((rear + <span class="hljs-number">1</span>) % size == front) {
            System.out.println(<span class="hljs-string">"Queue Overflow"</span>);
            <span class="hljs-keyword">return</span>;
        }
        <span class="hljs-keyword">if</span> (front == -<span class="hljs-number">1</span>) front = <span class="hljs-number">0</span>;
        rear = (rear + <span class="hljs-number">1</span>) % size;
        arr[rear] = value;
        System.out.println(value + <span class="hljs-string">" added to circular queue"</span>);
    }

    <span class="hljs-comment">// Dequeue operation</span>
    <span class="hljs-type">int</span> <span class="hljs-title function_">dequeue</span><span class="hljs-params">()</span> {
        <span class="hljs-keyword">if</span> (front == -<span class="hljs-number">1</span>) {
            System.out.println(<span class="hljs-string">"Queue Underflow"</span>);
            <span class="hljs-keyword">return</span> Integer.MIN_VALUE;
        }
        <span class="hljs-type">int</span> <span class="hljs-variable">value</span> <span class="hljs-operator">=</span> arr[front];
        <span class="hljs-keyword">if</span> (front == rear) { <span class="hljs-comment">// Queue becomes empty</span>
            front = rear = -<span class="hljs-number">1</span>;
        } <span class="hljs-keyword">else</span> {
            front = (front + <span class="hljs-number">1</span>) % size;
        }
        <span class="hljs-keyword">return</span> value;
    }
}
</code></div></div></pre><hr><h2>8. <strong>Time and Space Complexity</strong></h2><ul><li><strong>Enqueue:</strong> O(1)</li><li><strong>Dequeue:</strong> O(1)</li><li><strong>Peek:</strong> O(1)</li></ul><p>Space Complexity:</p><ul><li><strong>Array-based Queue:</strong> O(n)</li><li><strong>Linked List-based Queue:</strong> O(n)</li></ul><hr><h2>9. <strong>Use Case: Breadth-First Search (BFS)</strong></h2><p>Queues are used in <strong>BFS</strong> for traversing graphs level by level. Example:</p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">import</span> java.util.*;

<span class="hljs-keyword">class</span> <span class="hljs-title class_">Graph</span> {
    <span class="hljs-keyword">private</span> <span class="hljs-type">int</span> vertices;
    <span class="hljs-keyword">private</span> LinkedList&lt;Integer&gt; adjList[];

    Graph(<span class="hljs-type">int</span> v) {
        vertices = v;
        adjList = <span class="hljs-keyword">new</span> <span class="hljs-title class_">LinkedList</span>[v];
        <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>; i &lt; v; ++i)
            adjList[i] = <span class="hljs-keyword">new</span> <span class="hljs-title class_">LinkedList</span>&lt;&gt;();
    }

    <span class="hljs-keyword">void</span> <span class="hljs-title function_">addEdge</span><span class="hljs-params">(<span class="hljs-type">int</span> v, <span class="hljs-type">int</span> w)</span> {
        adjList[v].add(w);
    }

    <span class="hljs-keyword">void</span> <span class="hljs-title function_">BFS</span><span class="hljs-params">(<span class="hljs-type">int</span> start)</span> {
        <span class="hljs-type">boolean</span> visited[] = <span class="hljs-keyword">new</span> <span class="hljs-title class_">boolean</span>[vertices];
        Queue&lt;Integer&gt; queue = <span class="hljs-keyword">new</span> <span class="hljs-title class_">LinkedList</span>&lt;&gt;();

        visited[start] = <span class="hljs-literal">true</span>;
        queue.add(start);

        <span class="hljs-keyword">while</span> (!queue.isEmpty()) {
            <span class="hljs-type">int</span> <span class="hljs-variable">node</span> <span class="hljs-operator">=</span> queue.poll();
            System.out.print(node + <span class="hljs-string">" "</span>);

            <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> neighbor : adjList[node]) {
                <span class="hljs-keyword">if</span> (!visited[neighbor]) {
                    visited[neighbor] = <span class="hljs-literal">true</span>;
                    queue.add(neighbor);
                }
            }
        }
    }

    <span class="hljs-keyword">public</span> <span class="hljs-keyword">static</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">main</span><span class="hljs-params">(String args[])</span> {
        <span class="hljs-type">Graph</span> <span class="hljs-variable">g</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">Graph</span>(<span class="hljs-number">4</span>);
        g.addEdge(<span class="hljs-number">0</span>, <span class="hljs-number">1</span>);
        g.addEdge(<span class="hljs-number">0</span>, <span class="hljs-number">2</span>);
        g.addEdge(<span class="hljs-number">1</span>, <span class="hljs-number">2</span>);
        g.addEdge(<span class="hljs-number">2</span>, <span class="hljs-number">0</span>);
        g.addEdge(<span class="hljs-number">2</span>, <span class="hljs-number">3</span>);
        g.addEdge(<span class="hljs-number">3</span>, <span class="hljs-number">3</span>);

        System.out.println(<span class="hljs-string">"BFS starting from vertex 2:"</span>);
        g.BFS(<span class="hljs-number">2</span>);
    }
}
</code></div></div></pre><hr><h2>10. <strong>Flashcards</strong></h2><ol><li><p><strong>What is the principle of a queue?</strong></p><ul><li>FIFO (First In, First Out).</li></ul></li><li><p><strong>Difference between a queue and a stack?</strong></p><ul><li>Queue follows FIFO, stack follows LIFO.</li></ul></li><li><p><strong>What happens if you enqueue to a full queue?</strong></p><ul><li>Queue Overflow.</li></ul></li><li><p><strong>How is a circular queue different from a simple queue?</strong></p><ul><li>In a circular queue, the rear can wrap around to the front.</li></ul></li></ol><hr><h2>11. <strong>Practice Questions</strong></h2><ol><li><strong>What is the time complexity of enqueue and dequeue operations?</strong></li><li><strong>Write a program to reverse a queue using a stack.</strong></li><li><strong>Explain how BFS uses a queue.</strong></li><li><strong>Implement a priority queue.</strong></li></ol><hr><p>This completes <strong>queues</strong>! Let me know if you’re ready for the tricky question review or if we should move on to <strong>recursion</strong>.</p>

---



---

 
<h3><strong>Recursion</strong> – A Deep Dive</h3><hr><h2>1. <strong>What is Recursion?</strong></h2><p>Recursion is a process where a function <strong>calls itself</strong> directly or indirectly to solve a problem. A <strong>recursive function</strong> solves a small part of the problem in each call and eventually stops when it reaches a <strong>base case</strong>.</p><hr><h2>2. <strong>Real-Life Example</strong></h2><p>Think of a <strong>Russian doll</strong>. When you open a doll, there is a smaller one inside, and this repeats until the smallest doll is found, which represents the <strong>base case</strong>. Similarly, recursion breaks a large problem into smaller sub-problems until the simplest version is reached.</p><hr><h2>3. <strong>Structure of Recursive Function</strong></h2><p>A recursive function has two essential parts:</p><ol><li><strong>Base Case:</strong> The condition that stops the recursion.</li><li><strong>Recursive Case:</strong> The part where the function keeps calling itself with a smaller input.</li></ol><hr><h2>4. <strong>Simple Example of Recursion – Factorial Calculation</strong></h2><p>The <strong>factorial</strong> of a number <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>n</mi></mrow><annotation encoding="application/x-tex">n</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.4306em;"></span><span class="mord mathnormal">n</span></span></span></span> is the product of all positive integers less than or equal to <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>n</mi></mrow><annotation encoding="application/x-tex">n</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.4306em;"></span><span class="mord mathnormal">n</span></span></span></span>. Mathematically:</p><span class="katex-display"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><semantics><mrow><mi>n</mi><mo stretchy="false">!</mo><mo>=</mo><mi>n</mi><mo>×</mo><mo stretchy="false">(</mo><mi>n</mi><mo>−</mo><mn>1</mn><mo stretchy="false">)</mo><mo>×</mo><mo stretchy="false">(</mo><mi>n</mi><mo>−</mo><mn>2</mn><mo stretchy="false">)</mo><mo>×</mo><mo>…</mo><mo>×</mo><mn>1</mn></mrow><annotation encoding="application/x-tex">n! = n \times (n - 1) \times (n - 2) \times \ldots \times 1</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.6944em;"></span><span class="mord mathnormal">n</span><span class="mclose">!</span><span class="mspace" style="margin-right: 0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right: 0.2778em;"></span></span><span class="base"><span class="strut" style="height: 0.6667em; vertical-align: -0.0833em;"></span><span class="mord mathnormal">n</span><span class="mspace" style="margin-right: 0.2222em;"></span><span class="mbin">×</span><span class="mspace" style="margin-right: 0.2222em;"></span></span><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal">n</span><span class="mspace" style="margin-right: 0.2222em;"></span><span class="mbin">−</span><span class="mspace" style="margin-right: 0.2222em;"></span></span><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mord">1</span><span class="mclose">)</span><span class="mspace" style="margin-right: 0.2222em;"></span><span class="mbin">×</span><span class="mspace" style="margin-right: 0.2222em;"></span></span><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal">n</span><span class="mspace" style="margin-right: 0.2222em;"></span><span class="mbin">−</span><span class="mspace" style="margin-right: 0.2222em;"></span></span><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mord">2</span><span class="mclose">)</span><span class="mspace" style="margin-right: 0.2222em;"></span><span class="mbin">×</span><span class="mspace" style="margin-right: 0.2222em;"></span></span><span class="base"><span class="strut" style="height: 0.6667em; vertical-align: -0.0833em;"></span><span class="minner">…</span><span class="mspace" style="margin-right: 0.2222em;"></span><span class="mbin">×</span><span class="mspace" style="margin-right: 0.2222em;"></span></span><span class="base"><span class="strut" style="height: 0.6444em;"></span><span class="mord">1</span></span></span></span></span><p>Using recursion:</p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">public</span> <span class="hljs-keyword">class</span> <span class="hljs-title class_">Factorial</span> {
    <span class="hljs-keyword">static</span> <span class="hljs-type">int</span> <span class="hljs-title function_">factorial</span><span class="hljs-params">(<span class="hljs-type">int</span> n)</span> {
        <span class="hljs-keyword">if</span> (n == <span class="hljs-number">0</span>) <span class="hljs-comment">// Base Case</span>
            <span class="hljs-keyword">return</span> <span class="hljs-number">1</span>;
        <span class="hljs-keyword">return</span> n * factorial(n - <span class="hljs-number">1</span>); <span class="hljs-comment">// Recursive Case</span>
    }

    <span class="hljs-keyword">public</span> <span class="hljs-keyword">static</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">main</span><span class="hljs-params">(String[] args)</span> {
        System.out.println(<span class="hljs-string">"Factorial of 5 is: "</span> + factorial(<span class="hljs-number">5</span>));
    }
}
</code></div></div></pre><p><strong>Explanation:</strong></p><ul><li>If <code>n == 0</code>, return 1 (base case).</li><li>Otherwise, keep calling <code>factorial(n-1)</code> until <code>n</code> becomes 0.<br>For <code>factorial(5)</code>, the recursion goes:</li></ul><span class="katex-display" style=""><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><semantics><mrow><mn>5</mn><mo>×</mo><mn>4</mn><mo>×</mo><mn>3</mn><mo>×</mo><mn>2</mn><mo>×</mo><mn>1</mn><mo>=</mo><mn>120</mn></mrow><annotation encoding="application/x-tex">5 \times 4 \times 3 \times 2 \times 1 = 120</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.7278em; vertical-align: -0.0833em;"></span><span class="mord">5</span><span class="mspace" style="margin-right: 0.2222em;"></span><span class="mbin">×</span><span class="mspace" style="margin-right: 0.2222em;"></span></span><span class="base"><span class="strut" style="height: 0.7278em; vertical-align: -0.0833em;"></span><span class="mord">4</span><span class="mspace" style="margin-right: 0.2222em;"></span><span class="mbin">×</span><span class="mspace" style="margin-right: 0.2222em;"></span></span><span class="base"><span class="strut" style="height: 0.7278em; vertical-align: -0.0833em;"></span><span class="mord">3</span><span class="mspace" style="margin-right: 0.2222em;"></span><span class="mbin">×</span><span class="mspace" style="margin-right: 0.2222em;"></span></span><span class="base"><span class="strut" style="height: 0.7278em; vertical-align: -0.0833em;"></span><span class="mord">2</span><span class="mspace" style="margin-right: 0.2222em;"></span><span class="mbin">×</span><span class="mspace" style="margin-right: 0.2222em;"></span></span><span class="base"><span class="strut" style="height: 0.6444em;"></span><span class="mord">1</span><span class="mspace" style="margin-right: 0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right: 0.2778em;"></span></span><span class="base"><span class="strut" style="height: 0.6444em;"></span><span class="mord">120</span></span></span></span></span><hr><h2>5. <strong>How Recursion Works Internally (Call Stack)</strong></h2><p>Each recursive call is <strong>pushed onto the call stack</strong>, and once the base case is reached, the calls start <strong>popping</strong> off, returning results step by step.</p><hr><h2>6. <strong>Types of Recursion</strong></h2><ol><li><strong>Direct Recursion:</strong> A function directly calls itself.<pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">void</span> <span class="hljs-title function_">directRecursion</span><span class="hljs-params">()</span> {
    directRecursion();
}
</code></div></div></pre></li><li><strong>Indirect Recursion:</strong> A function calls another function, which eventually calls the original function.<pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">void</span> <span class="hljs-title function_">functionA</span><span class="hljs-params">()</span> {
    functionB();
}
<span class="hljs-keyword">void</span> <span class="hljs-title function_">functionB</span><span class="hljs-params">()</span> {
    functionA();
}
</code></div></div></pre></li></ol><hr><h2>7. <strong>Advantages and Disadvantages of Recursion</strong></h2><table><thead><tr><th><strong>Advantages</strong></th><th><strong>Disadvantages</strong></th></tr></thead><tbody><tr><td>Easier to write and understand code</td><td>Uses more memory (call stack overhead)</td></tr><tr><td>Great for problems like tree traversal or backtracking</td><td>Can lead to <strong>stack overflow</strong> if not terminated properly</td></tr></tbody></table><hr><h2>8. <strong>Recursion vs Iteration</strong></h2><ul><li><strong>Recursion</strong>: Uses a function that calls itself.</li><li><strong>Iteration</strong>: Uses loops to repeat a process.<br>Both methods can solve the same problem, but recursion is preferred when the problem can be broken into <strong>sub-problems</strong>, like tree traversal.</li></ul><hr><h2>9. <strong>Common Problems Solved Using Recursion</strong></h2><ol><li><strong>Factorial of a number</strong></li><li><strong>Fibonacci sequence generation</strong></li><li><strong>Tower of Hanoi</strong></li><li><strong>Binary search</strong></li><li><strong>Tree traversal (pre-order, in-order, post-order)</strong></li><li><strong>Backtracking (e.g., solving a maze)</strong></li></ol><hr><h2>10. <strong>Fibonacci Sequence using Recursion</strong></h2><p>The <strong>Fibonacci sequence</strong> is: 0, 1, 1, 2, 3, 5, 8...<br>Each number is the sum of the two preceding ones.</p><p><strong>Fibonacci using recursion:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">public</span> <span class="hljs-keyword">class</span> <span class="hljs-title class_">Fibonacci</span> {
    <span class="hljs-keyword">static</span> <span class="hljs-type">int</span> <span class="hljs-title function_">fibonacci</span><span class="hljs-params">(<span class="hljs-type">int</span> n)</span> {
        <span class="hljs-keyword">if</span> (n &lt;= <span class="hljs-number">1</span>) <span class="hljs-comment">// Base Case</span>
            <span class="hljs-keyword">return</span> n;
        <span class="hljs-keyword">return</span> fibonacci(n - <span class="hljs-number">1</span>) + fibonacci(n - <span class="hljs-number">2</span>); <span class="hljs-comment">// Recursive Case</span>
    }

    <span class="hljs-keyword">public</span> <span class="hljs-keyword">static</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">main</span><span class="hljs-params">(String[] args)</span> {
        System.out.println(<span class="hljs-string">"Fibonacci of 5 is: "</span> + fibonacci(<span class="hljs-number">5</span>));
    }
}
</code></div></div></pre><p><strong>Explanation:</strong></p><ul><li>For <code>n = 0</code> or <code>n = 1</code>, return <code>n</code> (base case).</li><li>Otherwise, return the sum of the previous two Fibonacci numbers.</li></ul><hr><h2>11. <strong>Tail Recursion</strong></h2><p>A <strong>tail-recursive</strong> function has its recursive call as the last statement.<br>Example:</p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">public</span> <span class="hljs-keyword">class</span> <span class="hljs-title class_">TailRecursion</span> {
    <span class="hljs-keyword">static</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">printNumbers</span><span class="hljs-params">(<span class="hljs-type">int</span> n)</span> {
        <span class="hljs-keyword">if</span> (n == <span class="hljs-number">0</span>) <span class="hljs-keyword">return</span>; <span class="hljs-comment">// Base Case</span>
        System.out.println(n);
        printNumbers(n - <span class="hljs-number">1</span>); <span class="hljs-comment">// Tail Recursion</span>
    }

    <span class="hljs-keyword">public</span> <span class="hljs-keyword">static</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">main</span><span class="hljs-params">(String[] args)</span> {
        printNumbers(<span class="hljs-number">5</span>);
    }
}
</code></div></div></pre><p><strong>Why Tail Recursion is Important?</strong></p><ul><li>Some compilers optimize tail recursion to <strong>reduce memory usage</strong>, making it as efficient as iteration.</li></ul><hr><h2>12. <strong>Tower of Hanoi</strong></h2><p>This is a classic problem solved using recursion. The objective is to move all disks from <strong>source rod</strong> to <strong>destination rod</strong> using an <strong>auxiliary rod</strong>, following these rules:</p><ol><li>Only one disk can be moved at a time.</li><li>A larger disk cannot be placed on top of a smaller disk.</li></ol><p><strong>Code:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">public</span> <span class="hljs-keyword">class</span> <span class="hljs-title class_">TowerOfHanoi</span> {
    <span class="hljs-keyword">static</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">moveDisks</span><span class="hljs-params">(<span class="hljs-type">int</span> n, <span class="hljs-type">char</span> fromRod, <span class="hljs-type">char</span> toRod, <span class="hljs-type">char</span> auxRod)</span> {
        <span class="hljs-keyword">if</span> (n == <span class="hljs-number">1</span>) {
            System.out.println(<span class="hljs-string">"Move disk 1 from "</span> + fromRod + <span class="hljs-string">" to "</span> + toRod);
            <span class="hljs-keyword">return</span>;
        }
        moveDisks(n - <span class="hljs-number">1</span>, fromRod, auxRod, toRod);
        System.out.println(<span class="hljs-string">"Move disk "</span> + n + <span class="hljs-string">" from "</span> + fromRod + <span class="hljs-string">" to "</span> + toRod);
        moveDisks(n - <span class="hljs-number">1</span>, auxRod, toRod, fromRod);
    }

    <span class="hljs-keyword">public</span> <span class="hljs-keyword">static</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">main</span><span class="hljs-params">(String[] args)</span> {
        <span class="hljs-type">int</span> <span class="hljs-variable">n</span> <span class="hljs-operator">=</span> <span class="hljs-number">3</span>; <span class="hljs-comment">// Number of disks</span>
        moveDisks(n, <span class="hljs-string">'A'</span>, <span class="hljs-string">'C'</span>, <span class="hljs-string">'B'</span>);
    }
}
</code></div></div></pre><p><strong>Explanation:</strong><br>For <code>n = 3</code>, the steps are:</p><ol><li>Move 2 disks from A to B using C.</li><li>Move the largest disk from A to C.</li><li>Move 2 disks from B to C using A.</li></ol><hr><h2>13. <strong>Time Complexity of Recursion</strong></h2><ul><li><strong>Factorial:</strong> O(n)</li><li><strong>Fibonacci:</strong> O(2^n) (exponential)</li><li><strong>Tower of Hanoi:</strong> O(2^n)</li><li><strong>Binary Search:</strong> O(log n)</li></ul><hr><h2>14. <strong>How to Avoid Stack Overflow Errors in Recursion</strong></h2><ol><li><strong>Use tail recursion</strong>, if possible.</li><li><strong>Convert recursion to iteration</strong> for large input sizes.</li><li><strong>Set a limit on recursive depth</strong>, or use <code>try-catch</code> to handle errors gracefully.</li></ol><hr><h2>15. <strong>Flashcards</strong></h2><ol><li><strong>What is a base case?</strong><ul><li>A condition that stops the recursion.</li></ul></li><li><strong>What happens if there is no base case in recursion?</strong><ul><li>It leads to <strong>infinite recursion</strong> and a <strong>stack overflow</strong> error.</li></ul></li><li><strong>Name a recursive algorithm used for searching.</strong><ul><li><strong>Binary Search.</strong></li></ul></li><li><strong>What is tail recursion?</strong><ul><li>When the recursive call is the last operation in the function.</li></ul></li></ol><hr><h2>16. <strong>Practice Questions</strong></h2><ol><li>Write a recursive function to calculate the sum of digits of a number.</li><li>Convert the Fibonacci sequence function to an <strong>iterative version</strong>.</li><li>Solve the <strong>Tower of Hanoi</strong> for 4 disks.</li><li>Explain how <strong>binary search</strong> uses recursion.</li></ol><hr><p>This completes the <strong>recursion</strong> topic! Are you ready to review tricky questions, or do you want to move on to another topic?</p>

---



---

 
<h3><strong>Tricky Questions Review – Recursion</strong></h3><p>Let’s dive into the tricky questions related to recursion. We’ll break them down step-by-step to ensure you grasp every concept deeply.</p><hr><h3>1. <strong>What happens if a recursive function does not have a base case?</strong></h3><ul><li><strong>Answer:</strong> The function will keep calling itself infinitely, resulting in <strong>stack overflow</strong>. This error occurs because the call stack has limited space, and without a base case, the function never terminates.</li></ul><p><strong>Example:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">void</span> <span class="hljs-title function_">infiniteRecursion</span><span class="hljs-params">()</span> {
    infiniteRecursion(); <span class="hljs-comment">// No base case</span>
}
</code></div></div></pre><hr><h3>2. <strong>How does the call stack work with recursion?</strong></h3><ul><li><strong>Answer:</strong> Each recursive call is pushed onto the <strong>call stack</strong>. When the base case is reached, the function returns values back through <strong>popping off</strong> calls from the stack in reverse order.</li></ul><p><strong>Example:</strong><br>For <code>factorial(3)</code>, here’s how the stack behaves:</p><ol><li><code>factorial(3)</code> → pushes <code>factorial(2)</code></li><li><code>factorial(2)</code> → pushes <code>factorial(1)</code></li><li><code>factorial(1)</code> → pushes <code>factorial(0)</code></li><li>Once <code>factorial(0)</code> returns 1, each call <strong>pops off</strong> and multiplies its result.</li></ol><hr><h3>3. <strong>What is the time complexity of recursive Fibonacci? Why is it so high?</strong></h3><ul><li><strong>Answer:</strong> The time complexity of the recursive Fibonacci function is <strong>O(2^n)</strong>, which is <strong>exponential</strong>.</li><li>This is because each Fibonacci call makes <strong>two recursive calls</strong> for smaller inputs, leading to a <strong>huge number of repeated calculations</strong>.</li></ul><p><strong>Optimization Tip:</strong> Use <strong>Memoization</strong> or <strong>Dynamic Programming</strong> to avoid recalculating the same values.</p><hr><h3>4. <strong>How can we convert recursion to iteration?</strong></h3><ul><li><strong>Answer:</strong> Some problems like <strong>factorial</strong> can be solved using <strong>loops</strong> instead of recursion. This reduces the risk of stack overflow.</li></ul><p><strong>Example (Iterative Factorial):</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">int</span> <span class="hljs-title function_">factorial</span><span class="hljs-params">(<span class="hljs-type">int</span> n)</span> {
    <span class="hljs-type">int</span> <span class="hljs-variable">result</span> <span class="hljs-operator">=</span> <span class="hljs-number">1</span>;
    <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> <span class="hljs-number">1</span>; i &lt;= n; i++) {
        result *= i;
    }
    <span class="hljs-keyword">return</span> result;
}
</code></div></div></pre><hr><h3>5. <strong>What is Tail Recursion? How does it differ from regular recursion?</strong></h3><ul><li><strong>Answer:</strong> In <strong>tail recursion</strong>, the recursive call is the <strong>last operation</strong> performed by the function.</li><li>Tail-recursive functions can be optimized by the compiler to use <strong>constant space</strong>, avoiding stack overflow.</li></ul><p><strong>Example of Tail Recursion:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">void</span> <span class="hljs-title function_">tailRecursion</span><span class="hljs-params">(<span class="hljs-type">int</span> n)</span> {
    <span class="hljs-keyword">if</span> (n == <span class="hljs-number">0</span>) <span class="hljs-keyword">return</span>;
    System.out.println(n);
    tailRecursion(n - <span class="hljs-number">1</span>); <span class="hljs-comment">// Tail call</span>
}
</code></div></div></pre><p><strong>Regular Recursion Example (non-tail):</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">int</span> <span class="hljs-title function_">sum</span><span class="hljs-params">(<span class="hljs-type">int</span> n)</span> {
    <span class="hljs-keyword">return</span> n + sum(n - <span class="hljs-number">1</span>); <span class="hljs-comment">// Not a tail call, since addition happens after the recursive call</span>
}
</code></div></div></pre><hr><h3>6. <strong>Why is recursion preferred in tree traversal algorithms?</strong></h3><ul><li><strong>Answer:</strong> Tree structures have a <strong>hierarchical nature</strong>, and recursion helps by easily handling <strong>subtrees</strong>. Functions like <strong>in-order, pre-order, and post-order traversal</strong> naturally fit with recursive algorithms, simplifying the code.</li></ul><hr><h3>7. <strong>Practice Problem: Sum of Digits using Recursion</strong></h3><p><strong>Question:</strong> Write a recursive function to calculate the sum of digits of a number.</p><p><strong>Answer:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">int</span> <span class="hljs-title function_">sumOfDigits</span><span class="hljs-params">(<span class="hljs-type">int</span> n)</span> {
    <span class="hljs-keyword">if</span> (n == <span class="hljs-number">0</span>) <span class="hljs-keyword">return</span> <span class="hljs-number">0</span>; <span class="hljs-comment">// Base case</span>
    <span class="hljs-keyword">return</span> n % <span class="hljs-number">10</span> + sumOfDigits(n / <span class="hljs-number">10</span>); <span class="hljs-comment">// Recursive case</span>
}

<span class="hljs-keyword">public</span> <span class="hljs-keyword">static</span> <span class="hljs-keyword">void</span> <span class="hljs-title function_">main</span><span class="hljs-params">(String[] args)</span> {
    System.out.println(sumOfDigits(<span class="hljs-number">123</span>)); <span class="hljs-comment">// Output: 6</span>
}
</code></div></div></pre><p><strong>Explanation:</strong></p><ul><li><code>sumOfDigits(123)</code> = 3 + <code>sumOfDigits(12)</code></li><li><code>sumOfDigits(12)</code> = 2 + <code>sumOfDigits(1)</code></li><li><code>sumOfDigits(1)</code> = 1 + <code>sumOfDigits(0)</code></li><li>Result: <strong>6</strong></li></ul><hr><h3>8. <strong>Why do some recursive functions perform poorly?</strong></h3><ul><li><strong>Answer:</strong> Recursive functions may perform poorly due to:<ol><li><strong>Overlapping subproblems:</strong> Same computations are repeated multiple times (e.g., Fibonacci).</li><li><strong>Deep recursion:</strong> If input size is large, it can lead to <strong>stack overflow</strong>.</li><li><strong>Excessive memory usage:</strong> Each call consumes space in the <strong>call stack</strong>.</li></ol></li></ul><hr><h3>9. <strong>How does Binary Search work using recursion?</strong></h3><p><strong>Answer:</strong> Binary Search divides the array into halves and searches in the relevant half recursively.</p><p><strong>Code Example:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">int</span> <span class="hljs-title function_">binarySearch</span><span class="hljs-params">(<span class="hljs-type">int</span>[] arr, <span class="hljs-type">int</span> low, <span class="hljs-type">int</span> high, <span class="hljs-type">int</span> key)</span> {
    <span class="hljs-keyword">if</span> (low &gt; high) <span class="hljs-keyword">return</span> -<span class="hljs-number">1</span>; <span class="hljs-comment">// Base case: Key not found</span>

    <span class="hljs-type">int</span> <span class="hljs-variable">mid</span> <span class="hljs-operator">=</span> (low + high) / <span class="hljs-number">2</span>;
    <span class="hljs-keyword">if</span> (arr[mid] == key) <span class="hljs-keyword">return</span> mid;
    <span class="hljs-keyword">else</span> <span class="hljs-keyword">if</span> (key &lt; arr[mid])
        <span class="hljs-keyword">return</span> binarySearch(arr, low, mid - <span class="hljs-number">1</span>, key); <span class="hljs-comment">// Search left half</span>
    <span class="hljs-keyword">else</span>
        <span class="hljs-keyword">return</span> binarySearch(arr, mid + <span class="hljs-number">1</span>, high, key); <span class="hljs-comment">// Search right half</span>
}
</code></div></div></pre><hr><h3>10. <strong>Tower of Hanoi – Recursive Insight</strong></h3><p><strong>Question:</strong> Explain the Tower of Hanoi algorithm recursively.</p><p><strong>Answer:</strong></p><ul><li>If there is only <strong>one disk</strong>, move it directly from <strong>source</strong> to <strong>destination</strong>.</li><li>For <strong>n disks</strong>, move the top n-1 disks to the auxiliary rod, move the largest disk to the destination, and then move the n-1 disks from auxiliary to destination.</li></ul><p><strong>Code:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">void</span> <span class="hljs-title function_">towerOfHanoi</span><span class="hljs-params">(<span class="hljs-type">int</span> n, <span class="hljs-type">char</span> from, <span class="hljs-type">char</span> to, <span class="hljs-type">char</span> aux)</span> {
    <span class="hljs-keyword">if</span> (n == <span class="hljs-number">1</span>) {
        System.out.println(<span class="hljs-string">"Move disk 1 from "</span> + from + <span class="hljs-string">" to "</span> + to);
        <span class="hljs-keyword">return</span>;
    }
    towerOfHanoi(n - <span class="hljs-number">1</span>, from, aux, to);
    System.out.println(<span class="hljs-string">"Move disk "</span> + n + <span class="hljs-string">" from "</span> + from + <span class="hljs-string">" to "</span> + to);
    towerOfHanoi(n - <span class="hljs-number">1</span>, aux, to, from);
}
</code></div></div></pre><hr><h3><strong>Summary of Key Points</strong></h3><ol><li><strong>Base case</strong> is essential for terminating recursion.</li><li><strong>Call stack</strong> holds each recursive call until the base case is reached.</li><li><strong>Tail recursion</strong> can improve efficiency by reducing memory usage.</li><li>Recursive solutions are <strong>elegant</strong> but should be used with caution for large inputs.</li><li><strong>Binary Search</strong> and <strong>Tree Traversal</strong> are natural fits for recursion.</li></ol><hr><p>These tricky questions cover most of the challenging parts of recursion. Do you want to practice more tricky problems, or should we move on to the next topic?</p>

---


---

 
<p>Below is the <strong>complete list of tricky questions and explanations</strong> for each topic. We will go deep into possible challenges your teacher might introduce to ensure you’re fully prepared.</p><hr><h2><strong>Tricky Questions Review – Arrays</strong></h2><ol><li><p><strong>Why is the time complexity for array insertion O(n) in the worst case?</strong></p><ul><li><strong>Answer:</strong> If the element is inserted at the beginning or in the middle, all subsequent elements must be shifted to make space, which takes <strong>O(n)</strong> time.</li></ul></li><li><p><strong>What is the difference between static and dynamic arrays?</strong></p><ul><li><strong>Answer:</strong> Static arrays have a fixed size, while dynamic arrays (like <code>ArrayList</code>) can grow as needed. Dynamic arrays internally <strong>double their size</strong> when full.</li></ul></li><li><p><strong>How do 2D arrays get stored in memory?</strong></p><ul><li><strong>Answer:</strong> A 2D array is stored as a <strong>contiguous block of memory</strong> in <strong>row-major</strong> or <strong>column-major</strong> order. Java uses row-major order, meaning all elements of a row are stored consecutively.</li></ul></li><li><p><strong>Sliding Window Problem: Find the maximum sum of a subarray of size K.</strong><br><strong>Code Example:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">int</span> <span class="hljs-title function_">maxSum</span><span class="hljs-params">(<span class="hljs-type">int</span>[] arr, <span class="hljs-type">int</span> k)</span> {
    <span class="hljs-type">int</span> <span class="hljs-variable">maxSum</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>, windowSum = <span class="hljs-number">0</span>;
    <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>; i &lt; k; i++) windowSum += arr[i];
    maxSum = windowSum;
    <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> k; i &lt; arr.length; i++) {
        windowSum += arr[i] - arr[i - k];
        maxSum = Math.max(maxSum, windowSum);
    }
    <span class="hljs-keyword">return</span> maxSum;
}
</code></div></div></pre></li></ol><hr><h2><strong>Tricky Questions Review – Linked Lists</strong></h2><ol><li><p><strong>How can you detect a cycle in a linked list?</strong></p><ul><li><strong>Answer:</strong> Use <strong>Floyd’s Cycle Detection Algorithm</strong> (also called the slow and fast pointer technique).</li></ul><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">boolean</span> <span class="hljs-title function_">hasCycle</span><span class="hljs-params">(ListNode head)</span> {
    <span class="hljs-type">ListNode</span> <span class="hljs-variable">slow</span> <span class="hljs-operator">=</span> head, fast = head;
    <span class="hljs-keyword">while</span> (fast != <span class="hljs-literal">null</span> &amp;&amp; fast.next != <span class="hljs-literal">null</span>) {
        slow = slow.next;
        fast = fast.next.next;
        <span class="hljs-keyword">if</span> (slow == fast) <span class="hljs-keyword">return</span> <span class="hljs-literal">true</span>;
    }
    <span class="hljs-keyword">return</span> <span class="hljs-literal">false</span>;
}
</code></div></div></pre></li><li><p><strong>How do you reverse a linked list iteratively?</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java">ListNode <span class="hljs-title function_">reverse</span><span class="hljs-params">(ListNode head)</span> {
    <span class="hljs-type">ListNode</span> <span class="hljs-variable">prev</span> <span class="hljs-operator">=</span> <span class="hljs-literal">null</span>, current = head;
    <span class="hljs-keyword">while</span> (current != <span class="hljs-literal">null</span>) {
        <span class="hljs-type">ListNode</span> <span class="hljs-variable">next</span> <span class="hljs-operator">=</span> current.next;
        current.next = prev;
        prev = current;
        current = next;
    }
    <span class="hljs-keyword">return</span> prev;
}
</code></div></div></pre></li></ol><hr><h2><strong>Tricky Questions Review – Stacks</strong></h2><ol><li><p><strong>Why are stacks useful in function calls?</strong></p><ul><li><strong>Answer:</strong> Stacks help maintain <strong>local variables</strong> and <strong>function states</strong> during recursion by storing <strong>activation records</strong> on the call stack.</li></ul></li><li><p><strong>How to implement two stacks in one array?</strong></p><ul><li><strong>Answer:</strong> Use one stack starting from the beginning of the array and the other starting from the end. They grow towards each other.</li></ul></li></ol><hr><h2><strong>Tricky Questions Review – Queues</strong></h2><ol><li><p><strong>How does a circular queue avoid overflow?</strong></p><ul><li><strong>Answer:</strong> When the rear reaches the end of the array, it wraps around to the front if space is available. This avoids unnecessary shifting of elements.</li></ul></li><li><p><strong>How does a priority queue differ from a regular queue?</strong></p><ul><li><strong>Answer:</strong> A priority queue serves elements based on their <strong>priority</strong> rather than the order they arrive.</li></ul></li></ol><hr><h2><strong>Tricky Questions Review – Sorting Algorithms</strong></h2><ol><li><p><strong>Why is QuickSort faster than MergeSort in practice?</strong></p><ul><li><strong>Answer:</strong> QuickSort has better <strong>cache performance</strong> because it sorts in-place, while MergeSort requires additional space.</li></ul></li><li><p><strong>What is the time complexity of Heap Sort?</strong></p><ul><li><strong>Answer:</strong> Heap Sort has a <strong>time complexity of O(n log n)</strong> in all cases, making it a reliable choice for large datasets.</li></ul></li></ol><hr><h2><strong>Tricky Questions Review – Time and Space Complexity</strong></h2><ol><li><p><strong>How do nested loops affect time complexity?</strong></p><ul><li><strong>Answer:</strong> If there are two nested loops, each running n times, the total time complexity is <strong>O(n²)</strong>.</li></ul></li><li><p><strong>What is the difference between amortized and worst-case time complexity?</strong></p><ul><li><strong>Answer:</strong> Amortized complexity is the <strong>average time</strong> per operation over a sequence of operations, whereas worst-case complexity focuses on the <strong>most expensive</strong> scenario.</li></ul></li></ol><hr><h2><strong>Tricky Questions Review – Recursion</strong></h2><ol><li><p><strong>What happens if there is no base case in a recursive function?</strong></p><ul><li><strong>Answer:</strong> The function keeps calling itself infinitely, causing a <strong>stack overflow</strong> error.</li></ul></li><li><p><strong>How to convert a recursive Fibonacci function to an iterative one?</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">int</span> <span class="hljs-title function_">fibonacci</span><span class="hljs-params">(<span class="hljs-type">int</span> n)</span> {
    <span class="hljs-keyword">if</span> (n &lt;= <span class="hljs-number">1</span>) <span class="hljs-keyword">return</span> n;
    <span class="hljs-type">int</span> <span class="hljs-variable">a</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>, b = <span class="hljs-number">1</span>, sum = <span class="hljs-number">0</span>;
    <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> <span class="hljs-number">2</span>; i &lt;= n; i++) {
        sum = a + b;
        a = b;
        b = sum;
    }
    <span class="hljs-keyword">return</span> sum;
}
</code></div></div></pre></li></ol><hr><p>These tricky questions cover challenging aspects your teacher might ask. Do you want me to focus on a specific part of these topics, or shall we go over any remaining doubts?</p>

---

---

 
<p>Let’s do an <strong>in-depth tricky questions review</strong> for <strong>Linked Lists, Recursion, and Time &amp; Space Complexity</strong>. These are common areas for tough questions in exams.</p><hr><h2><strong>Linked Lists: Tricky Questions and Explanations</strong></h2><h3>1. <strong>What is the difference between a Singly, Doubly, and Circular Linked List?</strong></h3><ul><li><strong>Singly Linked List</strong>: Nodes have one pointer (<code>next</code>) pointing to the next node.</li><li><strong>Doubly Linked List</strong>: Nodes have two pointers (<code>next</code> and <code>prev</code>) for both forward and backward traversal.</li><li><strong>Circular Linked List</strong>: The last node points back to the first node, creating a loop.</li></ul><p><strong>Code: Singly Linked List Node in Java</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">class</span> <span class="hljs-title class_">Node</span> {
    <span class="hljs-type">int</span> data;
    Node next;
    Node(<span class="hljs-type">int</span> data) { <span class="hljs-built_in">this</span>.data = data; <span class="hljs-built_in">this</span>.next = <span class="hljs-literal">null</span>; }
}
</code></div></div></pre><hr><h3>2. <strong>How do you reverse a Doubly Linked List?</strong></h3><p><strong>Code Example:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java">Node <span class="hljs-title function_">reverseDoublyLinkedList</span><span class="hljs-params">(Node head)</span> {
    <span class="hljs-type">Node</span> <span class="hljs-variable">current</span> <span class="hljs-operator">=</span> head, temp = <span class="hljs-literal">null</span>;
    <span class="hljs-keyword">while</span> (current != <span class="hljs-literal">null</span>) {
        temp = current.prev;
        current.prev = current.next;
        current.next = temp;
        current = current.prev;
    }
    <span class="hljs-comment">// Adjust head to the new front.</span>
    <span class="hljs-keyword">return</span> temp.prev;
}
</code></div></div></pre><hr><h3>3. <strong>How do you merge two sorted linked lists?</strong></h3><p><strong>Explanation:</strong> This is a common interview question that requires merging two sorted lists into one sorted list.</p><p><strong>Code Example:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java">Node <span class="hljs-title function_">mergeLists</span><span class="hljs-params">(Node l1, Node l2)</span> {
    <span class="hljs-type">Node</span> <span class="hljs-variable">dummy</span> <span class="hljs-operator">=</span> <span class="hljs-keyword">new</span> <span class="hljs-title class_">Node</span>(<span class="hljs-number">0</span>);
    <span class="hljs-type">Node</span> <span class="hljs-variable">current</span> <span class="hljs-operator">=</span> dummy;
    <span class="hljs-keyword">while</span> (l1 != <span class="hljs-literal">null</span> &amp;&amp; l2 != <span class="hljs-literal">null</span>) {
        <span class="hljs-keyword">if</span> (l1.data &lt;= l2.data) {
            current.next = l1;
            l1 = l1.next;
        } <span class="hljs-keyword">else</span> {
            current.next = l2;
            l2 = l2.next;
        }
        current = current.next;
    }
    current.next = (l1 != <span class="hljs-literal">null</span>) ? l1 : l2;
    <span class="hljs-keyword">return</span> dummy.next;
}
</code></div></div></pre><hr><h3>4. <strong>How do you detect a cycle in a Circular Linked List?</strong></h3><ul><li><strong>Floyd’s Cycle Detection Algorithm</strong>: Use two pointers – slow (moves 1 step) and fast (moves 2 steps). If they meet, the list contains a cycle.<br><strong>Code Example:</strong></li></ul><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">boolean</span> <span class="hljs-title function_">hasCycle</span><span class="hljs-params">(Node head)</span> {
    <span class="hljs-type">Node</span> <span class="hljs-variable">slow</span> <span class="hljs-operator">=</span> head, fast = head;
    <span class="hljs-keyword">while</span> (fast != <span class="hljs-literal">null</span> &amp;&amp; fast.next != <span class="hljs-literal">null</span>) {
        slow = slow.next;
        fast = fast.next.next;
        <span class="hljs-keyword">if</span> (slow == fast) <span class="hljs-keyword">return</span> <span class="hljs-literal">true</span>;
    }
    <span class="hljs-keyword">return</span> <span class="hljs-literal">false</span>;
}
</code></div></div></pre><hr><h2><strong>Recursion: Tricky Questions and Concepts</strong></h2><h3>1. <strong>How does recursion work internally?</strong></h3><ul><li>Recursion uses the <strong>call stack</strong> to store each function call. Each time a recursive function calls itself, a new frame is added to the stack. Once the base case is reached, the calls start returning.</li></ul><hr><h3>2. <strong>How do you solve the Tower of Hanoi problem recursively?</strong></h3><p><strong>Problem:</strong> Move <code>n</code> disks from source to target using an auxiliary peg.<br><strong>Code Example:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">void</span> <span class="hljs-title function_">towerOfHanoi</span><span class="hljs-params">(<span class="hljs-type">int</span> n, <span class="hljs-type">char</span> from, <span class="hljs-type">char</span> to, <span class="hljs-type">char</span> aux)</span> {
    <span class="hljs-keyword">if</span> (n == <span class="hljs-number">1</span>) {
        System.out.println(<span class="hljs-string">"Move disk 1 from "</span> + from + <span class="hljs-string">" to "</span> + to);
        <span class="hljs-keyword">return</span>;
    }
    towerOfHanoi(n - <span class="hljs-number">1</span>, from, aux, to);
    System.out.println(<span class="hljs-string">"Move disk "</span> + n + <span class="hljs-string">" from "</span> + from + <span class="hljs-string">" to "</span> + to);
    towerOfHanoi(n - <span class="hljs-number">1</span>, aux, to, from);
}
</code></div></div></pre><hr><h3>3. <strong>How do you convert a recursive function to an iterative one?</strong></h3><p><strong>Example:</strong> Converting <strong>factorial</strong> recursion into an iterative solution.</p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">int</span> <span class="hljs-title function_">factorial</span><span class="hljs-params">(<span class="hljs-type">int</span> n)</span> {
    <span class="hljs-type">int</span> <span class="hljs-variable">result</span> <span class="hljs-operator">=</span> <span class="hljs-number">1</span>;
    <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> <span class="hljs-number">1</span>; i &lt;= n; i++) {
        result *= i;
    }
    <span class="hljs-keyword">return</span> result;
}
</code></div></div></pre><hr><h3>4. <strong>What are the limitations of recursion?</strong></h3><ul><li><strong>Stack Overflow</strong>: Too many recursive calls (deep recursion) can cause a <strong>stack overflow</strong>.</li><li><strong>Overhead</strong>: Recursive functions can be less efficient because of repeated function calls.</li></ul><hr><h2><strong>Time and Space Complexity: Tricky Questions and Analysis</strong></h2><h3>1. <strong>What is the difference between Time and Space Complexity?</strong></h3><ul><li><strong>Time Complexity</strong>: Measures how the <strong>runtime</strong> of an algorithm grows as the input size increases.</li><li><strong>Space Complexity</strong>: Measures how much <strong>extra memory</strong> the algorithm uses as the input size grows.</li></ul><hr><h3>2. <strong>How to Calculate Time Complexity for Loops?</strong></h3><p><strong>Single Loop Example:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>; i &lt; n; i++) {
    System.out.println(i);
}
</code></div></div></pre><ul><li><strong>Time Complexity:</strong> O(n) because the loop runs <code>n</code> times.</li></ul><p><strong>Nested Loop Example:</strong></p><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">i</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>; i &lt; n; i++) {
    <span class="hljs-keyword">for</span> (<span class="hljs-type">int</span> <span class="hljs-variable">j</span> <span class="hljs-operator">=</span> <span class="hljs-number">0</span>; j &lt; n; j++) {
        System.out.println(i + <span class="hljs-string">" "</span> + j);
    }
}
</code></div></div></pre><ul><li><strong>Time Complexity:</strong> O(n²) because the inner loop runs <code>n</code> times for each iteration of the outer loop.</li></ul><hr><h3>3. <strong>How to Calculate Space Complexity for Recursive Functions?</strong></h3><ul><li><strong>Example: Fibonacci Recursive Code</strong><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-type">int</span> <span class="hljs-title function_">fibonacci</span><span class="hljs-params">(<span class="hljs-type">int</span> n)</span> {
    <span class="hljs-keyword">if</span> (n &lt;= <span class="hljs-number">1</span>) <span class="hljs-keyword">return</span> n;
    <span class="hljs-keyword">return</span> fibonacci(n - <span class="hljs-number">1</span>) + fibonacci(n - <span class="hljs-number">2</span>);
}
</code></div></div></pre></li><li><strong>Time Complexity:</strong> O(2ⁿ) because each call makes two more calls.</li><li><strong>Space Complexity:</strong> O(n) because the maximum depth of the recursion stack is <code>n</code>.</li></ul><hr><h3>4. <strong>What is Amortized Time Complexity?</strong></h3><ul><li><strong>Explanation:</strong> Amortized analysis finds the <strong>average time</strong> per operation over a sequence of operations, even if some individual operations are expensive.</li><li><strong>Example:</strong> In a dynamic array, most inserts take <strong>O(1)</strong> time, but occasionally when the array grows, it takes <strong>O(n)</strong> time.</li></ul><hr><h3>5. <strong>How to Analyze Time Complexity of Recursion?</strong></h3><ul><li><strong>Example:</strong><pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary">java</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-java"><span class="hljs-keyword">void</span> <span class="hljs-title function_">func</span><span class="hljs-params">(<span class="hljs-type">int</span> n)</span> {
    <span class="hljs-keyword">if</span> (n &lt;= <span class="hljs-number">1</span>) <span class="hljs-keyword">return</span>;
    func(n - <span class="hljs-number">1</span>);
    func(n - <span class="hljs-number">1</span>);
}
</code></div></div></pre></li><li><strong>Time Complexity:</strong> O(2ⁿ). Each call spawns two more calls, forming a binary tree of calls.</li></ul><hr><h2><strong>Summary of Key Tricks and Patterns</strong></h2><ul><li><strong>Linked Lists</strong>: Use the <strong>slow and fast pointer technique</strong> for cycle detection, and always <strong>adjust head and tail</strong> pointers carefully during reversal.</li><li><strong>Recursion</strong>: Always identify the <strong>base case</strong> to prevent infinite recursion, and be mindful of <strong>stack overflow</strong> errors.</li><li><strong>Time Complexity</strong>: Practice breaking down loops and recursion into simple steps to correctly identify the time complexity.</li><li><strong>Amortized Complexity</strong>: Understand it well for <strong>dynamic data structures</strong> like <strong>ArrayLists</strong>.</li></ul><hr><p>This detailed review covers all tricky aspects of <strong>Linked Lists, Recursion, and Time &amp; Space Complexity</strong>. Do you need further clarification or practice questions on any part?</p>
