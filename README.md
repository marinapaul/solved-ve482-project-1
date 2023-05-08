Download Link: https://assignmentchef.com/product/solved-ve482-project-1
<br>
<h1>1         A tough life…</h1>

As you are comfortably sleeping in your soft bed, your alarm clock loudly rings and wakes you up. Already 11 AM… It would be good to sleep a bit longer but you already hear your mum stepping in the room and widely opening the curtains. As you are blinded by the sudden burst of light you start grumbling, but she is not even paying attention to you and just says: “I told you to sleep instead of playing video games all night long! You’ve graduated two months ago and you haven’t found job yet!” The head under your pillow to protect yourself from the light you simply ignore her and start smiling as you think of last year at the same period when you had to wake up early to attend ve477 lectures. But luckily now you are home and you can sleep, so why not enjoying it? As you start to fall asleep again, she admonishes you “Wake up lazy kid! Time for you to to find a job!”

“But mum, I have already sent two CVs last week? What else do you want me to do?” you try to argue.

“What do I want you to do? Hum…I want you to start doing something with your life! If you don’t want to find a job then you’ll work here!” she orders you.

As she carries on you simply look at her disconcerted. “Yes, I found some exercises for you: you’re going to implement a shell,” and she punctuates with an ironic smile.

Totally speechless, you look at her wondering how come she knows what a shell is.

As she approaches from your bed she hands in a couple of pages to you just saying “Lets work begin!

And be sure that I’ll check on your regularly…”

While you regain your composure you manage to articulate “I’m already very busy playing video games!”

To what she firmly replies “Not anymore you’ll be busy implementing a shell!” Then she quits the room, leaving you puzzled and bitter. Why has not Lemonion call you already for an interview, you had the perfect profile? Now you are here lying in your bed with a couple of pages entitled <em>The mumsh shell</em>.

<h1>2         The mumsh shell</h1>

The main task of a shell is to wait for some user input, parse it and execute a command requested by the user. It should also provide support for input/output redirection and pipelining from a program into another one.

A shell simply consists of a loop that parses the user input. When waiting the shell displays a prompt, here we want our shell to display “mumsh $ ”.

When a command is input by the user it should be launched in a new process and the shell should block, waiting for the command to end.

A command line is composed of a command followed by some arguments. Arguments are space separated. The shell should exit when the user inputs exit. In case of error, such as when a command that does not exists is input, the shell should output an error on the standard error output (e.g. Error: no such file or directory).

The shell can be tested by comparing its behaviour to the result of the same commands in the regular Linux shell (e.g. sh, bash, zsh). Note that those commands are only for testing purpose, therefore they are far from being optimal and do not encompass all the features that need to be implemented.

The mumsh shell is expected to be running in both Linux and Minix 3.

<em>Hints:</em>

<ul>

 <li>Useful system calls: fork(), execvp(), wait/waitpid(), dup2/dup(), pipe() and close().</li>

 <li>A command line is not expected to be longer than 1024 characters.</li>

 <li>The use of the command system or of lex and yacc is prohibited.</li>

</ul>