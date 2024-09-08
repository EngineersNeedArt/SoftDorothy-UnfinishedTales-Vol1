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

It's possible (but I don't remember exactly) that **La Luna** was my first stab at a game like <a href="https://en.wikipedia.org/wiki/Elite_(video_game)">Elite</a>. Elite hasd a huge impression on me with its seeming depth and its ability to completely draw me into its world. More than once I would take a stab at doing something like Elite in scale but then shelve it when I realized the time that would be consumed to do it any justice.

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
