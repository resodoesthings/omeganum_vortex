# omeganum_vortex
a fork of [ArisuTendou's](https://www.roblox.com/users/1205999625/profile) readable version of OmegaNum on Roblox
Original OmegaNum.js/OmegaNum.lua fork by [FoundForces](https://www.roblox.com/users/669755416/profile)

Any function with string.rep will crash out with numbers >10000, don't use toShortScientific/toScientific and maybe avoid HyperE
changes made -> .arrow() is more stable but still laggy asf, avoid using numbers bigger than 2
added debugging to toShortScientific because it sucks
**DO NOT USE toString**, JSON encoding is not available yet 
this is an abbreviation module that is capable of really fucking big numbers

```lua
-- Limit will be 10↑↑↑...↑↑↑10 with 1e3? ↑'s
-- You can also view this as 10 milletented to 10
```

```lua
--> list of functions
--[[
correct: corrects a omeganum
fromNumber: converts a number to omeganum
toNumber: converts a omeganum to number
toDisplay: displays in arrow notation
toString: converts a omeganum to string (USE THIS FOR STORING VALUES)
fromString: converts a string to omeganum
toOmega
eq
le
me
meeq
leeq
abs
neg
cmp
max
min
log10
isint
recip
pow
mod
root
mul
floor
ceil
div
add
sub
sqrt
log
exp
maxabs
eternitytoOmega
pow10
gamma
fact
rand
exporand
toBigNum
toScientific
toShortScientific
short
toEnt
toShortEnt
toEs
toShortEs
toHyperE
toShortHyperE
lambertw
slog
tetrate
pentate
lbencode
lbdecode
]]
```
