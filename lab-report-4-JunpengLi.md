**Lab Report 4**
>
**Name:Junpeng Li(Johnson)**
>
**Professor Joe**
>
**CSE 15L**
>
___
## Link to my markdown-parse repository
[myMarkdown-parse](https://github.com/johnsonli010801/markdown-parse)
>
## Link to the repository that I review
[review-Markdown-Parse](https://github.com/Darrengn/markdown-parse)
___
# Expected output for each snippet
>
**snippet1 expected output in CommonMark demo site [link](https://spec.commonmark.org/dingus/)**
![image](lab4-1.png)
___
```
Expected will be [`google.com, google.com, ucsd.edu]
```
>
**snippet2 expected output in CommonMark demo site**
![image](lab4-2.png)
___
```
Expected will be [a.com, a.com(()), example.com]
```
>
**snippet3 expected output in CommonMark demo site**
![image](lab4-3.png)
___
```
Expected will be [https://ucsd-cse15l-w22.github.io/]
```
>
# Test cases within my repository
![image](lab4-myTest.JPG)
![image](lab4-myTestTerminal.png)
___
>
Literally, all the three test cases within my program has failed. The output console in the terminal is shown above. Most likely, the java program within my repository did not cover those special cases of links.
>
___
# Test cases within the review implementation repository
![image](lab4-reviewImpleTest.png)
**Terminal**:
![image](lab4-reviewTestTerminal1.png)
![image](lab4-reviewTestTerminal2.png)
>
Actually, all the test cases within the program that our lab group reviewed last week are also failed because the program did not complementarily cover those special link cases.

# Answer toward the three questions:
*Do you think there is a small(<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes describe the code change. If not, describe why it would be a more involved change.*
