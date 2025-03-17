#How did the AppScan CodeSweep scan performance compare to the previous code scanners you used? Be specific.
i.e. CodeQL and Bandit

After using AppScan code sceep , the main difference I can see it contains when using CodeQL & Bandit is:

for Bandit when it scans for a pull request it identifys the issues and makes it more noticable for the user by showing what has failed, but for CodeSweep when identifying the potential errors/vulnerabilities it passes it and makes 
it green, having it where you can still push the pull request. 

for CodeQL the main difference i can see when using the two is how simple the setup is for CodeQL, CodeQL is setup within Github's settings but for AppScan you have to go into github actions instead of settings to manually set it up and 
add it as an extension on VS, and after reviewing each of the code scanners i've realized that CodeQL did not really see any errors and passed it off compared to both the scanners. 

