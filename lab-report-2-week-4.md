# Lab Report 2 Week 4

## Breaking Test Case 1:

>Code change Diff:
>![](MarkdownDiffs1.png)
>![](MarkdownDiffs2.png)
>![](MarkdownDiffs3.png)
>[Link to failing test case](https://github.com/Carly-Freedman/markdown-parser/blob/main/test-file1.md)
>
>Symptom:
>![](MarkdownSymp1.png)
>
>The failure inducing input contains a link without a closing bracket. So, the bug is that the program has no final parenthesis to find, causing it to search for a substring starting at an index of -1 which does not exist. Therefore, we receive the symptom of the IndexOutOfBounds Error. 

## Breaking Test Case 2:

>Code Change Diff:
>![](MarkdownDiffs4.png)
>![](MarkdownDiffs5.png)
>![](MarkdownDiffs6.png)
>![](MarkdownDiffs7.png)
>[Link to failing test case](https://github.com/Carly-Freedman/markdown-parser/blob/main/test-file2.md)
>
>Symptom:
>![](MarkdownSymp1.png)
>
>The failure inducing input contains a link without an opening bracket. So, the bug is that the program has no first parenthesis to find, causing it to search for a substring starting at an index of -1 which does not exist. Therefore, we receive the symptom of the IndexOutOfBounds Error. 

## Breaking Test Case 3:

>Code change diff:
>![](MarkdownDiffs8.png)
>[Link to failing test case](https://github.com/Carly-Freedman/markdown-parser/blob/main/test-file3.md)
>
>Symptom:
>![](MarkdownSymp1.png)
>
>The failure inducing input contains a link without opening and closing brackets. So, the bug is that the program has no parenthesis to find, causing it to search for a substring starting at an index of -1 which does not exist. Therefore, we receive the symptom of the IndexOutOfBounds Error. 



