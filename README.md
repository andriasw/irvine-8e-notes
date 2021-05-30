# irvine-8e-notes
Reading, learning and coding based on Irvine's assembly language book (8e, Chinese Reprint: http://www.hzcourse.com/web/teachRes/detail/5181/208)

I am in China, so I bought the Chinese reprint. If you are in China, please consider buying the reprint instead of using (or using only) pirated digital copies, one of the reasons being Pearson has stopped releasing PDFs with print layout.

No pirated copies of the book will be uploaded here for copyight reasons.

I am actually new to any kind of programming at all (tried C, Java, Python here and there but am really at an elementary level), so if any technical or non-technical issues are found in this project, please do not hesitate and point it out using comments or anything git-related (no, I don't know git stuff either).

## Chapter 03

Sec. 3.2.2:

You should do two things before doing the project, or errors and unexpected things happen:

1. Unzip 20MB+ `Irvine.zip` available at [author's website](http://asmirvine.com/) and put it in C root directory, or [a dependency (or something else) error](https://www.chegg.com/homework-help/questions-and-answers/m-trying-set-vs-2019-work-masm-getting-error-cannot-open-file--ideas-masm-checked-build-de-q72206451) occurs when building the project:

![image](https://user-images.githubusercontent.com/5285681/120089535-03b85300-c12e-11eb-85b8-b9fa916a31a7.png)

2. For those who are new to Visual Studio or any serious programming at all (like me), you should swap the sequence of environment variables for dotnet, and make sure the `Program Files (x86)\` one is above the `Program Files` one, otherwise the project would fail to open:

![image](https://user-images.githubusercontent.com/5285681/120089799-2186b780-c130-11eb-8711-7dd09e83a9b6.png)

If you are using Windows 10, just push `Start` button and type enviornmental, the first settings option appeared in the search result should be it:

![image](https://user-images.githubusercontent.com/5285681/120089832-732f4200-c130-11eb-9118-5b4331fc2426.png)

If you are using older Windows versions, just Google `environment variables`.

Same thing happened when I tried [head-first-csharp / fourth-edition](https://github.com/head-first-csharp/fourth-edition). I did the swap, and the debugger appeared, so that I could proceed with building my first GUI app in C#.
