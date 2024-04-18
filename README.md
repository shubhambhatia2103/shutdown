# Python Script to Shutdown Computer
As we know, Python is a popular scripting language because of its versatile features. In this article, we will write a Python script to shutdown a computer.
To shut down the computer/PC/laptop by using a Python script, you have to use the `os.system()` function with the code
```bash
shutdown /s /t 1
```
## Note
```bash
For this to work, you have to import os library in the ide. If you don’t have it, then ‘pip install os‘ through the Command Prompt.
Causion: Please ensure that you save and close all the program before running this code on the IDLE, as the below program will immediately shut down your computer.
```
### Below is the Python implementation –
```bash
import os 

shutdown = input("Do you wish to shutdown your computer ? (yes / no): ") 

if shutdown == 'no': 
	exit() 
else: 
	os.system("shutdown /s /t 1") 

```
## Contact

[<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/linkedin.png" title="LinkedIn">](https://www.linkedin.com/in/shubhambhatia2103/) [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/github.png" title="Github">](https://github.com/shubhambhatia2103) [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/instagram-new.png" title="Instagram">](https://instagram.com/6eingshubham) [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/twitter-squared.png" title="Twitter">](https://twitter.com/whoodattboyy)
