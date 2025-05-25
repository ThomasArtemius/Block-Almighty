# Block-Almighty
Mini-Project Game for Artificial Intelligence Course.
There's a thief who stole a sacred artefact and you, The Angry God, need to stop him from escaping.
You have the power to add a block or remove a block on his path.
All you need to do is just left click on the available path to add the block or right click to remove a maze wall.
Prevent him from reaching the blue portal.
![](https://github.com/ThomasArtemius/Block-Almighty/blob/main/Gifs/Proto7%20Demo.gif)

## A* Star Based
![](https://github.com/ThomasArtemius/Block-Almighty/blob/main/Gifs/Proto2.gif)

## Min Heap Data Structure
A* formula is f(x) = g(x) + h(x), where g(x) is the cost and h(x) is the heuristic distance, The root is storing the lowest f(x) and a candidate for the next path.
Once the agent take the path, it will be poped from the heap and its position will be replace by the new lowest f(x) value.
The min heap structure is to contain the lowest value in descendeng manner, where the lowest point is store in the upper part. Agent can only explore up to 3 paths (if the agent reach the intersection). 
Then, the agent must choose the next path (lowest f(x)). As long the agent can find the lowest f(x) than before, it will be stored in the heap.
![](https://github.com/ThomasArtemius/Block-Almighty/blob/main/Gifs/Proto6.gif)

## Assets
The assets are generated using bing and the SFX as well the music is downloaded from pixabay
