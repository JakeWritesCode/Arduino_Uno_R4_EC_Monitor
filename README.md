# Arduino Uno R4 EC / TDS Monitor

I created this package because the EC monitors you can buy for arduino on the web only measure 
up to around 1000PPM, and I needed more range than that to measure hydroponic nutrients
in water. 

I found this wonderful repo: https://github.com/wvmarle/Arduino_ECSensor which seemed to solve
the problem.

However, I'm using an Arduino Uno R4 which uses the new 32bit ARM arch, so this code did not port well.
I've re-written it to be compaitble with the Uno R4 and moved some stuff to the arduino language so its 
a bit more readable (IMO).

I need to write a better readme here. If you stumble across this on the internet before I get round to 
it raise a GH issue and I'll help out / finish the docs.
