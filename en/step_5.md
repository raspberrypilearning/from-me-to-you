## Make 🧱 and test 🔄

Now, it's time to make your digital card. Start small, and add more to your project if you have time. 

**Tip:** Remember to test your project each time you add something. It is much easier to find and fix bugs before you make more changes.

![A strip of example projects including cards for world hello day, new year, world environment day, a thank you card and a happy birthday card..](images/showcase_static.png)

Some useful skills you could use for your card:  
+ Add code to sprites and a backdrop
+ Customise sprites in the Paint editor
+ Add `graphic effects`{:class="block3looks"}, `motion`{:class="block3motion"}, and `sound`{:class="block3sound"} to a sprite
+ Use the `forever`{:class="block3control"} and `repeat`{:class="block3control"} loop blocks
+ Use the `next costume`{:class="block3looks"} and `wait`{:class="block3control"} blocks to animate a sprite
+ Use `layers`{:class="block3looks"} blocks to move sprites in front of or behind other sprites
+ Use the `text to speech` and `translate` extensions 

--- task ---

Add the backdrop and new sprites you need for this page. 

![Choose a sprite and choose a backdrop icons.](images/sprite-and-backdrop.png)

--- /task ---

### For each sprite 🐈 🐢 🎈

--- task ---

You will need to add code to each character and object sprite in your book. Consider whether they will do anything when the project starts, when the backdrop switches to a particular page or when the sprite is clicked. 

```blocks3
when flag clicked

when this sprite clicked

when backdrop switches to [page v]
```

[[[scratch3-change-costumes-to-show-mood]]]

[[[scratch3-animate-movement-costumes]]]

[[[scratch3-graphic-effects]]]

[[[scratch3-jiggle-a-sprite]]]

--- /task ---

### Your message

--- task ---

 **How** you will say your message. You can add your message as either a **sprite/sprites** or a **sound**.

You can go to **Choose a Sprite** and select **Letters** from the Sprite Library or search for `numbers`:
![Show Choose a Sprite letters/numbers](images/from-me-letters-numbers.png){:width="300px"}

You could use the **Text** tool in the Paint editor to write a short message: 

[[[scratch3-use-text-tool]]]

You can record a spoken message if you like:

![The record icon from the add sound menu.](images/record-sound.png)

[[[scratch3-record-sound]]]

![The text to speech blocks menu icon.](images/text-to-speech.png)

[[[scratch3-text-to-speech]]]

--- /task ---

### Scratch editor reminders

--- task ---

[[[scratch3-copy-code]]]

[[[scratch3-full-screen]]]

[[[scratch3-duplicate-sprite]]]

--- /task ---

--- task ---






--- /task ---




--- task ---

Now, think about how the user will interact with your project.

For example:
+ "When the user clicks on the green flag, a sprite moves"

+ "When the user clicks on a sprite, the sprite changes colour"

**Tip:** Write down your main idea or tell a friend or family member. It is easier to make a project when you can explain what your idea is.

You might have lots of other ideas. Save them for later.

--- /task ---

--- task ---
Add a block for **when** your sprite should do something.

--- collapse ---
---
title: Start code with Hat blocks
---

```blocks3
when green flag clicked
when this sprite clicked
```

These blocks have a different shape — they are sometimes called **Hat blocks**. They start code running when a particular event happens, such as a user clicking.

--- /collapse ---

--- /task ---

--- task ---

Add the blocks that you need to make your sprite do **what** you want it to do.

Choose the blocks that you need and drag them underneath a Hat block. Put blocks inside a `forever`{:class="block3control"} block if you want them to keep running.

![Example code blocks](images/example-code-blocks.png)

You can use any of the skills that you have learned:

+ [Motion](https://projects.raspberrypi.org/en/projects/getting-started-scratch/5){:target="scratch_guide"}
+ [Looks](https://projects.raspberrypi.org/en/projects/getting-started-scratch/6){:target="scratch_guide"}
+ [Sound](https://projects.raspberrypi.org/en/projects/getting-started-scratch/7){:target="scratch_guide"}
+ [Variables](https://projects.raspberrypi.org/en/projects/getting-started-scratch/8){:target="scratch_guide"}

--- /task ---

**Tip:** Some of the best ideas come from playing. You will find good ideas by accident.

--- task ---

**Test:** 🔄 Show someone else your project and ask for 🗣️ their feedback. Do you want to make any changes to your book? 

⏱️ If you have time, you can upgrade your project. 

💡 You could:
- Add more code to your sprites
- Add another sprite
- Add another page
- Record a sound 
- Create a new costume in the Paint editor

--- /task ---

--- task ---

**Debugging** is finding and fixing mistakes in your code that are called **bugs** 🐞. 

You might find some bugs in your project that you need to fix. Here are some common bugs:

--- collapse ---
---

title: Debugging tips

---

+ **My sprite is going upside down** — Add a `set rotation style left-right`{:class="block3motion"} or `set rotation style don't rotate`{:class="block3motion"} block.

+ **My sprite 'jumps' when it changes costume or bounces** — Make sure that the costume is centred in the Paint editor (line up the blue cross with the cross hairs in the centre of the Paint editor).

+ **My sprite stops when it gets to the edge of the Stage** — Add an `if on edge, bounce`{:class="block3motion"} block.

+ **My sound does not play** — Have you added a block to `play sound`{:class="block3sound"} when the sprite is clicked? If you have copied code from another sprite, you will need to add the sound to this sprite from the **Sounds** tab. Check the volume on your computer and make sure that you have not lowered the volume with code — try `set volume to`{:class="block3sound"}`100`.

+ **Other sprites keep going in front of my sprite** — Use a `go to front layer`{:class="block3looks"} block.

+ **My sprite only moves/changes once** — Put your code inside a `forever`{:class="block3control"} block so it keeps running.

+ **My sprite does not change when I move a variable slider** — Put your code inside a `forever`{:class="block3control"} block so it keeps updating. 

--- /collapse ---

You might find a bug that is not listed here. Can you work out how to fix it?

🗣️ We love hearing about your bugs and how you fixed them. Use the **Send feedback** button at the bottom of this page and tell us if you found a different bug in your project.

--- /task ---


--- task ---
What is your next step? It might be to add more code to your sprite. It might be to add code to another sprite. It might be to record a sound or create a new costume in the Paint editor. 

Are you stuck for ideas? Don't forget to look at step 3: [Get inspiration](https://projects.raspberrypi.org/en/projects/from-me-to-you/2){:target="_blank"} and **See inside** some projects.

If you have finished or don't have much time left, then move on to the next step to share your digital card.

--- /task ---

--- task ---

Take a look at some From me to you projects created by community members, which you can explore in the Raspberry Pi Foundation’s studio of From me to you Community Projects  [See inside](https://scratch.mit.edu/studios/28525955){:target="_blank"}.

--- /task ---

--- save ---
