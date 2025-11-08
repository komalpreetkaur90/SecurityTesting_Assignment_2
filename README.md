Assignment 2 

1. Do these results match what you found in your previous peer review? Why or why not?
Yes, they mostly match. The peer review found issues like hardcoded passwords, SQL injection, insecure HTTP, and unsafe input. The CodeQL scan flagged similar problems. Some small differences exist because machines and humans sometimes notice different things.

2. Do you think they caught all the vulnerabilities present in the code? Why or why not?
No, not all of them. Scanners are good at finding common problems, but they can miss things that need human understanding, like code logic errors or input validation done in the wrong order. That’s why we still needed to manually check and fix the code.

3. Why is using multiple code scanners better than using one?
Using more than one scanner helps catch more problems. Different scanners are good at finding different types of issues, so combining them makes it less likely that a vulnerability will be missed.

Assignment 3

How did the AppScan CodeSweep scan performance compare to the previous code scanners you used? Be specific.
i.e. CodeQL and Bandit
AppScan CodeSweep was faster and easier to use than CodeQL and Bandit. It scans my code automatically in VS Code and shows problems right away, which makes fixing them quick. CodeQL gives more detailed results but takes longer and can be confusing at first. Bandit is fast for Python but only works for that language. Overall, CodeSweep is easy to use, works with multiple languages, and fits nicely into both VS Code and GitHub Actions.