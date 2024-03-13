# labreport5


**Part 1**

1. Scenario
I'm having trouble with my autograding script and writing my code in Java and it is not working. I have set up a bash script that compiles and runs for the student Java code. However, it's showing errors and failure for the output which is not what I expected. Expected result `autograding passed`
<img width="761" alt="截圖 2024-03-12 下午9 01 39" src="https://github.com/3van20230/Lab5/assets/156235233/5298fa3a-d08f-4af2-b9d2-821e244a9e28">
<img width="855" alt="截圖 2024-03-12 下午9 01 13" src="https://github.com/3van20230/Lab5/assets/156235233/072fbb8c-a3ca-4567-9dbc-30d24ab281ba">

As you can see, it's not saying anything even though the program seems to be running fine. 

2. TA responding:
It looks like your script is indeed encountering an issue with the comparison of the output. One thing you can try is to run the script with some sample inputs and see what output it produces. You can do this by running the script manually and providing input to the program.

3. screen shot of trying:
<img width="917" alt="截圖 2024-03-12 下午9 04 47" src="https://github.com/3van20230/Lab5/assets/156235233/1e963240-fadc-4c17-bdd3-7245587cd01e">

<img width="738" alt="截圖 2024-03-12 下午9 04 58" src="https://github.com/3van20230/Lab5/assets/156235233/4699d00f-3503-4c1f-ae5e-6354a6b207a2">

4. 
Command Line:
./autograde.sh
Description of what to edit to fix the bug:
we added a comparison step to ensure the accuracy of the auto grading process. After compiling the Java program, we run it and capture the output in a variable called student_output. We then compare this output with the expected output using an if statement. If the student's output matches the expected output.

**Part 2**

Reflecting: 
  The autograding from Week 6 was definitely one of my favorite labs in this class. Having taken CSE12 previously, where practice assignments were turned in through autograding, I was already familiar with the concept. However, I had always been curious about how it works. This lab provided me with the opportunity to delve deeper into the structure and inner workings of autograding.

  Through this experience, I gained a better understanding of the skills involved and how they contribute to the overall assessment process. It was enlightening to see how the feedback loop between coding practice and automated assessment enhances learning. This lab has certainly enriched my appreciation for the course material and the connection between both classes.

  Overall, I thoroughly enjoyed the lab and found it to be a valuable learning experience. It has motivated me to continue exploring the intersection of coding practice and automated assessment in my studies.



