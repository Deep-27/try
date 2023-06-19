Problem
Statement:
Stonehall lies in ruins! The abyssal horde came out of nowhere, and it destroyed everything in its path.
What is left of Stonehall is a directed, unweighted and possibly disconnected graph �G with �N cities and �M roads. The �N cities in Stonehall are numbered from 11 to �N. Commander Tresdin is currently standing at an isolated and completely disconnected city �+1N+1 which is outside Stonehall. That is, there are no edges to or from this city currently. She vowed to destroy the Abyssal Underlord, and hence, wants to go down to the hunt!
Commander Tresdin can use her magic to create new directed roads, which would connect her isolated city �+1N+1 with any other city (from 11 to �N) in Stonehall. She wants that, starting from her city �+1N+1, there should be at least 11 path to reach every city in Stonehall. In other words, she wants that all cities from 11 to �N to be reachable from her city �+1N+1. Since time is short, you must help her by telling her the minimum number of new roads she needs to construct to achieve this.
Input:
•	The first line has �T, number of test cases in the file.
•	Next line has 22 integers, �N and �M, denoting number of cities and number of roads respectively
•	Next �M lines have 22 integers, � �u v, denoting that there is a directed road from �u to �v.
Output:
For each test case, print in a new line, the minimum number of roads/edges she needs to create to make every node reachable from Node �+1N+1.
Constraints
•	1≤�≤10001≤T≤1000
•	1≤�≤1051≤N≤105
•	1≤�≤2∗1051≤M≤2∗105
•	1≤�,�≤�1≤u,v≤N
•	Sum of �N over all test cases in a file is ≤106≤106
•	Sum of �M over all test cases in a file is ≤2∗106≤2∗106
Subtasks
•	20% points - �≤100,�≤200N≤100,M≤200
•	80% points - Original Constraints
Sample Input:
1
4 4
1 2
1 3
3 4
2 4
Sample Output:
1
EXPLANATION:
•	Initially Command Tresdin is at City �+1N+1 which is completely disconnected, isolated from Stonehall. It has no edges to and from it initially. In this case, �+1=5N+1=5.
•	She can make a directed road from city 55 to city 11.
•	City 11 is directly reachable from City 55 after construction of that road. From city 11, she can further reach to cities 2,32,3 and 44. Hence, all cities became reachable!

