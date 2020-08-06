## Develop the interaction
Now you're going to make your digital card do something to make it interactive. 

You need to break up your project up into parts so you can develop the parts one at a time. In computing, this process is called decomposition.

--- task ---
What behaviour will your first sprite have? You need to think about **what** you want your sprite to do and **when** it will do it. 

Examples:
"When you click on the balloon it will pop and disappear."
"The flower will spin 10 times when you click on it."
"When you click on the Stage, the doughnut will stamp where you clicked."
"When the rocket touches the star, the star will spin and make a sound."
"When you click on the Dance button, all the person sprites will dance."

You might have lots of ideas. Just choose one of them to start with.

--- /task ---

--- task ---
Describe what the sprite will do in words. Tell a friend or someone in your family. 

--- /task ---

--- task ---
Add the blocks that you need to decide **when** your sprite will do something. 

It could be one of these blocks:

```blocks3
when green flag clicked

when this sprite clicked

when stage clicked

```

And you may need a `forever`{:class="block3control"} loop that does something when a condition is true.
```blocks3
when green flag clicked
forever 
if <condition>

end
```

If more than one sprite or the stage is involved then you may need to use event blocks:

```blocks3
when I receive :: events

```
OR

```blocks3
broadcast :: events
```

--- /task ---

--- task ---
Add the blocks to make your sprite do **what** you want it to do. Go to blocks you now know or use a How to... to help you. Or you can revist step 3: [Investigate digital cards](https://learning-admin.raspberrypi.org/en/projects/digital-card/2) and See inside.

--- /task ---

**Tip:** Have a go. It won’t break. Some of the best ideas come from playing. 

**Tip:** You will come across good ideas by accident.

--- task ---
Test your new code. Is it running as you imagined? 

**Tip:** You can drag some of your blocks away and add them back one at a time to help you understand what your code is doing.

**Tip:** If your code uses a `when I receive [event]` block you can click on the `broadcast [event]` block to test it. 

**Tip:** If your code runs when it detects another sprite touching then you can just drag the other sprite on the stage to test it. 

--- /task ---

--- task ---
Show someone else you project and tell them what you’ve done and what your plans  are. Ask for their honest feedback. You might want to improve your project.
--- /task ---

**Tip:** It’s ok to change your mind. Be clear about what you’re aiming for.

--- task ---
What’s your next step? It might be to develop the sprites’s behaviour. It might be to add code to another sprite. 

If you have used a `when I receive [event]` block then you may want to add `broadcast [event]` block to another sprite (or the other way around).

Are you stuck for ideas? Take a look at the Scratch Studio and don’t forget to look at the See inside.

If you have finished or don't have much time left then carry on to the next step to share your card.
--- /task ---

