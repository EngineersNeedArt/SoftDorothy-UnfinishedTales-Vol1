# Soft Dorothy Software: Unfinished Tales (Vol 1)
The first part of a collection of **Soft Dorothy Software** scraps and game experiments from the late 80's and early 90's.

<p align="center">
<img width="758" src="https://github.com/EngineersNeedArt/SoftDorothy-UnfinishedTales-Vol1/blob/ea029bff1b3a18a76b2187c4dac275e4f3823a34/Images/Ridaava-walk.png">
</p>

### Sleepless Nights

Around 1988 when I was still in college I wrote my first shareware game on the Macintosh computer called **Glider**. For a number of years that followed I spent a good deal of my conscious hours (and perhaps unconscious hours as well) progamming little games for my amusement. I think the little Macintosh Plus with crisp black and white pixels, curious mouse interface, became a new kind of canvas for me. I don't think I was *naturally* a programmer, programming was a means to an end — an end I suppose that consisted of little games that I approached as a kind of little art.

<p align="center">
<img width="320" src="https://github.com/EngineersNeedArt/SoftDorothy-UnfinishedTales-Vol1/blob/3c0c2c6514f32224374624b40ff1abba4480e3cb/Images/earlyprogrammer.jpeg">
</p>

To be clear the games had to be fun as well. If you allow at least that computer games have an art *aspect* we'll agree that games are not the kind of art you hang on the wall.

To that end I often "sketched" out a game, fairly quickly sometimes, to find early on that it was not to be. Perhaps the game seemed like it had potential but it was going to consume a year of my life to write it. Sometimes though the game just wasn't grabbing me — was simply missing something compelling to make it enjoyable.

I suspect my personality is to reject "lost ideas" quickly where someone else might have spent more time trying to nurture them. Perhaps there were in fact some diamonds in the rough. But other ideas were calling and so off I went to the next thumbnail sketch.

Regardless, if only for some of the pixel art, it may have been worth it to me recovering these prototype games and experiments.

### Bundle Identifiers

The old Macintosh OS (before OS X) used four-character codes to identify each application. These were called bundle identifiers. Beginning with **Glider** I established a pattern for my own game's bundle identifiers. The first two characters were lower-case: `sd` while the last two were digits beginning, with **Glider**, `01`.

I found on one of my recovered hard drives a document listing the titles and bundle identifiers I had used. Here is the beginning of the list:

```
sd01 = Glider          v.1.0/2.0/2.02ß/3.0          +++
sd02 = La Luna         not distributed
sd03 = Reaction        not distributed
sd04 = BlackBox        not distributed
sd05 = Paria           incomplete <slow, complex>
sdHM = Harmonigraph    not distributed
sd08 = FishTank        not distributed
sd09 = Glypha          v.1.0/2.0                    +++
sd10 = Mobocracy       incomplete <time-consuming>
sd11 = Dione           incomplete <no fun>-K
sd12 = Light Cycles    incomplete <buggy>-K
sd13 = MiniGolf Edit   incomplete
sd14 = MiniGolf Cr     incomplete <buggy>
sd15 = K-10            incomplete <sound prob.>
sd16 = War             not distributed
sd17 = Sled Run        incomplete <slow, no fun>
sd18 = Stella Obscura  v.1.0                        +++
:
```

It begins of course with `sd01` for **Glider**. If you had a Macintosh back in the 1990's you might recognize `sd09`, **Glypha**. The bundle identifiers listed in between though belonged to programs that never left my hard drive.

To the degree I am able to, this repo represents those "lost" experiments. We'll skip **Glider**, **Glypha** and **Stella Obscura** from the list — since they shipped they're already in a repo called <a href="https://github.com/EngineersNeedArt/SoftDorothy-SharewareProjects">**SoftDorothy-SharewareProjects**</a>.

### La Luna, Reaction, BlackBox:

These programs are, at this time, completely lost. I had copied over the binaries from one file system to another, over a decade ago, but alas all the resource forks were lost and so to then are the applications.

> The dates on the binaries (if correct) suggest that I toyed around with the apps in September, 1989.

It's possible (but I don't remember exactly) that **La Luna** was my first stab at a game like <a href="https://en.wikipedia.org/wiki/Elite_(video_game)">Elite</a>. Elite had a huge impression on me with its seeming depth and its ability to completely draw me into its world. More than once I would take a stab at doing something like Elite in scale but then shelve it when I realized the time that would be consumed to do it any justice.

**Reaction** was, to my recollection, more of an educational demo of a nuclear chain reaction. The application showed "neutrons" as a regular grid of circles on the screen. A control allowed the user to change the density of the neutrons (the spacing between neutrons in the grid). With the click of a button the reaction would begin with one neutron disappearing — decomposing into a few energetic neutrons that scattered at random angles from the original neutron's location. If any of the neutrons struck another neutron in the grid before they left it would cause that neutron to also decompose into a few more.

It's possible I was inspired to write the app after reading one of the *Computer Recreations* articles in *Scientific American* magazine (<a href="https://ia800905.us.archive.org/34/items/pdfy-URIEj2bFFdno0y_f/scientificamerican0285-18.pdf">example article</a>).

I am a bit at a loss to recall what **BlackBox** might have been. My best guess is that it may have been similar to a puzzle game where you deduce the location of a number of hidden mirrors in a "black box" (hidden on a grid obscured by a black rectangle) by placing lasers around the perimeter and note where the reflected (?) laser light exits the grid.

### Paria:

**Paria** was very much an *Elite* inspired sketch of a game. If you run the game in an emulator, some small amount of activity comes to life with regard to the controls and window. You have to select `New Game` from the `File` menu first.

> Don't be fooled by all of the menu items in the games that follow — many are in fact merely stubs and do nothing when selected. That's just the nature of quick prototyping.

<p align="center">
<img width="512" src="https://github.com/EngineersNeedArt/SoftDorothy-UnfinishedTales-Vol1/blob/957b1a683a521a08dc317d4a1776aa9c3eed01af/Images/paria.png">
</p>

You're piloting a spaceship (if that's not obvious) — and in this case the ship was made intentionally complicated to add an element of realism to the game and to allow for perhaps some clever (or desperate) energy management strategies to liven up the game.

The left side of the console is concerned with power creation and power reserves (primary, secondary). Weapons (top right, `LAS`, incomplete), protective energy shields (bottom right) would consume that energy during a fire fight.

Top center is the star map and buttons to the left of it toggle the map display to show other information to aid in navigation.

Below the map/navigation view is your cockpit view out the front of the spacecraft.

Playing with it a bit I see that the `+TH` button (and ones near it) allow you to adjust your ship velocity. In fact if you throttle up ,eventually you will see a planet approach in the cockpit view.

> Before posting a lot of these old sketches, I tried to add a little code to throttle the game somewhat since on modern emulators running "all out" the demos were often unplayable. In the case of **Paria** the planet flew by so fast I had blinked and missed it.

Clicking the mouse in the cockpit view appears to fire a laser but I am pretty sure it's just stubbed in for show — nothing results from it but a brief dip of your ship's energy reserves.

Even with the barest degree of functionality in the sketch it's clear that many months, perhaps a year or more, would have been required to implement a full and proper game. Text along the bottom hints at an "intelligent" computer assistant that needed flushing out, full 3D navigation with enemy ships, possible trading, would have been required. Abort (`ABT`), and various radio (`RDIO`) controls (and perhaps `DES` was self-destruct) had to be fleshed out as well.

> It looks like this one was begun around December, 1989 — more or less abandoned January, 1990.

Could it ultimately have been "Elite-levels" of fun? Who knows. I think though I saw what I had at that point and decided to move along to the next idea. Even a stub of a game like **Paria** I thought I could always return to at some later date.

### Harmonigraph:

<p align="center">
<img width="512" src="https://github.com/EngineersNeedArt/SoftDorothy-UnfinishedTales-Vol1/blob/3b4e9592b1ba70d65cdc99b8beaba51c27db5611/Images/harmonigraph.png">
</p>

**Harmonigraph** was a little experiment of the educational toy variety like **Reaction** that I described earlier. A pendulum (or multiple) controls the X-axis while another pendulum(s) controls Y-axis. `Start` kicks off the calulating, rendering.

There was a tool called *Prototyper* that I picked up about this time and **Harmonigraph** was I believe the first application I created using it. *Prototyper* made it easy to create windows with controls, text and would then generate the C or Pascal code to give you a shell with which you could then go in and add the functionality.

For **Harmonigraph** icons-as-buttons along the left allow you to increase or decrease the amplitude of the pendulums — modify the frequency, phase. It more or less works — though seems to crash the OS when you quit (ha, ha). I didn't play with it exhaustively though.

This might be a fun one to rewrite for the web using Javascript, an HTML5 Canvas... I would prefer though to have a UI with stacked pendulums where you could pull them back to set the amplitude, slide a weight up and down to change the period....

### FishTank:

<p align="center">
<img width="512" src="https://github.com/EngineersNeedArt/SoftDorothy-UnfinishedTales-Vol1/blob/c590a8600a94ddedf2ca357f3784beeab580d784/Images/fishtank.png">
</p>

Like a screen-saver, **FishTank** was only ever meant to be a virtual fish tank that you kind of watched. Desiging your own tank — stocking it with fish you select, arranging the various plants and decorations would have made it somewhat amusing. Tamagotchi-like I might have required you to periodically feed the fish lest they die...

It was shelved long before any of those features saw the light of day. I think the payoff-vs-effort indicator was trending low in my mind for this one so on to the next idea.

> Original file dates suggest I started it in December 1989, bailed by March 1990.

### Mobocracy:

<p align="center">
<img width="512" src="https://github.com/EngineersNeedArt/SoftDorothy-UnfinishedTales-Vol1/blob/1f7aa651cca6681534645b2c269908291a77d5d6/Images/mobocracy.png">
</p>

Side-scroller, post apolocalyptic ... **Mobocracy** was a very 90's game. Original file dates suggest February and March of 1990 were consumed with knocking this half-baked sketch out.

If you wanted to kick the tires, you can only "play" it by selecting `Practice` from the `File` menu. Controls: try `A`, `D`, the space bar, the arrow keys. Artwork has our hero with her sword drawn, parrying, thrusting but if those modes are implemented in the code I didn't take the time to discover. There is additional artwork for a kind of "bounty wall", a weapons shop — none of which were ever implemented.

<p align="center">
<img width="512" src="https://github.com/EngineersNeedArt/SoftDorothy-UnfinishedTales-Vol1/blob/1729ccaaa9f2052e13f27abb42abd1c464bef695/Images/ridaava_with_sword.png">
</p>

The lower portion of the game hints at a weapon selection, map, an inventory of bullets, gold, etc. (The player's fatigue is expended by jumping, etc., replenishes quickly though.)

This was clearly a game that, whether the payoff was high or not, was clearly going to be a huge effort. Although Prince of Persia (Metal Slug, etc.) would show it was possible, I think I also felt constrained by the almost 1-diminsional aspect of a side-scroller. Maybe I would have felt more confortable making it a 2-D *Rogue-like* instead. In any event, there were other fields still to sow.

### Dione:

<p align="center">
<img width="404" src="https://github.com/EngineersNeedArt/SoftDorothy-UnfinishedTales-Vol1/blob/e374d48e51853ed81d4fd3df251d770e74a7e4e9/Images/Dione.png">
</p>

**Dione** was not one of those sown fields that would bear fruit. More or less started out as an *Asteroids*-like. Actually, if you really know your obscure 80's arcade games, it took more inspiration from *Space Duel* — a game where two players find their *Asteroids*-like spaceships tethered together creating all manner of fascinating dynamics when each craft can independently rotate, thrust. Watching the linked ships tumble across the screen like a baton in freefall was, I think, what I was initially going for.

I couldn't have failed any harder. **Dione** (the name came from Greek mythology) should have been called "Ball and Chain" as that is how the game play feels. If you really want to try it: left and right arrow keys, `Shift` and space bar.

Is there a diamond in the rough here? Why, no, not at all. Still, *Space Duel* is still, in my opinion, ripe for really kicking up a notch into the bullet-hell genre. Now *that* would be something.

> **Dione** was a March, 1990 sketch.

### Light Cycles:

One of the earliest games I had written was a "TRON" light cycle game on the Commodore VIC-20. Maybe I thought I would have a go with it on the Macintosh. In fact, games being as rare in general as they were on the Mac in those days, there wasn't a proper clone.

<p align="center">
<img width="427" src="https://github.com/EngineersNeedArt/SoftDorothy-UnfinishedTales-Vol1/blob/10c1043574c957df91bc10183616c4aa27f05349/Images/LightCycleSprites.png">
</p>

**Light Cycles**, should you try to play it in its rough form, is un-throttled and so plays best in an emulator that you can run at 1990 speeds. I must have decided early on to bail on it however as much of the sprite artwork is unimplemented. That's kind of too bad because I would love to see the player "rez" in, see the *Recognizer* enter the game grid....

### MiniGolf (Editor and Player):

This was the first time I thought to tackle miniature golf as a computer game. Like the previous **Light Cycles** I went with a 2.1-dimensional look. Which is to say, it's more or less a top-down game but I added just a bit of an orthographic shear to it to suggest a hint of 3-dimensionality.

> Later, when I began programming in color, I would revisit miniature golf in an unfinished game called **LiliPutz**.

This early B&W attempt consisted of two separate apps: **MiniGolf Editor** for creating the courses and **MiniGolf Player** for, of course, playing them.

<p align="center">
<img width="512" src="https://github.com/EngineersNeedArt/SoftDorothy-UnfinishedTales-Vol1/blob/9f1c1044f364344eccf0cb5acb9fc14c2356dd05/Images/MiniGoldEditor.png">
</p>

I saw that they compiled and ran (added some throttling to **MiniGolf Player**) but otherwise relied on the course (`Course.2`) that was my little test course from March of 1990. `Try It` doesn't work in **MiniGolf Editor**. Instead you'll have to `Open Course...` and `Begin Game` in **MiniGolf Player**.

<p align="center">
<img width="512" src="https://github.com/EngineersNeedArt/SoftDorothy-UnfinishedTales-Vol1/blob/9f1c1044f364344eccf0cb5acb9fc14c2356dd05/Images/MiniGolfPlayer.png">
</p>

Oh, the collision detection is completely broken — balls don't often ricochet correctly off the walls, sometimes end up outside the course. You know, these little things are not terribly important when you're just protoyping a game. I mean these are solveable issues. But if for other reasons the game seems destined for the byte-heap, why bother?

And so I bothered not for **MiniGolf**. As I mentioned, I would revist it later, in color. I am unclear as to why I did abandon this version and move on to experiment with new games. 

> When I get to the color version I can explain why that one was offloaded though.

### K-10:

<p align="center">
<img width="512" src="https://github.com/EngineersNeedArt/SoftDorothy-UnfinishedTales-Vol1/blob/25ac5a339811b08cc9ca9e6b34e4c4ff98a6b316/Images/K-10.png">
</p>

I was in college at the University of Kansas when I began **K-10**. It was named for Kansas highway 10 — the more or less straight and flat stretch of asphalt between Lawrence, Kansas and Kansas City. For a driving game that wanted to keep things simple K-10 was a cheap excuse to present only a straight road.

<a href="https://en.wikipedia.org/wiki/Spy_Hunter">*Spy Hunter*</a>, the old arcade game, was an abvious inspiration — it too being a top-down driving game where the cars have weapons. Perhaps a little more obscure, I was inspired too by the Steve Jackson Games pen-and-paper RPG <a href="https://en.wikipedia.org/wiki/Car_Wars">*Car Wars*</a>.

You can see the *Car Wars* inspiration on the right portion of the game where armor (front, rear, driver and passenger side) is indicated. Fore and aft weapons... Also, like "rolling up a character", the game was to rely heavily on your designing your car, fitting it with the various weapons and armor, engine upgrades — to the degree your car budget allowed.

I was focusing a good deal at this early stage on getting the shifting (the cars were to be all manual) correct. You have to shift into 1st gear to get rolling, watch the RPM gauge, shift to 2nd when you start to red-line. I was trying to get the power curves to feel right so that putting the car in 4th at a stop would be lugging the engine — downshifting to 1st at highway speed would possibly blow the engine.

<p align="center">
<img width="418" src="https://github.com/EngineersNeedArt/SoftDorothy-UnfinishedTales-Vol1/blob/cde2877bb5f97c39f477f9eb198ca0a21a6de847/Images/K-10_sprites.png">
</p>

As with a lot of these "sketches", you can look to some of the placeholder graphical elements or inoperable menu items to get an idea of where I hoped to eventually go with the game. The `PICT` resource too hints at a cop car, caltrops, mines and other various weapons that might eventually be employed in the game.

I have a vague recollection that the physics involved started to overwhelm me. I was stuck trying to decide if you model the drivetrain physics from the asphalt to the tire (via frictional component) through the transmission and its gearing to the cylinders trying to turn a flywheel? Or do you go the reverse direction and start with the torque from the cylinders firing, work through the transmission, etc? It seemed like a problem where the math had to go both directions at the same time.

Regardless, I seemed to have shelved the game sometime around April, 1990. Is it worth revisiting? Maybe you think 
<a href="https://en.wikipedia.org/wiki/Carmageddon">Carmageddon</a> finally (and thoroughly) scratched that 
cars-destroying-other-cars itch but I still think there is room for a top-down "Death Race 2000".

If you decide to try the game out, I have been successful 1) `Car` —> `Open Car...` and select a car from the Cars folder then 2) select `File` —> `Test Run`. The keys `1`, `2`, `3`, and `4` shift gears (you need to shift to 1st gear right away), the mouse button is the accelerator, moving the mouse left and right is how you steer.

You will probably see an enemy car or two — and they will fire upon you. If I had implemented player weapons I was unable to discover how to fire them. Also, collision detection is very basic.
