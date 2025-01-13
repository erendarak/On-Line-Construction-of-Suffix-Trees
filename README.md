# CS333 Algorithm Analysis - Spring 2024

## Project Title: On-Line Construction of Suffix Trees

### Group Members
- **Eren Darak** (eren.darak@ozu.edu.tr)
- **Ahmet Berkay Arslanpençe** (berkay.arslanpence@ozu.edu.tr)

---

### Project Description
This project explores the development and analysis of an **on-line algorithm** for constructing suffix trees with **linear time complexity**. Our study builds upon Ukkonen's foundational work on suffix tree construction, presenting modifications and insights aimed at enhancing efficiency and comprehensibility.

Suffix trees are critical data structures for efficient string operations. They are particularly useful in applications such as:
- Pattern matching
- Text compression
- Bioinformatics

The proposed algorithm processes strings symbol by symbol in a left-to-right manner, maintaining the suffix tree for the scanned portion of the string at all times. It is designed to optimize performance by:
- Reducing space complexity using pointers for edge representation.
- Introducing suffix links for efficient node traversal.

### Key Features
- **On-line Algorithm**: Constructs the suffix tree as the string is read.
- **Linear Time Complexity**: Processes the string in O(n) time, where n is the string length.
- **Practical Modifications**: Enhances understanding and efficiency of suffix tree construction.

---

### Resources and References
We used the following resources to support our research:

#### Papers
- Ukkonen, E. "On-Line Construction of Suffix Trees." Algorithmica, vol. 14, 1995, pp. 249-260.

#### Visualizations
- Kokoszka, Brenden. [Visualization of Ukkonen’s Algorithm](https://brenden.github.io/ukkonen-animation/)

#### Tutorials
- GeeksforGeeks: [Ukkonen's Suffix Tree Construction](https://www.geeksforgeeks.org/ukkonens-suffix-tree-construction-part-1/)

---

### Project Components
1. **Research Proposal**
   - An overview of the project goals and expected outcomes.

2. **Research Report**
   - Detailed explanation of the algorithm and its analysis.
   - Comparative study with existing methods.
   - Discussion of results and observations.

---

### How to Use
While the project focuses on theoretical analysis and does not include implementation, we recommend the following tools for hands-on learning:
- **GeeksforGeeks tutorials** for step-by-step construction.
- **Brenden's visualization** to understand the algorithm dynamics.

---

### Future Work
- Extending the algorithm to handle dynamic strings efficiently.
- Implementing the algorithm in a programming language for practical use.

---

### Contact
For any questions or further collaboration, please reach out to the group members via their email addresses provided above.
