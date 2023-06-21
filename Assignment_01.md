## [Assignment: 01](https://github.com/H-R-S/Python-Assignments/blob/main/Assignment_01.md)

Q. In the season 5 finale of Game of Thrones, Jon Snow was assassinated by members of the Night's
Watch, led by Ser Alliser Thorne and including Olly, a young boy Jon had taken under his wing.
The behind-the-scenes story of Jon Snow's death scene is that it was a closely guarded secret. The
showrunners, David Benioff and D.B. Weiss, went to great lengths to keep the scene from being
spoiled, even going so far as to shoot fake death scenes to throw off paparazzi and fans.
As for why Jon Snow was killed, there were several factors at play. Firstly, Jon had made a
controversial decision to allow the wildlings (a group of people who live north of the Wall) to cross
over into the Seven Kingdoms and settle in the Gift, a stretch of land south of the Wall. This
decision was not popular among the members of the Night's Watch, who saw the wildlings as their
enemies.
Secondly, Jon had become increasingly focused on the threat posed by the White Walkers, an
ancient enemy who were slowly but surely marching south towards the Wall. Some members of
the Night's Watch saw Jon's preoccupation with the White Walkers as a distraction from their real
mission, which they saw as defending the Seven Kingdoms from wildling invasion.
Finally, there was a longstanding tension between Jon and Ser Alliser Thorne, who had never liked
Jon and resented him for being appointed Lord Commander over himself. Thorne saw Jon's
decision to let the wildlings through the Wall as a betrayal of the Night's Watch, and saw Jon
himself as a threat to the organization's integrity.
All of these factors came to a head in the season 5 finale, when Jon was ambushed and stabbed by
members of the Night's Watch who had grown tired of his leadership. The scene was a shocking
moment in the show's history, and left fans wondering what would happen next.

In simple words :

In the TV show Game of Thrones, a character named Jon Snow was killed by members of the
Night's Watch in the season 5 finale. This was a shocking moment for viewers.
There were several reasons why Jon was killed. Firstly, he allowed a group of people called the
wildlings to cross over into the Seven Kingdoms and settle in a stretch of land south of a giant
wall. This was seen as controversial by some members of the Night's Watch who saw the wildlings
as their enemies.
Secondly, Jon was very focused on a threat posed by an ancient enemy called the White Walkers,
who were marching south towards the wall. Some members of the Night's Watch didn't see the
White Walkers as a priority and thought Jon was neglecting his duty to defend against the
wildlings.
Lastly, there was a tension between Jon and one of the leaders of the Night's Watch, Ser Alliser
Thorne, who didn't like Jon and saw him as a threat to the organization. Thorne saw Jon's decision
to let the wildlings through the wall as a betrayal.
All of these issues came to a head and led to Jon being attacked and killed by members of the
Night's Watch.
If Jon Snow had not allowed the wildlings to cross over into the Seven Kingdoms and settle in the
Gift, then he may not have been killed by the Night's Watch who saw the wildlings as their enemies.
Else if Jon Snow had prioritized defending against the wildlings instead of the White Walkers, then
some members of the Night's Watch may not have seen him as neglecting his duty, which was one
of the reasons why they killed him.
Else if Jon Snow had made an effort to mend his relationship with Ser Alliser Thorne, who saw
him as a threat, then he may not have been killed by Thorne and his followers.
It's important to note that these are hypothetical scenarios and there were likely other factors that
contributed to Jon Snow's death in the show.
Game of Thrones Simulation Scenario
You are a developer tasked with creating a simulation of the events leading up to Jon Snow's death
in the TV show Game of Thrones. The simulation should use Python variables, strings, conditional
statements, and loops.

Steps:

Define the variables that will be used in the simulation. These variables include jon_alive (a
Boolean that tracks whether Jon Snow is alive or dead), wildlings_crossed (a Boolean that tracks
whether Jon allowed the wildlings to cross over into the Seven Kingdoms), white_walkers_threat
(a Boolean that tracks whether Jon focused on the threat posed by the White Walkers),
alliser_thorne_hates_jon (a Boolean that tracks whether Ser Alliser Thorne dislikes Jon Snow),
and night_watch_mutiny (a Boolean that tracks whether there is a mutiny within the Night's
Watch).

Ask the user whether Jon Snow should allow the wildlings to cross over into the Seven Kingdoms.
Use a conditional statement to set the wildlings_crossed variable to True or False depending on
the user's response.

Ask the user what Jon Snow's priority should be: defending against the wildlings or the White
Walkers. Use a conditional statement to set the white_walkers_threat variable to True or False
depending on the user's response.

Ask the user whether Jon Snow should make an effort to mend his relationship with Ser Alliser
Thorne. Use a conditional statement to set the alliser_thorne_hates_jon variable to True or False
depending on the user's response.

Use a conditional statement to check if all the conditions for a Night Watch mutiny are met. These
conditions are: the wildlings have crossed over into the Seven Kingdoms, Jon Snow is focused on
the threat posed by the White Walkers, and Ser Alliser Thorne dislikes Jon Snow. If all the
conditions are met, set the night_watch_mutiny variable to True.

Use a conditional statement to check if there is a Night Watch mutiny. If there is a mutiny, set the
jon_alive variable to False.

Use a conditional statement to output whether Jon Snow survived or was killed.

Use a loop to allow the user to run the simulation multiple times if they choose to do so.

### Code:
```
jon_alive = True
wildlings_crossed = False
white_walkers_threat = False
alliser_thorne_hates_jon = False
night_watch_mutiny = False

wildlings_input = input("Should Jon Snow allow the wildlings to cross over into the Seven Kingdoms? (y/n) ")
if wildlings_input.lower() == 'y':
    wildlings_crossed = True

priority_input = input("What should Jon Snow's priority be? Defending against the wildlings (w) or the White Walkers (ww)? ")
if priority_input.lower() == 'ww':
    white_walkers_threat = True

alliser_input = input("Should Jon Snow make an effort to mend his relationship with Ser Alliser Thorne? (y/n) ")
if alliser_input.lower() == 'n':
    alliser_thorne_hates_jon = True

if (wildlings_crossed) and (white_walkers_threat) and (alliser_thorne_hates_jon):
    night_watch_mutiny = True

if (night_watch_mutiny):
    jon_alive = False

if (jon_alive):
    print("Jon Snow survived.")
else:
    print("Jon Snow was killed.")

while True:
    repeat_input = input("Do you want to run the simulation again? (y/n) ")
    if repeat_input.lower() == 'n':
        break
    else:
        jon_alive = True
        wildlings_crossed = False
        white_walkers_threat = False
        alliser_thorne_hates_jon = False
        night_watch_mutiny = False

```
### Output:
```
Should Jon Snow allow the wildlings to cross over into the Seven Kingdoms? (y/n) y
What should Jon Snow's priority be? Defending against the wildlings (w) or the White Walkers (ww)? w
Should Jon Snow make an effort to mend his relationship with Ser Alliser Thorne? (y/n) y
Jon Snow survived.
Do you want to run the simulation again? (y/n) n
```
