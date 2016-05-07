# 1. Installation

In this part, we are going to install Elixir on our machine. The setup will be different depending of your Operation System (Max, Windows or a flavour of Linux). I will provide detailed help for Mac, Windows and Ubuntu. If you have a different Linux distribution, feel free to contact the community to help you or to search online.

For each OS, we will need to install Erlang first, then Elixir on top of it.

The main address will be http://elixir-lang.org/install.html

You will install Elixir 1.2.3. Any previous release will not work !
## Quick and Dirty

### Windows

On the http://elixir-lang.org/install.html#windows we can download the installer. Then launch it and follow the instructions. You can now go launch a command line (Appendix A) and by typing the following instructions, you should see that result.

    Microsoft Windows [version 10.0.10586]
    (c) 2015 Microsoft Corporation. Tous droits réservés.
    >iex.bat
    Eshell V7.2.1  (abort with ^G)
    Interactive Elixir (1.2.3) - press Ctrl+C to exit (type h() ENTER for help)
    iex(1)>

### Ubuntu
On Ubuntu you will want to go to http://elixir-lang.org/install.html#unix-and-unix-like and use the Ubuntu part. In your command line, you will type the following instructions.

    //to update



### Mac
To be written

##Text editor
    Which one? Notepad++ is an easy simple one. but no elixir on them. Maybe all on Sublime ?

##In details
So what happened ? What is that Elixir and what is that Erlang ?

Erlang is a language that go back to the middle of the 1980s. It was written to solve a couple of really specific problems. It is based around a Virtual Machine. It is a specific program that run on your computer and understand the Erlang code you give him. It follows that code to make things happen on your computer.

_insert a diagram of OS->VM->code_

Why use a Virtual Machine and not directly give the code to the computer? Because different computer works differently. By adding a layer between our code and the computer, we can make a code that will work everywhere. Instead of adapting our code to the specificities of each computers, we can write code for the Virtual Machine. Then we only have to adapt the Virtual Machine to different computers.

The Virtual Machine of the Erlang coding language is known as the BEAM.

So why do we have to install it? We are learning Elixir, not Erlang ! Well Erlang is solving a lot of problems and is an interesting language, but it is a language from the 1980s. It is not really easy to use and some of the choice that were made are not really modern. But the philosophy behind it is really powerful.
So José Valim, a brazilian programmer decided to create Elixir. A language that run on the BEAM just like an Erlang program, but that would have all the nice and powerful things that we invented between the creation of Erlang and now.

So how does it works ? We write Elixir code. Then the Elixir program we installed will translate it into a code the BEAM will understand. And then the BEAM will run it. That is why we installed Erlang. Elixir need the BEAM to work.
