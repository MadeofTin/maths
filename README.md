# Mathscapes
Solving Problems with Mathematical Landsapes 

   Start|   1st | 2nd | 3rd | 4th | 5th | 6th | 7th | 8th | 9th | 10th | 11th | 12th | 
         --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
     __SFO__ | LAX | LAS | PHX | SEA | DEN | DFW | IAH | ORD | CTL | ATL | MIA | JFK | 
     __SEA__ | SFO | LAS | LAX | DEN | PHX | DFW | ORD | IAH | CLT | ATL | JFK | MIA | 
     __LAX__ | LAS | SFO | PHX | DEN | SEA | DFW | IAH | ORD | CLT | ATL | MIA | JFK |
     __LAS__ | LAX | PHX | SFO | DEN | SEA | DFW | IAH | ORD | CLT | ATL | MIA | JFK | 
     __PHX__ | LAS | LAX | SFO | DFW | DEN | IAH | SEA | ORD | CLT | ATL | MIA | JFK |
     __DEN__ | PHX | LAS | DFW | LAX | ORD | IAH | SFO | SEA | CLT | ATL | JFK | MIA | 
     __DFW__ | IAH | DEN | CLT | ORD | PHX | ATL | LAS | MIA | LAX | JFK | SFO | SEA |
     __IAH__ | DFW | CLT | DEN | ATL | PHX | MIA | ORD | LAS | LAX | JFK | SFO | SEA | 
     __ORD__ | CLT | ATL | JFK | DFW | DEN | IAH | MIA | PHX | LAS | SEA | LAX | SFO |
     __CLT__ | ATL | MIA | ORD | DFW | IAH | JFK | DEN | PHX | LAS | LAX | SFO | SEA |
     __ATL__ | CLT | JFK | ORD | MIA | DFW | IAH | DEN | PHX | LAS | LAX | SFO | SEA |
     __MIA__ | CLT | ATL | IAH | DFW | JFK | ORD | DEN | PHX | LAS | LAX | SFO | SEA |
     __JFK__ | ATL | ORD | CLT | MIA | DFW | IAH | DEN | PHX | LAS | SEA | LAX | SFO |
     
## Step 2

Here | to | There | Position  |
--- | --- | --- | --- |
DEN | --> | DFW | 3rd |
DFW | --> | DEN | 2nd |

Multiply the positions together.

   |   |   |   |
--- | --- | --- | --- |
 DEN | <-> | DFW | 6 |
 
### Full Table

City    | SFO | SEA | LAX | LAS | PHX | DEN | DFW | IAH | ORD | CLT | ATL | MIA | JFK | 
| ---   | --- | --- | --- | --- | --- | --- | --- |  --- | --- | --- | --- | --- | --- |
__SFO__ | --- | 4*1 | 1*2 | 2*3 | 3*3 | 5*7 | 6*11 | 7*11| 8*12 | 9*11 | 10*11 | 11*11 | 12*12 |
__SEA__ | --- | --- | 3*5 | 2*5 | 5*7 | 4*8 | 6*12 | 8*12 | 7*10 | 9*12 | 10*12 | 12*12 | 11*10 |
__LAX__ | --- | --- | --- | 1*1 | 3*1 | 4*4 | 6*9 | 7*9 | 8*11 | 9*10 | 10*10 | 11*10 | 12*11 |
__LAS__ | --- | --- | --- | --- | 2*1 | 4*2 | 6*7 | 7*8 | 8*9 | 9*9 | 10*9 | 11*9 | 12*9 |
__PHX__ | --- | --- | --- | --- | --- | 5*1 | 4*5 | 6*5 | 8*8 | 9*8 | 10*8 | 11*8 | 12*8 | 
__DEN__ | --- | --- | --- | --- | --- | --- | 3*2 | 6*3 | 5*5 | 9*7 | 10*7 | 12*7 | 11*7 | 
__DFW__ | --- | --- | --- | --- | --- | --- | --- | 1*1 | 4*4 | 3*4 | 6*5 | 8*4 | 10*5 | 
__IAH__ | --- | --- | --- | --- | --- | --- | --- | --- | 7*6 | 2*5 | 4*6 | 6*3 | 10*6 | 
__ORD__ | --- | --- | --- | --- | --- | --- | --- | --- | --- | 1*3 | 2*3 | 7*6 | 3*2 |
__CLT__ | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | 1*1 | 2*1 | 6*3 |
__ATL__ | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | 4*2 | 2*1 |
__MIA__ | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | 5*4 | 
__JFK__ | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | 


## Step 3 Order the Cites
