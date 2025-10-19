# 2. All in one

Every program needs a starting point, from where all the logic is derived. As for a lot of classic programming languages are calling this point *main* and have only one entry point, Scratch is working somehow different. It can have a lot of different entry points, which can be compared to threads in classic programming. Threads are logical sequences, which run asynchronous. This means they can run one after the other, but they can also run in parallel. They are independently running code sequences, but they can interact and also influence each other.

Therefore programming with multiple threads is common, but also difficult and error prone. So for this first program we will try to have only one thread handling all the logic of our code.

## 2.1 Greatings

Perhaps you already had a look at all the possible interactions we can do with some sprite. If so you have most likely already seen, how to give some output to the user of your program. This is an important part of interacting with the user of your program. This way you can provide information, what the program currently is doing or give some solution to a problem the user what you to solve. To start the program we want to use for now the green flag.

Let's first start with just giving some nice greating to the user to let him know the program has started.

## 2.2 Who are you

For now we have given some general greating to the user, but we do not know anything about the user for now. What if we wanted to get the name of the person we are interactiv with? Could we perhaps even have some specific greating including this information?

Try to find some way to ask for the users name and get some input. Try also to use this input.

## 2.3 Memories

If you managed to get the name of your user and also use it in some context, you did already saved this information somehow. If you had a look at the example, you will see that we used some question and answer block, which saved the answer automatically in some element called *answer*. This is nothing else but a variable holding this information. Variables are used to save some information. The content can come from some user input, but can also be generated internally to keep track of some calculations or results we want to use in some other place in the code. Perhaps we want to output it to the screen or we want to do some additional calculation on it. Perhaps you also want to combine some information to something new. For this reason we can use operators on variables. Different languages have different operators. Have a look at what you can find in Scratch and try to use them to combine your information to something useful.

Alter the code, so that we are asking for the users name and their age and combine these information to some meaningfull output.

## 2.4 All about motion

Now we already know how to interact with the user by giving output and receiving input. We are also able to keep information stored in variables. Next we want to think about how we can make the program more visual entertaining to the user. For this reason we want to move the sprite on the screen.

Try to implement some movement logic to our sprite.

## 2.5 All over again

Now we can move the sprite. What happend, when you started the program. What did you need to do, to move the sprite several times?

As you can see from this question, it is nice to let the sprite move from one point to another just by pressing the start flag. But it is also not very convinient to rerun the program every time you want to repeat this behavior. The idea of programs is, that they can do specific sequences over and over again, with only minimal or even no external input. So it would be nice to let the sprite move on its own, without us starting the program each time.

To repeat a task multiple time, there are specific control sequences in all programming languages called loops. They will repeat all instructions inside until some condition is met. This condition can be some external trigger or some internal state we want to reach. Sometime we want to run a loop forever until the program is closed. This is mostly used in the main program threads, so that they can react to internal or external inputs as long as the program is running.

Try to add a loop to your program. Is this already some useful implementation?

## 2.6 Only when...

What do you think, are we done yet? Is it useful, that the sprite is moving to some edge and stucking there? Most likely this is not what we want. So what can we do about it?

The answer is, we need to add some more logic to the program. Perhaps we want to move the sprite only up to a specific point. Or we want to move it only if some input is given. Perhaps we want to let the sprite move around the screen randomly. For all these cases we need some control element, which is called condition. Think about what you perhaps would like to make the sprite represent. Should it in some way interact with the user? Will it react on some boundaries on the screen?

Try to make your program more interactive in using some conditions.
