Sure! Here's a rewritten version of the assignment with original phrasing to avoid plagiarism while retaining the core details:

---

# DataStructures-Assignment1

### Assignment 1 Submission

**Name:** Dhruvin Lad  
**Student ID:** c0903253  

---

### Question 1: Artifact Management

**Key Components:**
- **ArtifactVault Class:** This class manages an array of `Artifact` objects.
- **Add Artifact:** Adds new artifacts into the first available spot in the array and ensures that the array remains sorted.
- **Remove Artifact:** Deletes an artifact by name and shifts the remaining artifacts to fill the empty space.
- **Linear Search:** Implements a search by iterating through each element until a match is found.
- **Binary Search:** Performs a binary search on the sorted array to locate an artifact by its name.
- **Artifact Class:** Holds details about an artifact, such as its name and age, and implements the `Comparable` interface to facilitate sorting.

---

### Question 2: Path Navigation in a Labyrinth

**Key Components:**
- **Node Class:** Represents each location in the path, containing the name of the location and a reference to the next node.
- **Add Location:** Appends a new location at the end of the linked list.
- **Remove Last Location:** Removes the last location by traversing to the second-last node and adjusting pointers.
- **Loop Detection:** Implements Floyd’s Cycle-Finding Algorithm (using slow and fast pointers) to identify loops in the path.
- **Print Path:** Iterates over the list and prints out the locations.

**Explanation:**
- **Adding Locations:** New locations are added at the end of the list.
- **Removing Last Location:** The last location is removed by navigating to the second-last node and adjusting pointers.
- **Loop Detection:** A loop is detected if the fast and slow pointers meet, signaling the presence of a cycle.
- **Simulated Trap:** A loop was manually created by connecting the last node back to an earlier location in the list to simulate a trap.

---

### Question 3: Stack of Ancient Scrolls

**Key Components:**
- **Stack Class:** Uses Java’s built-in `Stack` to store scroll titles.
- **Push Operation:** Adds a scroll to the top of the stack.
- **Pop Operation:** Removes and returns the top scroll from the stack.
- **Peek Operation:** Retrieves the top scroll without removing it.
- **Search Operation:** Checks if a scroll exists using the `contains()` method.
- **Display:** Outputs all scrolls from top to bottom.

**Explanation:**
- **Push Scrolls:** Adds scrolls like “Ancient Scroll of Wisdom” to the stack.
- **Peek Scroll:** Displays the top scroll without removing it.
- **Search Scroll:** Checks for the presence of scrolls, such as “Scroll of Water Magic.”
- **Pop Scroll:** Removes the top scroll.
- **Display Stack:** Outputs the scrolls from top to bottom.

---

### Question 4: Explorer Queue (Circular Queue)

**Key Components:**
- **Circular Queue Class:** Implements a circular queue using an array.
- **Enqueue Operation:** Adds an explorer to the queue and handles wrap-around.
- **Dequeue Operation:** Removes an explorer from the front and adjusts pointers.
- **Peek Operation:** Retrieves the explorer at the front without removing them.
- **Check Full/Empty:** Determines whether the queue is full or empty.
- **Display Queue:** Shows the explorers currently in the queue.

**Explanation:**
- **Enqueue Explorers:** Adds explorers in the order they arrive.
- **Dequeue Explorers:** Removes explorers from the front as they leave.
- **Peek Explorer:** Displays the next explorer in line.
- **Full/Empty Check:** Verifies the queue status at different stages.

---

### Question 5: Clue Binary Tree

**Key Components:**
- **Binary Tree Class:** Represents a binary tree where clues are stored in nodes.
- **Insert Clue:** Adds clues while maintaining the binary search tree properties (left child smaller, right child larger).
- **Tree Traversal:** Implements in-order, pre-order, and post-order traversal methods.
- **Search Clue:** Searches for a clue using the binary search logic.
- **Count Clues:** Counts all clues in the tree recursively.

**Explanation:**
- **Inserting Clues:** Clues are added while maintaining the binary search tree properties.
- **Tree Traversals:** Demonstrates in-order, pre-order, and post-order visits to nodes.
- **Search Clue:** Searches for specific clues like “Clue B.”
- **Count Clues:** Counts and returns the total number of clues.

---

### Challenge Descriptions and Approach:

#### 1. **Artifact Array Management**
   - **Description:** Built a class to handle an array of artifacts with functionality to add, remove, and search the artifacts (both linearly and using binary search).
   - **Approach:** The array is kept sorted after each insertion, making binary search efficient. Removing an artifact shifts the remaining elements.
   - **Design Choices:** The array has a fixed size, and binary search assumes that the array is always sorted.
   
#### 2. **Linked List for Path Navigation**
   - **Description:** Designed a singly linked list to represent a labyrinth path with loop detection and location management.
   - **Approach:** Efficient location addition and removal, along with a loop detection algorithm to identify cycles in the path.
   - **Design Choices:** No duplicate location handling was required, and the list has no size limit.

#### 3. **Scroll Stack Management**
   - **Description:** Implemented a stack to manage ancient scrolls, providing methods for standard stack operations.
   - **Approach:** Standard stack operations like push, pop, and peek were implemented, along with a search function.
   - **Design Choices:** Stack overflow wasn’t handled, and the stack has a fixed size.
   
#### 4. **Circular Queue of Explorers**
   - **Description:** Built a circular queue to manage explorers.
   - **Approach:** The circular array efficiently handles the addition and removal of explorers while wrapping around when necessary.
   - **Design Choices:** Queue size is fixed.

#### 5. **Binary Tree of Clues**
   - **Description:** Developed a binary tree to manage clues, with methods for insertion, traversal, and searching.
   - **Approach:** Recursively implemented binary search tree properties for efficient clue searching.
   - **Design Choices:** Unique clues are assumed, and the tree is not self-balancing.

---

### Running the Code:

1. **Development Environment:** The code can be run using any Java IDE or environment like IntelliJ IDEA or Eclipse.
2. **Compilation:** Compile each class using:
   ```bash
   javac ClassName.java
   ```
3. **Execution:** Run the classes using:
   ```bash
   java ClassName
   ```
   Replace `ClassName` with the relevant class name for each part of the assignment.

---
