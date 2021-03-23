# a1
SE 4367.001

**Part Zero**
Part zero of MP1 was about setting up Eclipse and Soot and ensuring buildpaths. 



**Part One**
Part one mainly had to deal with the sample codes TestDominatorFinder.java, DominatorFinder.java and the test program GCD.java.
![image](https://user-images.githubusercontent.com/34780150/112222964-3f4b1400-8bf7-11eb-93c4-0757f2fd117b.png)

In this second image, we can see where TestDominatorFinder.java is using Soot to build a control graph.
![part1](https://user-images.githubusercontent.com/34780150/112223053-5d187900-8bf7-11eb-848d-a02b2c7ad943.png)

The following image shows that the method doAnalysis, is already completed with the given code.
![image](https://user-images.githubusercontent.com/34780150/112223529-10816d80-8bf8-11eb-9351-fc375fc74c05.png)



**Part Two**
Part two had us comparing different call graph construction algorithms.

The first image is an example of runnning TestSootCallGraph without CHA or Spark enabled. Total edges: 16.
![part2](https://user-images.githubusercontent.com/34780150/112224977-16784e00-8bfa-11eb-9f24-b5f500a1adc4.png)

The second image is an example of runnning TestSootCallGraph with CHA enabled. Total edges: 3105.
![image](https://user-images.githubusercontent.com/34780150/112225297-8b4b8800-8bfa-11eb-87fc-66965e011bdf.png)

The third image is an example of runnning TestSootCallGraph with Spark enabled. Total edges: 12.
![image](https://user-images.githubusercontent.com/34780150/112225624-0f9e0b00-8bfb-11eb-8d44-d01821ce3e3f.png)

The number of total edges between CHA and Spark is an extreme difference. I suspect there is something I am missing here. 
