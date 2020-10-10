# Don't Be too Sophisticated

How deep is your knowledge of your programming language of choice? Are you a real expert? Do you know every strange construct that the compiler won't reject? Well, maybe you should keep it to yourself.

Most of the time a programmer does not write code just for himself. It's very likely that he creates it within a project team or shares it in some other way. The point is that there are other people who will have to deal with the code. And since other people will deal with the code, some programmers want to make it just brilliant. The code will be formatted according to the chosen style guide and I'm sure that it will be well commented or documented. And it will use sophisticated constructs to solve the underlying problems in the most elegant way. And that's sometimes exactly where the problems start.

If you look at development teams you will notice that most of their members are average-level programmers. They do a good job with the mainstream features of their programming languages, but they will see sophisticated code as pure magic. They can see that the code is working, but they don't understand why. This leads to one problem we know all about: Although well formatted and commented, the code is still hard to maintain. You might get into trouble if there is a need for enhancement or to fix a bug when the magician is not within reach. There might even be a second problem: People tend to reject what they do not understand. They might refuse to use this brilliant solution, which makes it a little less brilliant after all. They might even blame the sophisticated solution if there are some strange problems. Thus, before creating a highly sophisticated solution, you should take a step back and ask yourself whether this kind of solution is really needed or not. If so, hide the details and publish a simple API.

So what is the thing the programmer should know? Try to speak the same language as the rest of your team. Try to avoid overly sophisticated constructs and keep your solutions comprehensible to all. This does not mean that your team should always stay on an average programming level without improvements. Just don't improve the level by applying magic: Take your team with you. Give your knowledge to your team members when appropriate and do it slowly, step by step.

By [Ralph Winzinger](http://programmer.97things.oreilly.com/wiki/index.php/Ralph_Winzinger)