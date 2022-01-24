# Lab 2: 
## Code Change 1: Image in markdown
 Images should not be included in the markdownParse() list of links
 
 1. Github Code Change 
 ![image](Change1_GithubCodeChange.png)
 
 2. Link to the failure inducing test file 
 
 [File that caused image Error](https://rsavoj.github.io/cse15l-lab-reports/Lab-report-2/testfile2.md)
 
 3. Symptom of failure:  Images should not be included in the markdownParse() list of links
 ![image](Change1_Symptom.png)

 4. Relationship between the bug and the symptom: The markdownParse() code identifies links using brackets and parenthesis. Images also use brackets and parenthesis for formating in markdown. If we use the original markdownParse() code it will read the image as a link. The symptom of this bug is that the image is included in the list of links. To fix this bug we added a line of code checking if the image had a ! before it. If this was the case then the code would skip over the image and not add it to the list of links.

 
