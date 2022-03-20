Thoughts:
- Maybe make it functional in order to limit large blocks that take a ton of space
Ex: 
if(expr, then(), else())
- Optional typing with hungarian notation?
s_name
- May consider having multiple editions of the language. Like a minihack and microhack. The micro would have even smaller coding constraints in order to minimize typing and maximize screen utilization. Would likely have reduced readability though.

Principals:
- Need to limit indenting. But that is very valuable to programmers. How can this be done? Just force limited nesting? No function past two levels deep? Or no indenting but you're basically writing assembly at that point.
- Explicit typing, I hate not knowing where something is coming from. Maybe it’s ok with an IDE but this needs to be useable without an IDE
- Optimize for average mobile keyboard layout, don’t force user to switch between keyboard types all the time
- Symbols limited to , and . which is weak
- Perhaps use mostly characters on other screen and optimize for user not switching back?
- 3 main options for Android, write out example code for what you could see all of them looking like

Constructs:
- Loop: lambda only for now
Objects/Classes: super simple definition and instantiation
- Literals: as many as possible (heck even add a date literal, I’ve always wanted that)
- Natives: TBD, guess this would overlap a lot with above

Grammar:
- Probably get rid of semi-colons to save space
- Even not making it optional for multiple statements on a single line, want to maximize vertical screen use as much as possible
- Sugar for return statement (maybe just <= 1,2,3

Functions
Don’t see a reason for both declared and expressions, just use a variable if you want it named
([args]) => statement
([args]) => {[statement,...]}

Statement
{block} | statement



Block
{[statement,...]}



Running major example 1
<c, p> from ‘system’

main = () = > {
  c.log(‘started’)
  d = if(p.args[1] == ‘yes’
     begin^p.args[2]
     end
  )
  <= d
}

end = ‘junk’

Begin = (v) =>
  // loop over each number in string and add together
  // can only loop arrays maybe but add sugar for easy range creation
  total = 0
  Loop: (item) = [***v]
          total += i_(item) // assumes type_(expr) for dynamic casting
  


Running major example 2 (keyboard 2)

Not sure how to get around not heaving letters, hard to read what’s happening otherwise. Maybe just aim for small programs? 
Ordinal parameters only means less verbosity
.number for named references, just number for implied ordinal params
Get rid of equals for assignment, just assume leftmost is assignment
Hmm, default money symbol is different between languages/countries, don’t use or allow interchangeable? Probably just don’t use
> function entry then < function leave (return)

.1, .2 // have to memorize 1 is default console, 2 is process, etc

.0 > 
