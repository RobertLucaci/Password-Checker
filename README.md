# Password-Checker
What you could find here is a password checker, but not just any silly, dumb password checker.
This is, legitimately, going to be the most secure way for you to check if your password has ever been hacked just typing it in terminal.
This project uses Troy Hunt's **Have I Been Pwned** API to get the passwords that have been leaked in the past using only the first five characters of the SHA1 generated password.

# How hackers work?
Well, passwords get leaked all the time. We’ve heard about data breaches, right? Facebook has been hacked with data breaches, LinkedIn, Yahoo, all this big companies sometimes get their data bases leaked and essentially what happens is that our usernames and passwords get leaked to the public.
Hackers compile this lists of leaked usernames and passwords and try to log into different services  looping this data using something called dictionary attacks or brute force.
So there are databases of all emails and passwords that have ever been leaked through history.

# How can you run it?
You should copy the **main.py** file into your local computer.
Open it with your Text Editor or IDE.
The only thing you have to do know to find out if your password has been pawned or hacked is to write in your terminal: 

**python3 main.py “your password”**
