# algo-efficiency-mini-project-sunisha_udar
🧮 **Assignment 1 – Data Analysis of Algorithms**

📘 **Introduction**

This assignment focuses on analyzing the time complexity and performance behavior of classical algorithms using Python.
The notebook demonstrates the implementation and comparison of fundamental algorithms such as the Fibonacci sequence and various sorting techniques.
Through experimental evaluation and graphical visualization, the assignment highlights differences in algorithmic efficiency and computational complexity.

🔢 **1. Fibonacci Series**
🔍 **Objective**

To implement and analyze the Fibonacci sequence using both recursive and iterative approaches and compare their time complexities.

🧠 **Description**

The Fibonacci series is a sequence where each term is the sum of the two preceding ones:

𝐹
(
𝑛
)
=
𝐹
(
𝑛
−
1
)
+
𝐹
(
𝑛
−
2
)
F(n)=F(n−1)+F(n−2)

with base conditions 
𝐹
(
0
)
=
0
F(0)=0 and 
𝐹
(
1
)
=
1
F(1)=1.

⚙️ **Implementation Steps**

Implemented a recursive function to calculate Fibonacci numbers.

Implemented an iterative approach for the same.

Compared execution times for various input sizes.

Visualized performance using matplotlib plots.

⏱️ **Time Complexity**

**Recursive Fibonacci:** 
𝑂
(
2
𝑛
)
O(2
n
) — exponential growth due to repeated subproblems.

**Iterative Fibonacci:** 
𝑂
(
𝑛
)
O(n) — linear time with constant space.

📊 **Observation**

As n increases, the recursive computation becomes extremely slow due to redundant calls, while the iterative computation remains efficient.
This demonstrates how algorithmic design directly affects runtime efficiency.

📚 **2. Bubble Sort**
🔍 **Objective**

To implement Bubble Sort and study its computational complexity and performance behavior.

🧠 **Description**

Bubble Sort repeatedly swaps adjacent elements if they are in the wrong order. This continues until the entire list is sorted.

⚙️ **Implementation Steps**

Created a function to perform Bubble Sort on an input list.

Recorded the number of comparisons and swaps.

Measured runtime for different list sizes.

Plotted time vs. input size for visualization.

⏱️ **Time Complexity**

**Best Case:** 
𝑂
(
𝑛
)
O(n) (when already sorted)

**Average Case:** 
𝑂
(
𝑛
2
)
O(n
2
)

**Worst Case:** 
𝑂
(
𝑛
2
)
O(n
2
)

📊 **Observation**

Bubble Sort performs poorly on large datasets due to its quadratic time complexity.
It is mainly used for educational purposes rather than real-world applications.

⚡ **3. Merge Sort**
🔍 **Objective**

To implement Merge Sort using recursion and evaluate its time complexity and space requirements.

🧠 **Description**

Merge Sort follows the divide and conquer approach by dividing the array into two halves, sorting each recursively, and merging them.

⚙️ **Implementation Steps**

Implemented recursive splitting of the array.

Performed merging of sorted subarrays.

Visualized recursion depth and time taken using graphs.

Compared performance for different input sizes.

⏱️ **Time Complexity**

**Best Case:** 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn)

**Average Case:** 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn)

**Worst Case:** 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn)

📊 **Observation**

Merge Sort provides stable and consistent performance even for large inputs.
However, it requires extra space for merging, leading to an auxiliary space complexity of 
𝑂
(
𝑛
)
O(n).

⚔️ **4. Quick Sort**
🔍 **Objective**

To implement Quick Sort and analyze its recursive behavior, partition strategy, and runtime efficiency.

🧠 **Description**

Quick Sort also uses the divide and conquer technique. It selects a pivot element, partitions the array around it, and recursively sorts the subarrays.

⚙️ **Implementation Steps**

Implemented recursive Quick Sort with partitioning.

Tracked recursion depth and number of swaps.

Plotted time complexity comparisons with Merge Sort.

Observed how pivot selection affects runtime.

⏱️ **Time Complexity**

**Best Case:** 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn)

**Average Case:** 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn)

**Worst Case:** 
𝑂
(
𝑛
2
)
O(n
2
) (for poor pivot choices)

📊 **Observation**

Quick Sort generally outperforms Merge Sort in average cases because of in-place partitioning and better cache utilization.
However, its performance degrades for already sorted data if the pivot is not chosen wisely.

📈 **5. Comparative Analysis of Sorting Algorithms**
⚙️ **Description**

All sorting algorithms were tested on lists of different sizes. Execution times were recorded, and results were visualized using matplotlib.

📊 **Observation**

Bubble Sort showed the slowest performance due to quadratic time complexity.

Merge Sort and Quick Sort exhibited significantly faster runtimes.

Quick Sort was slightly faster than Merge Sort in average cases but less consistent in the worst case.

🧩 **Conclusion**

Efficient algorithms such as Merge Sort and Quick Sort are ideal for large datasets, while simpler ones like Bubble Sort are useful for conceptual learning.
The Fibonacci comparison reinforced the importance of algorithm optimization and iterative improvements.

🧠 **Key Takeaways**

Recursive algorithms are elegant but often inefficient.

Iterative and divide-and-conquer methods significantly improve runtime.

Graphical analysis provides intuitive understanding of performance trends.

Understanding time complexity is essential for algorithmic efficiency.
