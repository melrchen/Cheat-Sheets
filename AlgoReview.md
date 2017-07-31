
## Algorithm Complexity

* Divid, conquer, and combine
* Master Theorem: `T(n)=2T(n/2)+n`
* Sterling's Approximation: `n! = \sqrt{ 2 \pi n} (\frac{n}{e})^n`

## Python Cost Models

| Operation       | List/array  | Dict/Hash Table  |
| --------------- |:-----------:| ----------------:|
| Append          | O(1)        | O(1)             |
| Search          | O(n)        | O(1)             |
| Remove          | O(n)        | O(1)             |
| Order preserved | Yes         | No               |

# Sorting 

* Comparison sort = decision tree with n! leaves


| Comparison? | Sort      | Time                   |  In Place  |  Stable  |
| ----------- |:---------:| :---------------------:| :--------: | -------: |
| Yes         | Insertion | \Theta(n+d) or O(n^2)  |  yes       |  yes     |
| Yes         | Merge     | \Theta(nlogn)          |  yes       |  yes     |
| Yes         | Heap      | \Theta(nlogn)          |  yes       |  no      |
| Yes         | AVL       | \Theta(nlogn)          |  no        |  yes     |
| No          | Counting  | \Theta(n+k)            |  no        |  yes     |
| No          | Radix     | \Theta((n+b)log_b(k)   |  no        |  yes     |

# Hashtables

# Trees

# Graphs

# Math

# Operating Systems
