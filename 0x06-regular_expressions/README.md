Regular expression(REGEX)

Regular Expression()
A regular expression, commonly called a “regexp”, is a sequence of characters that define a search pattern.  It is mainly for use in pattern matching with strings, or string matching (i.e. it operates like a “find and replace” command). While it is a very powerful tool, it is also very dangerous because of its complexity.



Some people, when confronted with a problem, think “I know, I’ll use regular expressions.”   Now they have two problems. (super classic joke in the industry)(http://regex.info/blog/2006-09-15/247)

One thing you have to be careful with is that different languages use different regexp engines. That means that a regexp in Python, for example, will be interpreted differently in Javascript:

Regular expressions are everywhere and software engineers, no matter their positions, will have to use them during their careers. System administrators and DevOps are the ones using them the most because they are very handy for log parsing.

Read about regexp:

http://www.regular-expressions.info/(https://www.regular-expressions.info/)
http://www.w3schools.com/jsref/jsref_obj_regexp.asp Play with regexp (or compose them):(https://www.w3schools.com/jsref/jsref_obj_regexp.asp)

Ruby: http://rubular.com/(https://rubular.com/)

PHP/Javascript/Python: https://regex101.com/(https://regex101.com/)

Regular expressions - basics(https://www.slideshare.net/neha_jain/introducing-regular-expressions)
Regular Expressions - Advanced(https://www.slideshare.net/neha_jain/advanced-regular-expressions-80296518)
Rubular is your best friend(https://rubular.com/)
Use a regular expression against a problem: now you have 2 problems(https://blog.codinghorror.com/regular-expressions-now-you-have-two-problems/)
Learn Regular Expressions with simple, interactive exercises(https://regexone.com/)

0. Requirements:

The regular expression must match School
Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method

1. Requirements:

Find the regular expression that will match the above cases
Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method

2. Requirements:

Find the regular expression that will match the above cases
Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method

3. Requirements:

Find the regular expression that will match the above cases
Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method

4. Requirements:

Find the regular expression that will match the above cases
Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method
Your regex should not contain square brackets

5. Requirements:

The regular expression must be exactly matching a string that starts with h ends with n and can have any single character in between
Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method
Example:

6. This task is brought to you by a professional advisor Neha Jain, Senior Software Engineer at LinkedIn.

Requirement:

The regular expression must match a 10 digit phone number

7. Requirement:

The regular expression must be only matching: capital letters

8. This exercise was prepared for you by Guillaume Plessis, VP of Infrastructure at TextMe. It is something he uses daily. You can thank Guillaume for his project on Twitter.

For this task, you’ll be taking over Guillaume’s responsibilities: one afternoon, a TextMe VoIP Engineer comes to you and explains she wants to run some statistics on the TextMe app text messages transactions.

Requirements:

Your script should output: [SENDER],[RECEIVER],[FLAGS]
The sender phone number or name (including country code if present)
The receiver phone number or name (including country code if present)
The flags that were used
You can find a [log file here].()
