## Develop the interaction
Now you're going to make your digital card do something to make it interactive. 

You need to break up your project up into parts so you can develop each part, one at a time. In computing, this process is called decomposition.

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
Describe what the sprite will do in words. Tell a friend or family member.

--- /task ---

--- task ---
Add a backdrop that fits with your theme. 
--- /task ---

--- task ---
Add one or more sprites that you think you will use in your card. Don't worry you can always change, delete or add more sprites later as you develop your ideas. 
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
forever :: control
if  <condition ::  operators> :: control 
```

If more than one sprite or the stage is involved in the interaction then you may need to use event block:

```blocks3
broadcast :: events
```
and:

```blocks3
when I receive :: events

```
--- /task ---

--- task ---
Add the blocks to make your sprite do **what** you want it to do. Go to blocks you now know or use a How to... to help you. Or you can revist step 3: [Investigate digital cards](https://learning-admin.raspberrypi.org/en/projects/digital-card/2) to See inside projects.

--- /task ---

**Tip:** Have a go. Your computer won’t break!

**Tip:** Some of the best ideas come from playing. You will come across good ideas by accident.

--- task ---
Test your new code. Is it running as you imagined? 

**Tip:** You can drag some of your blocks away from the script but keep them within the Code area and add them back one at a time to help you understand what your code is doing.

**Tip:** If your code runs when it detects another sprite touching it then you can just drag the other sprite on the stage to test it. 

**Tip:** If your code uses a `when I receive`{:class="block3event"} block you can click on the `broadcast`{:class="block3event"} block to test it. 

**Add: scratch-testingcode-dragblock/dragsprite/broadcast**

--- /task ---

--- task ---
Show someone else your project and tell them what you’ve done and what your plans are. Ask for their honest feedback. You might want to improve your project based on their feedback.
--- /task ---

**Tip:** It’s ok to change your mind but always be clear about what you’re aiming for.

--- task ---
What’s your next step? It might be to develop the sprites’s behaviour. It might be to add code to another sprite. 

If you have used a `when I receive`{:class="block3event"} block then you may want to add `broadcast`{:class="block3event"}  block to another sprite (or the other way around).

Are you stuck for ideas? Take a look at the Scratch Studio and don’t forget to look at step 3: [Investigate digital cards](https://learning-admin.raspberrypi.org/en/projects/digital-card/2) to See inside.

If you have finished or don't have much time left then carry on to the next step to share your card.
--- /task ---
--- save ---
