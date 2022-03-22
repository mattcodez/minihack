Thoughts:
- Maybe make it functional in order to limit large blocks that take a ton of space
Ex: 
if(expr, then(), else())
- Optional typing with hungarian notation?
s_name
- May consider having multiple editions of the language. Like a minihack and microhack. The micro would have even smaller coding constraints in order to minimize typing and maximize screen utilization. Would likely have reduced readability though.
- Maybe operator overloading but I think that would require strict typing which greatly increases verbosity

Principals:
- Need to limit indenting. But that is very valuable to programmers. How can this be done? Just force limited nesting? No function past two levels deep? Or no indenting but you're basically writing assembly at that point.
- Explicit typing, I hate not knowing where variables are coming from. Maybe it’s ok with an IDE but this needs to be useable without an IDE
- Optimize for average mobile keyboard layout, don’t force user to switch between keyboard types all the time
- Symbols limited to , and . which is weak
- Perhaps use mostly characters on other screen and optimize for user not switching back?
- 3 main options for Android, write out example code for what you could see all of them looking like

Constructs:
- Loop: lambda only for now
  - But if we limit indenting to have no nested blocks, lambdas are not possible
Objects/Classes: super simple definition and instantiation
- Literals: as many as possible (heck even add a date literal, I’ve always wanted that)
- Natives: TBD, guess this would overlap a lot with above
