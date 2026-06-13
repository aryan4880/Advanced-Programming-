# Advanced Programming 

## Question
Develop a student performance analyzer in Java. You are given a list of students of your batch. Each student has: id (int) //don't include CSB string name (String) courses (List) scores (Map<String, Integer>) where key = course, value = marks

Do:

Store students using appropriate collections.
Implement the following methods: List getTopNStudents(List students, int n); Map<String, Double> getAverageScorePerCourse(List students); Set getAllUniqueCourses(List students);
Must use:

Use ArrayList, HashMap, and HashSet
Use Streams for aggregation and filtering
Sort students by average score (descending)
Use Comparator
Handle missing course scores using getOrDefault
Ensure type safety using generics
Perform complexity analysis:

What is the time complexity of computing course averages?
What is the complexity of sorting top N students?

