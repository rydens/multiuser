# multiuser
Everything that I find useful for monitoring my multi-user
server, even if they are just my friends.

I wrote everything, so that means that there are probably
numerous ways to do something better.

Also, there are numerous files that are just there for testing 
concepts, like `args` or `usertest`, and once I'm finished, they will disappear.

Anyways, on to the contents!



## `announce`
This magical thing is a program... THAT FREAKIN' WRITES A PROGRAM.

*Whoo Hoo*

It writes an `announcement` program, and all it does right now is make a file that prints the message, then asks if you want it deleted. It only works for the person that runs it as of now.

*Please note that the list of users is imported from another source.
Make your own if you actually use this.*


## `args`
Me learning how to use arguments properly.


## `argstest`
A program to test my `args` program.


## `colors.py`
This is just a python library of colors, to be used for solarized
terminals. It just makes things look fancy.


## `del`
A very short program to easily delete the `exannounce` file from when
I was testing.


## `hconfigupdate`
Something like `multiupdate`; it needs root, and logs on to each user account, from a seperate file, and deletes their `~/repos/home-config` then `git clone`s a new one.


## `multiupdate`
`multiupdate` is a simple program that goes out to where these programs are stored so that anyone can access them, `/usr/bin/multiuser`, and deletes all the contents there.

Then, it copies all the stuff from this repository back up there.

Why? Because this allows me to do every bit of development from here, then send it back so everyone can use it.


## `oldpush` *The old one*
`oldpush` simply pushes files from the directory you are in
to a certain target directory.

I made this because my friend is learning web development,
and I gave him an account on my server so he could actually
make some websites. This just makes things easier for everyone.


## `pathtest`
Me testing using `os.path.exists()`


## `push` *The new version!*
Does the same thing as `oldpush`, above, just in a much shorter way because I learned arguments!
Still in progress, I think


## `usertest`
My test file for importing a list of usernames from another location; if you want to do this, modify your PYTHONPATH a bit.




### There will definitely be more, it's just in the works.
*Thanks,*
> *rydens*
