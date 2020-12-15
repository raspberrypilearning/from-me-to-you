## Make
Now you're going to make your digital card project. 

Start small and add more to your project if you have time. You will need to decide on what to do first and what to save for later. You might want to add code to one sprite before you paint a costume for another. 

As you work your way through your digital project, remind yourself how to do things in Scratch with the [Getting started with Scratch](https://learning-admin.raspberrypi.org/en/projects/getting-started-scratch) guide. 

--- task ---
If you haven't already chosen a backdrop and added a sprite then start now. You can always add more later including using the Paint editor to make your own. 
--- /task ---

--- task ---

Think about **what** you want to say in your message in your digitial card.

--- /task ---

--- task ---

Now think about how the user will interact with your project.

For example:
+ "When the user clicks on the green flag, a sprite moves"

+ "When the user clicks on the sprite, the sprite gets brighter"

Write your initial idea down or tell a friend or family member. It's easier to make a project when you can explain what your idea is.

You might have lots of other ideas. Start with the initial idea first.

--- /task ---

You now need to think about **how** you are going to say your message. You can either add your message as **a sprite or a series of sprites** or **sound**.

--- task ---
You can choose sprites from the Scratch library by searching for **letters** and **numbers**.

You might find it useful to use the **Text** tool in the Paint editor to write a short message: 

--- collapse ---
---
title: Using the Text tool in the Paint editor
---

Select the first colour you want for your text.

![Show Fill colour](images/from-me-fill-colour.png){:width="250px"}

Select the **Text** tool:

![Show Text tool](images/from-me-text-tool.png){:width="250px"}

Click on the Paint editor and start typing your message.

Select the font dropdown to change the text font:
![Show Font](images/from-me-text-font.png){:width="250px"}

Click on the **Arrow** tool and select your message. Drag the corner handles to resize your message.
![Show Arrow tool and resize handles](images/from-me-arrow-resize.png){:width="250px"}

Centre

--- /collapse ---

You can also use any other skill and tool from the Paint editor which you have learned:

+ [Paint editor](https://learning-admin.raspberrypi.org/en/projects/getting-started-scratch/6){:target="scratch_guide"}

--- /task ---

--- task ---
Do you need to add sounds to a sprite or to the Stage?

You can record a spoken message if you like:

--- collapse ---
---
title: Recording a sound
---

--- /collapse ---

--- /task ---

--- task ---
Add a block for **when** your sprite should do something.

--- collapse ---
---
title: Starting code with hat blocks
---

```blocks3
when green flag clicked
when this sprite clicked
```

These blocks have a different shape, they are sometimes called **Hat blocks** and they start code running when a particular event happens.
You could also use a `wait`{:class=“block3control”} block to add a delay before running other blocks.
And you may need a `forever`{:class=“block3control”} loop that keeps running blocks.

```blocks3
when green flag clicked
forever :: control
```
--- /collapse ---

--- /task ---

--- task ---

Add the blocks you need to make your sprite do **what** you want it to do.

For example, in the New Year project, the small firework has the code:

```blocks3
when flag clicked
set size to (70)%
go to [back v] layer
set volume to (40)%
point in direction (-35)
```

and, 

```blocks3
when this sprite clicked
start sound (Rip v)
forever
move (8) steps
if on edge, bounce
```

You can use any of the skills you have learnt:

+ [Useful code](https://learning-admin.raspberrypi.org/en/projects/getting-started-scratch/4){:target="scratch_guide"}
+ [Block reference](https://learning-admin.raspberrypi.org/en/projects/getting-started-scratch/5){:target="scratch_guide"}

--- /task ---

**Tip:** Have a go. Your computer won’t break!

**Tip:** Some of the best ideas come from playing. You will come across good ideas by accident.

--- task ---
Test your new code. Is it running as you imagined? Here are some useful debugging tips:

--- collapse ---
---

title: Debugging tools

---

+ You can click on block in the Menu and run it. You could try some `graphic effects`{:class="block3looks"} blocks to see what you like and then use `clear graphic effects`{:class="block3looks"} to make your sprite normal again.

+ You can drag some of your blocks away from the script but keep them within the Code area and add them back one at a time to help you understand what your code is doing.

--- /collapse ---

--- /task ---

--- task ---

Show someone else your project and tell them what you’ve done and what your plans are. Ask for their honest feedback. You might want to improve your project based on their feedback.

--- /task ---

**Tip:** It’s ok to change your mind but always be clear about what you’re aiming for.

--- task ---
What’s your next step? It might be to add more code to your sprite. It might be to add code to another sprite. It might be to record a sound or paint a new costume. 

Are you stuck for ideas? Don’t forget to look at step 3: [Investigate](https://learning-admin.raspberrypi.org/en/projects/digital-card/2){:target=”_blank”} and `See inside`{:class="block3motion"} some projects.

If you have finished or don't have much time left then carry on to the next step to share your digital card.

--- /task ---

--- save ---
