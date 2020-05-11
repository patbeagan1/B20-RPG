### Action Economy
A normal turn is 4 seconds long. Instead of having different action "types", each action is valued at a certain number of seconds. Players are free to spend the seconds on their turn how they wish, or save some seconds for use on a later turn. However, any seconds which are saved in this way _must all be spent on the next action taken, regardless of what that action is_. This does not include the conditional step.

Some sample actions are listed here. For a more comprehensive list, look in the Appendix.
Attacking with a dagger: 1s
Attacking with a claymore: 3s
Moving one unit of speed: 2s
Switch weapons: 1s
Defending from an incoming attack (can be done on anyone's turn): 1s
Conditional step (moving one meter when  you would otherwise not move): 0s

This is a sample set of turns which shows how this economy would work.


|           Action          | Cost | Remaining time |
| :-----------------------: | :--: | :------------: |
|        Turn Starts        |      |     4/4 + 0    |
|  Moving one unit of speed |  2s  |     2/4 + 0    |
|  Attacking with a dagger  |  1s  |     1/4 + 0    |
|  Switching to a claymore  |  1s  |     0/4 + 0    |
| +++++++++++++++++++++++++ | ++++ | ++++++++++++++ |
|        Turn Starts        |      |     4/4 + 0    |
| Attacking with a claymore |  3s  |     1/4 + 0    |
| +++++++++++++++++++++++++ | ++++ | ++++++++++++++ |
|        Turn Starts        |      |     4/4 + 1    |
| Attacking with a claymore |  3s  |     2/4 + 0    |
|  Moving one unit of speed |  2s  |     0/4 + 0    |
| +++++++++++++++++++++++++ | ++++ | ++++++++++++++ |
|        Turn Starts        |      |     4/4 + 0    |
|            Hold           |  0s  |     4/4 + 0    |
| +++++++++++++++++++++++++ | ++++ | ++++++++++++++ |
|        Turn Starts        |      |     4/4 + 4    |
|      Conditional step     |  0s  |     4/4 + 4    |
|            Hold           |  0s  |     4/4 + 4    |
| +++++++++++++++++++++++++ | ++++ | ++++++++++++++ |
|        Turn Starts        |      |     4/4 + 8    |
|  Moving one unit of speed |  1s  |     4/4 + 0    |

One good strategy for this type of battle is to leave a second open while going into the next turn, to allow yourself the ability to defend from incoming attacks. However, defending against an incoming attack will result in you dropping all of your saved seconds, so be wary. Some spells or other forms of magic may take many seconds, or even minutes to complete, so when you're in a party it is best to have someone in the front line, blocking attacks so that mages can concentrate.

On the other hand, interrupting an enemy mage during a long incantation may decide the outcome of a battle. Keep in mind that if a character has a lot of health and is most of the way through an incantation, they may choose not to react to incoming attacks so as to not drop their spell.
