4. Log into ieng6
![](Step4.png)
Keys Pressed:
```
$ ssh cs15lsp23ga@ieng6.ucsd.edu
```

5. Clone your fork of the repository from your Github account
![](Step5.png)
Keys Pressed:
```
$ git clone https://github.com/ucsd-cse15l-s23/lab7
```

6. Run the tests, demonstrating that they fail
![](Step6.png)
Keys Pressed:
```
$ bash test.sh
```

7. Edit the code file to fix the failing test
![](Step7.png)
Keys Pressed:
```
vim ListExamples.java
```
```
/lo → <Enter> → <down> → <left> → <left> → <left> → <left> → c → <delete> → type 2 → <Esc> → :wq
```

8. Run the tests, demonstrating that they now succeed
![](Step8.png)
Keys Pressed:
```
$ bash test.sh
```

9. Commit and push the resulting change to your Github account (you can pick any commit message!)
![](Step9.png)
Keys Pressed:
```
$ git add .
$ git commit -m "Added new feature"
$ git push origin main
```
