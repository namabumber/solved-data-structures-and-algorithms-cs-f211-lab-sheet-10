Download Link: https://assignmentchef.com/product/solved-data-structures-and-algorithms-cs-f211-lab-sheet-10
<br>
5/5 - (2 votes)

<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">1. IPL is in full flow and now teams have to choose the best possible opening pair for their team. Given N right-handed batsmen and N left-handed batsmen and their respective average scores. Find out the best k combinations of left and right-handed batsmen. Time Complexity: O(N* k).</span>

Sample Input FormatNkArray with average scores for right-hand batsmen Array with average scores for left-hand batsmen

Sample Input 1

22 12 34

Sample Output 1

65

Sample Input 2

44 1423 2516

Sample Output 2

10 9 9 8

2. Given N bags, each bag contains Ai kg of meat. There is a kid and a magician. In one unit of time, kid chooses a random bag i and he can eat maximum of Ai kg of meat, then the magician fills the ith bag with floor(Ai/2) kg of meat.

Given Ai for 1 &lt;= i &lt;= N, find the maximum number of meat kid can eat in K units of time.

Input Format NKArray A

Sample Input 1

23 65

Sample Output 1

14

3. You are given a stream of asteroid sizes and you need to find the median of the size of the asteroid you have observed at each time step. You will be given N, the length of the stream and an array of numbers representing the size of the new asteroid of that time step.

Required Time Complexity – O(N * logN)

Sample Input

45 15 1 3

Sample Output

5 10 5 44. Given a level order traversal of a binary tree, find out if that tree follows the property of min heap.

Sample Input

410 15 14 25 30

Sample Output

True

Sample Input

510 9 8 7 6

Sample Output

False

5. Given a level order traversal of min heap, convert it into max heap and print its level order traversal

Sample Input103 5 9 6 8 20 10 12 18 9

Sample Output

20 18 10 12 9 9 3 5 6 8

6. Arya is a huge cricket fan, so he decides that he’ll meet his five favourite cricketers in this problem-set of heaps. And he’ll try to impress them. The first cricketer he wants to impress is: Kane Williamson. He asked Williamson to answer some queries in a press interview. Williamson is irritated by Arya’s constant interruption during his interview, so Williamson decides to give Sharat a run for his money by asking him the answer to various queries. Williamson will give a query of the types mentioned below to Sharat and will expect him to answer those.

<ul>

 <li>●  Push X — Insert Williamson’s score in an array. – Query type 1.</li>

 <li>●  Diff — Find out the difference between Willamson’s current highest and current lowest score,</li>

</ul>

Note that the level order traversal of the above tree is 1 2 3 4 5.

currently present in the array. And then remove a single instance of each of those values from the

<table>

 <tbody>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

 </tbody>

</table>

array. – Query type 2.In case, the current lowest and current highest score are same, then only one instance of that score will be removed from the array.

<ul>

 <li>●  CountHigh — Find out the number of times Williamson has scored his current highest score, currently present in array. – Query type 3.</li>

 <li>●  CountLow — Find out the number of times Williamson has scored his current lowest score, currently present in array. – Query type 4.</li>

</ul>

Input format

The first line contains an integer Q, which denotes the number of queries which have to be dealt by Sharat. The next Q lines will contain a query like the ones mentioned above.

Output format

For the query types 2, 3, and 4, print the answer in a new line. If there is no record of any innings, that is, the array of Williamson’s score is empty for query type 2, 3 and 4, then print -1.

Example Input10 CountHigh Push 442 CountHigh Push 7555 Diff

Push 2799 DiffPush 8543 Diff

Diff

Output

-11 7113 00-1

7. Given an array arr[] of size n containing 0 and 1 only. The problem is to count the subarrays having equal number of 0’s and 1’s.

Input

{1,0,0,1,0,1,1}

Output

8Explanation: The sub arrays are: {1,0}, {0,1}, {1,0}, {0,1}, {1,0,0,1}, {0,1,0,1}, {1,0,0,1,0,1}, {0,0,1,0,1,1}.

8. There are N chairs arranged in a row. K people come in a line and start occupying the chairs. Each person wants to be as far as possible from every other person. So, every person arriving looks for the largest empty

continuous sequence of unoccupied chairs and occupies the middle position. They have a preference indicating whether they would choose the left or the right chair if there are two chairs at the middle to choose from (else the preference does not matter, since there is only 1 chair at the centre). If there are multiple largest empty sequences, then the person chooses the sequence which appears first from left side.

You are asked to answer Q queries. Determine which person has occupied the queried position.

Input Format

The first line of every test file are 2 integers N and K.

The next line contains a string S of length K. The ith character would be ‘L’ or ‘R’ indicating the preference

of the ith person – the left or the right seat respectively.

Next line contains an integer Q – the number of queries.

Next Q lines contain an integer Qi – the queried position.

Output Format

For each query, output the persons’ entry number if it is occupied, else print ‘−1’ without quotes in a new

line.

Example

Input

53

RLR

5 1 2 3 4 5

Output

2

-1

1

-1

3