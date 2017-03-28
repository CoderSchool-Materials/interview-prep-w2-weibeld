## iPrep Week 2: Big O and Hashtables

* **Big O Notation**: Describing an algorithm's complexity
* **Hashtables**: Stores data with key value pairs

What you will submit:
- A GitHub repo with this README file (with the boxes checked).
- Create a GIF showing your Interviewbit dashboard (see below) showing exercises you've done.

### Required tasks

**Big O Notation**

- [x] Watch [Big O Notation](https://www.youtube.com/watch?v=v4cd1O4zkGw)(8m)
  - Four rules to remember about the big-O notation:
    1. Different steps get added: e.g. `O(a+b)`
    2. Drop constants: not `O(2N)` but `O(N)`
    3. Use different variables for different inputs: e.g. `O(A*B)`
    4. Drop non-dominate terms: not `O(n^2 + n)` but `O(n^2)`
- [x] Read [Big O Notation in plain English](http://stackoverflow.com/questions/487258/what-is-a-plain-english-explanation-of-big-o-notation) and write down what you learned from it
  - I have learned that...
    - The base of the logarithm of a `O(log n)` complexity does not matter
- [x] Visit http://bigocheatsheet.com/ and think about how useful it could be to you
  - Very nice overview, need to order the poster :smiley:
- [x] Watch LogN in 5m: https://www.youtube.com/watch?v=kjDR1NBB9MU
  - I have learned that...
    - Complexity of quicksort is `O(n*log(n))`
  
**Hashtables**

- [x] Read [InterviewCake Hashtable](https://www.interviewcake.com/concept/java/hash-map?)
  - Hash table interview questions
- [x] Watch concept video: [HackerRank Video: Hash Tables](https://www.youtube.com/watch?v=shs0KM3wKv8) (6m)
  - I have learned that...
    - How hash tables internally work:
      1. Map key to hash code by a hash function
      2. Map hash function to an array index
      3. Store value in array at the calculated index
    - There are two causes of collisions
      1. Two different keys map to the same hash code
      2. Two different hash codes map to the same array index
    - One way to handle collisions: *chaining*
      - Array elements do not contain only single objects, but may contain multiple objects in the form of a linked list of key/value pairs

Extras: 
- [ ] [Introducing Hash Tables](https://www.youtube.com/watch?v=MfhjkfocRR0) (7m)
- [ ] [Hash Table Algorithms](https://www.youtube.com/watch?v=Ke_tII6Y0GE) (7m)

**Coding**

- [x] Set up an account on Interviewbit.com and start the [Programming course](https://www.interviewbit.com/courses/programming/)
- [x] Finish at least 2 tasks on Exercism

### Optional tasks

Some tasks are the same as optional tasks in Assignment 1.

- [ ] Do more tasks on exercism
- [ ] Finish [Time Complexity chapter](https://www.interviewbit.com/courses/programming/topics/time-complexity) in Level 1 of Interviewbit
- [ ] Finish [Arrays chapter]((https://www.interviewbit.com/courses/programming/topics/arrays/)) in Level 2 of Interviewbit
- [ ] Finish [Math chapter](https://www.interviewbit.com/courses/programming/topics/math/) in Level 2 of Interviewbit.
