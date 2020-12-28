# Leetcode 1. Two Sum
> Difficulty : <b> Easy </b>


***
* Leetcode의 첫 문제이며 난이도는 Easy이다. 하지만 leetcode에서의 난이도는 믿을만한게 아니기 때문에 생각보다 어려울수도 있다...

문제를 간략히 설명하면 Target Number와 int형 배열을 입력 받았을 때 배열 내에서 더해서 Target Number가 될 수 있는 값의 쌍을 찾으면 된다.
<details>
<summary> 원문 </summary>
<div markdown="1">
Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

You can return the answer in any order.
</div>
</details>
###### Example 1:
	Input: nums = [2,7,11,15], target = 9
	Output: [0,1]
index가 0, 1인 2와 7의 합이 9이기 때문에 위와 같은 output을 얻을 수 있다.

###### Example 2:
	Input: nums = [3,2,4], target = 6
	Output: [1,2]
index가 1, 2인 2와 4의 합이 6이기 때문에 위와 같은 output을 얻을 수 있다.
<br><br>
####풀이
***
가장 먼저 든 생각은 C++ 표준 라이브러리에서 사용할 수 있는 Map container였다.
해당 문제에서 사용할 수 있는 Map Container의 특징은 다음과 같다.
* 
