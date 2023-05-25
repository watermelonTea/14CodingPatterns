# 14CodingPatterns
14 Coding Patterns according to Fahim ul Haq

## In an attempt to improve my coding skills I will follow this article and try to gain knowledge on these 14 patterns using supplementary resources.

To outline the 14 patterns that [Fahim ul Haq](https://hackernoon.com/u/fahimulhaq) brings up, we have:

 - Sliding Window
 - Two Pointers or Iterators
 - Fast and Slow Pointers
 - Merge Intervals
 - Cyclic Sort
 - In-place reversal of Linked List
 - Tree Breadth First Search
 - Tree Depth First Search
 - Two Heaps
 - Subsets
 - Modified Binary Search
 - Top K Elements
 - K-way Merge
 - Topological Sort
# Sliding Window
According to Fahim, a sliding window pattern is a pattern that requires you to perform an **operation** on a specific window of a given array or linked list. 
 - An example he provides is as follows: 	
	 - FIND THE LONGEST SUBARRAY CONTAINING ALL 1's.

So, a sliding window is the "window" that is sliding along the given array as you continue to perform which ever operation is requested from you.

	![sliding window](https://files.catbox.moe/rhhs55.png)
You can see here that the Window began on the first two elements of the array and has **slid** to the next position. 
Key Identifiers:

 - The problem contains a *list*, *array*, or *string*. These items are ***linear*** in the fact that when you visualize or imagine these things they are typically in a linear fashion. 
 - You are presented with the task of finding the longest/shortest substring, subarray, or a specific value.
	 - What the heck does this mean?
		 - Longest or Shortest Substring = A continuous sequence of characters within a larger string.
			 - Find the largest substring without repeated characters in **abcabcbb**
				 - "abc" would be the longest substring with unique characters.
		 - Longest or Shortest Subarray = A contiguous(*together in a sequence*) portion of an array.
			 - Given the array [2, 1, 3, 5, 4, 2, 6], find the shortest subarray that contains all unique elements.
				 - In [2, 1, 3, 5, 4, 2, 6], the shortest unique subarray is [3, 5, 4].

Resources:
*The article that the majority of this write-up is based on:
https://hackernoon.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed*
