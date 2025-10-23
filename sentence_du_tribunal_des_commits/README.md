# README best practices #

First of, I want to preface this by saying I've been unfairly punished because of the wrong doing of others.
BUT, since I'm not a little whiny Bitch, I'm gonna do it anyways.

We've been asked to write a README on Commits best practices, so, here we go:

Why and how should we write clear commits ?

1: WHY?

Commits are the timeline of your project.
They’re how you, your teammates, and future you (who’s probably more tired and less patient) figure out what the hell happened and why.

Bad commits are chaos.
Good commits are documentation, accountability, and context all rolled into one neat line.
They make it easier to:

Debug issues without wanting to cry

Review code faster

Understand the evolution of a feature

Avoid repeating the same mistakes

Basically: clean commits save everyone time and brain cells.


2. HOW?

Alright, theory time’s over. Let’s talk about how to actually write a decent commit message.

→ Step 1: Think before committing

Ask yourself:

“If someone who isn’t me reads this, will they know what changed and why?”

If the answer’s no, your message sucks. Try again.

→ Step 2: Follow a structure

A good commit usually looks like this:

<type>: <short summary>

Example:

fix: handle null input in authentication


# Commit message “types” (for the organized ones) #

You’ll often see people prefix commits with a “type”, which helps a lot when your project grows.

Type	    Meaning
feat	    new feature
fix	        bug fix
docs	    documentation only
style	    formatting, indentation, missing semicolons, etc.
refactor	code improvement without changing behavior
test	    adding or fixing tests
chore	    maintenance
