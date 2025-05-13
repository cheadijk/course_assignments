## **Problem-Solving Practice Questions**

### **Introduction:**  
These problems are designed to test your critical thinking and problem-solving abilities. By solving these, you will improve your logical reasoning and ability to approach real-world challenges with structured solutions.

### **Objective:**  
The goal of this exercise is to enhance your problem-solving skills by tackling a variety of puzzles. By the end of this task, you should be able to think critically and apply logical steps to solve complex problems.

---

### **Questions:**

1. **The Chocolate Bar Problem**  
   There is a chocolate bar that is divided into 16 smaller squares, and you have to break it down into individual squares. How many breaks are needed to split the entire bar into individual squares?  
   
   To break a chocolate bar into 16 individual squares, you need to make 15 breaks.
   Each break increases the total number of pieces by one.
   Start with 1 whole piece (the full bar). After 1 break → 2 pieces, after 2 breaks → 3 piecesm and then after 15 breaks → 16 pieces. 

2. **The Light Bulb Problem**  
   You have 3 light bulbs in a room and 3 switches outside the room. How can you figure out which switch controls which bulb if you can only enter the room once?

   1. Turn ON Switch 1, and leave it on for 5–10 minutes. This will allow the corresponding bulb to heat up.
   2. Turn OFF Switch 1, and turn ON Switch 2.
   3. Leave Switch 3 OFF.
   4. Now, go into the room.

   The bulb that is on corresponds to Switch 2 (it’s currently receiving power).
   The bulb that is off but warm corresponds to Switch 1 (it was on for a while, then turned off).
   The bulb that is off and cold corresponds to Switch 3 (it was never turned on).

3. **The Water Jug Problem**  
   You have two jugs: one can hold 5 liters and the other can hold 3 liters. How can you measure exactly 4 liters using only these two jugs?

   1. Fill Jug B (3L) fully → Jug A: 0L, Jug B: 3L
   2. Pour Jug B into Jug A → Jug A: 3L, Jug B: 0L
   3. Fill Jug B again → Jug A: 3L, Jug B: 3L
   4. Pour Jug B into Jug A until A is full
      Jug A needs 2L more to be full (since it already has 3L)
      So you pour 2L from Jug B into Jug A → Jug A: 5L (full), Jug B: 1L left
   5. Empty Jug A → Jug A: 0L, Jug B: 1L
   6. Pour remaining 1L from Jug B into Jug A → Jug A: 1L, Jug B: 0L
   7. Fill Jug B again (3L) → Jug A: 1L, Jug B: 3L
   8. Pour Jug B into Jug A (which currently has 1L, so it can take 4L max)
      → Jug A: 4L, Jug B: 0L

4. **The Wolf, Goat, and Cabbage Problem**  
   A farmer needs to get a wolf, a goat, and a cabbage across a river. He has a boat that can only carry him and one other item at a time. How can he cross the river with all three without the wolf eating the goat or the goat eating the cabbage?

   1. Take the goat across the river and leave it on the other side.
      Left: wolf, cabbage
      Right: goat
   2. Return alone to the original side.
   3. Take the wolf across the river.
   4. Bring the goat back with you.
      Left: goat
      Right: wolf
      In boat: farmer and goat
   5. Take the cabbage across the river.
   6. Return alone to the original side.
   7. Take the goat across the river one final time.
      Left bank: empty
      Right bank: wolf, goat, cabbage
      No one got eaten.

5. **The Bridge and Torch Problem (Multiple Versions)**  
   Four people need to cross a bridge at night. They have only one flashlight, and at most two people can cross the bridge at a time. Different people walk at different speeds: 1 minute, 2 minutes, 5 minutes, and 10 minutes. When two people cross together, they must walk at the slower person's pace. How can all four people cross the bridge in 17 minutes?

   1. A and B cross → 2 minutes
      Left: C, D
      Right: A, B
      Flashlight is on the right
   2. A returns → 1 minute
      Left: A, C, D
      Right: B
      Total time: 2 + 1 = 3 minutes
   3. C and D cross → 10 minutes
      Left: A
      Right: B, C, D
      Flashlight is on the right
      Total time: 3 + 10 = 13 minutes
   4. B returns → 2 minutes
      Left: A, B
      Right: C, D
      Total time: 13 + 2 = 15 minutes
   5. A and B cross again → 2 minutes
      All four are now across
      Total time: 15 + 2 = 17 minutes

6. **The Coin Puzzle**  
   You have 12 coins, one of which is either heavier or lighter than the rest. Using a balance scale, what is the minimum number of weighings required to find the odd coin?

   Each weighing on a balance scale gives 3 outcomes:
   - Left heavier
   - Right heavier
   - Balanced

   So, in 𝑛 weighings, the number of distinct outcomes is: 3𝑛
 
   With 3 weighings, that’s: 3³ =  27 possible outcomes

   You have 12 coins, and the odd one could be either heavier or lighter, so there are:
   12 × 2 = 24 scenarios

   Since 27 ≥ 24, it is possible to identify both:
   - Which coin is odd
   - Whether it is heavier or lighter
   
   within 3 weighings.

7. **The Egg Drop Problem**  
   You have two identical eggs and a building with 100 floors. The eggs are strong enough to be dropped from some floors, but will break if dropped from too high. What is the minim?

   You need to balance the strategy between:
   - Minimizing drops if the first egg breaks early.
   - Not wasting too many drops on safe floors.

   The optimal solution is to drop the first egg in decreasing intervals to allow exactly 14 total drops at worst:
   Step-by-step idea:
   1. Drop the first egg from floor 14
   2. If it doesn't break, go to floor 27 (14 + 13)
   3. Then floor 39 (27 + 12)
   4. Then floor 50 (39 + 11)
   5. Then floor 60 (50 + 10)
   6. Then floor 69 (60 + 9)
   7. Then floor 77 (69 + 8)
   8. Then floor 84 (77 + 7)
   9. Then floor 90 (84 + 6)
   10. Then floor 95 (90 + 5)
   11. Then floor 99 (95 + 4)
   12. Then floor 100 (99 + 1)

   If the first egg breaks at any point, say at floor 69, you use the second egg to test each floor one by one from floor 60 to 68 — up to 8 additional drops.
   But because the steps are shrinking (14 → 13 → 12 ...), even in the worst case, you won’t need more than 14 total drops.
   The minimum number of drops required in the worst case is 14.