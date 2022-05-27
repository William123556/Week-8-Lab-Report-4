A link to your markdown-parse repository and a link to the one you reviewed in week 7

[Repo in my group](https://github.com/TuannDang/markdown-parser)
[Repo to review:](https://github.com/khiemddang/markdown-parser)

**Snippet 1**

<img width="295" alt="Screen Shot 2022-05-22 at 4 04 04 PM" src="https://user-images.githubusercontent.com/103155832/169719749-878c9e02-5551-4ae4-aece-74bf99f29e52.png">

the test cases I copy from the lab report and put this to the Common Mark Demo Site: https://spec.commonmark.org/dingus/

The sceent shot is below:

<img width="1261" alt="Screen Shot 2022-05-22 at 8 37 18 PM" src="https://user-images.githubusercontent.com/103155832/169738629-04d832bb-c564-4316-bcff-ed611e785257.png">


Showing the code in MarkdownParseTest.java for how I turned it into a test

<img width="468" alt="Screen Shot 2022-05-22 at 4 23 50 PM" src="https://user-images.githubusercontent.com/103155832/169720488-702a8190-aaba-4251-a4d5-7f0112388fdf.png">

the corresponding output when running the tests, my implementation failed. The image below shows the JUnitAssertion that was produced as a result of my implementation failing.

<img width="1065" alt="Screen Shot 2022-05-22 at 7 04 16 PM" src="https://user-images.githubusercontent.com/103155832/169729748-cd1fd2e0-51ef-49e9-9bf9-6a2ac75eaf25.png">

For the implementation you reviewed in Week7

<img width="1123" alt="Screen Shot 2022-05-22 at 7 23 39 PM" src="https://user-images.githubusercontent.com/103155832/169731591-423871b3-2122-4c60-b788-ec98682d06b7.png">

both implementations failed this test case.

**Snippet 2**

<img width="366" alt="Screen Shot 2022-05-22 at 7 25 56 PM" src="https://user-images.githubusercontent.com/103155832/169731834-f6fcf7c0-98b2-43e6-8eec-dc7491c2b2ed.png">

The sceentshot of Common Mark demo is below:

<img width="1256" alt="Screen Shot 2022-05-22 at 7 27 28 PM" src="https://user-images.githubusercontent.com/103155832/169731993-1ea496b2-67ba-4aa9-9de8-1663c48b1fd1.png">

Showing the code in MarkdownParseTest.java for how I turned it into a test

<img width="497" alt="Screen Shot 2022-05-22 at 7 31 19 PM" src="https://user-images.githubusercontent.com/103155832/169732344-9937b154-c500-409c-aa9f-091e6c85d0a6.png">

the corresponding output when running the tests, my implementation failed. The image below shows the JUnitAssertion that was produced as a result of my implementation failing.

<img width="946" alt="Screen Shot 2022-05-22 at 7 31 53 PM" src="https://user-images.githubusercontent.com/103155832/169732394-f648eb83-ec69-4c32-8edd-86807fd6cb74.png">

For the implementation you reviewed in Week7

<img width="943" alt="Screen Shot 2022-05-22 at 7 33 18 PM" src="https://user-images.githubusercontent.com/103155832/169732504-ecf7fa77-e688-47d6-9b2c-74e9392dda23.png">

both implementations failed this test case.

**Snippet 3**

<img width="662" alt="Screen Shot 2022-05-22 at 7 35 32 PM" src="https://user-images.githubusercontent.com/103155832/169732693-e561a1c9-6802-47fa-ab17-26959a91b60e.png">

The sceentshot of Common Mark demo is below:

<img width="1214" alt="Screen Shot 2022-05-22 at 7 37 52 PM" src="https://user-images.githubusercontent.com/103155832/169732904-a06cc130-8bd9-4411-81f8-241fe47bc3f8.png">

Showing the code in MarkdownParseTest.java for how I turned it into a test

<img width="741" alt="Screen Shot 2022-05-22 at 7 40 46 PM" src="https://user-images.githubusercontent.com/103155832/169733148-0b5a946f-2c13-4885-b6e0-0df176496694.png">

the corresponding output when running the tests, my implementation failed. The image below shows the JUnitAssertion that was produced as a result of my implementation failing.

<img width="890" alt="Screen Shot 2022-05-22 at 7 41 37 PM" src="https://user-images.githubusercontent.com/103155832/169733226-c4ebdf3b-9ad8-4401-a875-b02d27f3e1a8.png">

For the implementation you reviewed in Week7

<img width="828" alt="Screen Shot 2022-05-22 at 7 42 03 PM" src="https://user-images.githubusercontent.com/103155832/169733271-1913592e-7976-4da2-aaeb-fa497b2bbb2f.png">

both implementations failed this test case.

**Answer the following questions with 2-3 sentences each:**

***Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.***

I think I can add some code which make the program ignore the backticks which is less than 10 lines.

***Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.***

I think fix snippet 2 problems I need to add more than 10 lines code to fix it, because the markdown snippet problems is nested parantheses within the link and stop at the first instance of a closed paranthesis.

***Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.***

I think fix snippet 3 problems I need to add more than 10 lines code to fix it for the newlines in brackets and paraentheses, I need to make sure which line is produces a link and not produces a link.
