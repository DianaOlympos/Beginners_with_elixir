# 3. Printing and displaying

Open your text editor. Welcome in your main tool to write code. This is where you will work. Create a new file named `ex1.exs`. Open it with your text editor. Here is where you are going to type your code in the next lessons. Then you will save it and go to your command line. (Do Appendix A if you don't understand what i mean exactly) and type `elixir ex1.exs`. You will then see things happens in your command line and you will be able to continue the exercise.
And that is all. Here it is. Let move to do our first code !

##Quick and Dirty

Open your file named `ex1.exs` in your text editor and type the following line in it.

    IO.puts "Hello World!"
    IO.puts "Hello Again"
    IO.puts "I like typing this."
    IO.puts "This is fun."

Then save your file and go to your command line. Then **run** the file by typing in it `elixir ex1.exs`.

Here is what you should see in the command line. If it is not that, then you made a mistake somewhere. Check that you typed exactly the same things.


>> insert here the results in powershell and terminal ? Or just use generic terminal ?

##What Happened?

So we wrote in a file, we typed an incantation on the command line and the computer talked to us. Let's begin with the file.

File which name end with a `.exs` are what we call **Elixir script**. They are simple program that are read by the computer and tell him how to act. Latter we may move to more complex things, but for now your code will be in a single file for each lessons. So they will be script written in a `.exs` file.
Then we typed something in the command line. By typing `elixir ex1.exs` we told the command line to search elixir on our computer, give it the script `ex1.exs` and let elixir read and act following the code we typed. That is how we are going to work in all the following lessons.

So what did our code did? Well let's look at it. We wrote IO.puts. That is telling to the computer "Write the things that follow on the console". So it took what was following and printed it. Yeah you made a computer print words !

##Exercises

1. Try to make your script write another line.
2. Try to put a `#` at the beginning of a line and run your script. What is happening ? Try to find out. Feel free to search the internet.
