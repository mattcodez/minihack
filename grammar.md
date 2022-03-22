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
