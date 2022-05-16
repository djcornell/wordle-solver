# wordle-solver
 
A simple command line wordle solver

# Example usage

Search for words containing letters e, t and s
> wordle-solver.exe -search ets 

Search for words that do not have letters z, y and q
> wordle-solver.exe -stop zyq

Search for words that start with s and end with t
> wordle-solver.exe -positions s___t

Search for words that start with s, end with t, do not use z, y and q and contains r somewhere
> wordle-solver.exe -positions s___t -stop zyq -search r

output
    search chars: [r]
    stop chars: [z y q]
    shirt
    short
    skirt
    smart
    snort
    sport
    spurt
    start
    strut
    found 9 matches