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
| ---   | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
__SFO__ | --- | 4   | 2   | 6   | 9   | 35  | 66  | 77  | 96  | 99  | 110 | 121 | 144 |
__SEA__ | 4   | --- | 15  | 10  | 35  | 32  | 72  | 96  | 70  | 108 | 120 | 144 | 110 |
__LAX__ | 2   | 15  | --- | 1   | 3   | 16  | 54  | 63  | 88  | 90  | 100 | 110 | 132 |
__LAS__ | 6   | 10  | 1   | --- | 2   | 8   | 42  | 56  | 72  | 81  | 90  | 99  | 108 |
__PHX__ | 9   | 35  | 3   | 2   | --- | 5   | 20  | 30  | 64  | 72  | 80  | 88  | 96  | 
__DEN__ | 35  | 32  | 16  | 8   | 5   | --- | 6   | 18  | 25  | 63  | 70  | 84  | 77  | 
__DFW__ | 66  | 72  | 54  | 42  | 20  | 6   | --- | 1   | 16  | 12  | 30  | 32  | 50  | 
__IAH__ | 77  | 96  | 63  | 56  | 30  | 18  | 1   | --- | 42  | 10  | 24  | 18  | 60  | 
__ORD__ | 96  | 70  | 88  | 72  | 64  | 25  | 16  | 42  | --- | 3   | 6   | 42  | 6   |
__CLT__ | 99  | 108 | 90  | 81  | 72  | 63  | 12  | 10  | 3   | --- | 1   | 2   | 18  |
__ATL__ | 110 | 120 | 100 | 90  | 80  | 70  | 30  | 24  | 6   | 1   | --- | 8   | 2   |
__MIA__ | 121 | 144 | 110 | 99  | 88  | 84  | 32  | 18  | 42  | 2   | 8   | --- | 20  | 
__JFK__ | 144 | 110 | 132 | 108 | 96  | 77  | 50  | 60  | 6   | 18  | 2   | 20  | --- | 


## Step 3 Order the Cites

This is the "Landscape" you now traverse.

Next     | SFO | SEA | LAX | LAS | PHX | DEN | DFW | IAH | ORD | CLT | ATL | MIA | JFK | 
| ---    | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
__1st__  | LAX | SFO | LAS | LAX | LAS | PHX | IAH | DFW | CLT | ATL | CLT | CLT | ATL |
__2nd__  | SEA | LAS | SFO | PHX | LAX | DFW | DEN | CLT | JFK | MIA | JFK | ATL | ORD |
__3rd__  | LAS | LAX | PHX | SFO | DEN | LAS | CLT | MIA | ATL | ORD | ORD | IAH | CLT |
__4th__  | PHX | DEN | SEA | DEN | SFO | LAX | ORD | DEN | DFW | IAH | MIA | JFK | MIA |
__5th__  | DEN | PHX | DEN | SEA | DFW | IAH | PHX | ATL | DEN | DFW | IAH | DFW | DFW |
__6th__  | DFW | ORD | DFW | DFW | IAH | ORD | ATL | PHX | MIA | JFK | DFW | ORD | IAH | 
__7th__  | IAH | DFW | IAH | IAH | SEA | SEA | MIA | ORD | IAH | DEN | DEN | DEN | DEN | 
__8th__  | ORD | IAH | ORD | ORD | ORD | SFO | LAS | LAS | PHX | PHX | PHX | PHX | PHX |
__9th__  | CLT | CLT | CLT | CLT | CLT | CLT | JFK | JFK | SEA | LAS | LAS | LAS | LAS |
__10th__ | ATL | JFK | ATL | ATl | ATL | ATL | LAX | LAX | LAS | LAX | LAX | LAX | SEA |
__11th__ | MIA | ATL | MIA | MIA | MIA | JFK | SFO | SFO | LAX | SFO | SFO | SFO | LAX |
__12th__ | JFK | MIA | JFK | JFK | JFK | MIA | SEA | SEA | SFO | SEA | SEA | SEA | SFO |
