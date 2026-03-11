# C++ A* Pathfinding Project

## Overview
My A* Project is a little game that you can play with the algorithm given a map file for it to work with it will try find the best path to the end with an energy cost in mind. Each tile you move reduces your energy by 1 and you can gain energy in the map by the +2 and +3 tiles. The algorithm knows it cannot end with a negative energy so you must make a map that will work or you will be given an error. Example maps are below
## Features
This project features an A* algorithm with more that just a heuristic cost of making a move compared to another it needs to understand that it has an energy aswell and that energy is used to move around the board     

Maps are respresented as a grid of tiles loaded from .txt files       

The maps have multiple different tiles that affect movement or energy  
- '#' = Wall  
- . = Walkable tile  
- A = Acid (-5 energy)  
- 2 = +2 Energy Pickup  
- 3 = +3 Energy Pickup

After solving a map data is given back to the user like  
- The number of steps taken  
- Final Energy  
- Nodes expanded  
- Acid Tiles used

The project can also handle multiple maps at one time aswell  

## How It Works
Step 1 - Start Node  
The algorithm starts here at S with an energy of 20  
This node is placed in the open set 

Step 2 - Expand Start Node 
The algorithm explores neighbouring tiles
moving to a tile that is closest to the G(oal) while doing a calculation based off of the best possible move and the energy calculation is done 

## File Structure

## Setup and Run

## Sample Maps

## Results

## Lessons Learned

## Future Improvements
