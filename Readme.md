# Extended Hanoi
In this assignment, we delve into one of the most renowned problems in recursive functions: The Towers of Hanoi. However, this assignment is based on the extended form of it.

In this assignment, you won't need to implement the graphic of the project. The only thing you will need to do is to complete four functions below.

Before we start, let me clarify that first of all, you should try to write pseudocode for each function. After that, try to convert it to JavaScript code. To convert your pseudocode to JavaScript code, you can use the following example in this project:
```
pseudocode: Move A ----> B
JS Code: moves.push([A, B])
```
## Hanoi
As you may know, when implementing extended Hanoi problems, you will need to use the Hanoi function. So, first, please implement the normal Hanoi function. This function is created to move n disks from the "from" rod to the "to" rod, with the help of the "via" rod.

## exhanoi_1
The first extended Hanoi problem involves three rods. When you enter a number n, 3 disks go on the third rod, 2 disks go on the second rod, and 1 disk goes on the first rod. This operation continues until the number of disks on the first rod reaches n. Implement this function to move all disks to the third rod.

## exhanoi_2
The second extended Hanoi problem involves four rods. When you enter a number n, n gray disks go on the third rod, and n white disks go on the first rod. Your task is to complete this function to change disks in the first rod with those in the third rod. Remember, you cannot put two disks with opposite colors on each other.

## exhanoi_3
The third extended Hanoi problem involves three rods. When you enter a number n, 1 disk goes on the first rod, and 2 disks go on the second rod. This operation continues until the number of disks on the second rod reaches 2n. The task of this function is to move all disks to the third rod.

### Important note
Don't forget that all of these functions act as rules of the classic Hanoi problem, and all of those rules still apply.

