# Performance Analysis between ArrayList and LinkedList
This is a Java project that evaluates the performance of ArrayList and LinkedList for various operations, such as adding and removing elements from the beginning, middle, and end of the list.

# Requirements
- Java Development Kit (JDK) 8 or later
- Apache Maven
# How to run
- Clone this repository
- Navigate to the project directory using the command line
- Build the project with Maven: mvn clean package
- Run the project: java -cp target/list-evaluation-1.0-SNAPSHOT.jar ListEvaluation
# Results
The following operations were evaluated and the time it took to complete them in milliseconds was recorded:

- Add 100 elements to the beginning of the list
- Add 100 elements to the middle of the list
- Add 100 elements to the end of the list
- Remove 100 elements from the beginning of the list
- Remove 100 elements from the middle of the list
- Remove 100 elements from the end of the list
- Add 10,000 elements to the beginning of the list
- Add 10,000 elements to the middle of the list
- Add 10,000 elements to the end of the list
- Remove 10,000 elements from the beginning of the list
- Remove 10,000 elements from the middle of the list
- Remove 10,000 elements from the end of the list
- The results of the evaluation are printed to the console in milliseconds for each operation.

# Conclusion
Based on the evaluation, ArrayList performs better than LinkedList for operations that involve adding or removing elements from the end of the list. However, for operations that involve adding or removing elements from the beginning or middle of the list, LinkedList performs better than ArrayList. Therefore, the choice between ArrayList and LinkedList depends on the specific use case and the type of operations performed on the list.
