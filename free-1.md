# Free project 1



An RPG mapmaker with mixed tile sizes and shapes. It would let users create or upload tiles of certain sizes, then specify on the map which patterns belong where by clicking and dragging map regions and selecing the tile to fill the area. There would also be an option to designate what a "border" to the tile looks like, and then the area would have the border on the outside. Tiles that don't fill a square could also have transparency and be layered over others, so borders wouldn't have to be sharp and linear. Once the areas and patterns are specified, an image would be produced. "Objects" could also be placed on the scene, layered above tiled areas.



## The user and a language

This section describes who the project would serve and why a language might be a

good way to meet their needs.



The user would be game developers (or perhaps bored artists). Unfortunately, this feels more like an application than a language, but map generation is a very useful tool.



### What's the need?

_What need is met by your idea? Who are you helping? What is that person's

experience like now? What would their experience be like if you could help 

them?_



Well, existing map generators that I'm aware of generally have set tile sizes, which limits the ability to quickly design maps that don't look as blocky or aren't constrained by having every piece of the map fill a tile of the same size. But to have complete control over a map would require illustrating it entirely from scratch, which would take too long. This would be a tool that might keep the process quick while allowing for more artistic design decisions.



### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_



If existing map makers count as DSLs, then these tools have already proven to address this type of need.



### Why you?

_What excites you about this idea? How did you come up with it?_



Words cannot express my interest in game design.

Map generation is one of the basics of game dev tools, and free-to-use tools can always be improved on.



### Domain

_Describe the project's domain in five words._



Tile map editing and generation



### Interface (syntax)

_How might the user interact with the language? What does programming look 

like? Why is this the right way to interact with the problem domain?_ 



A "program" would be a breakdown of a map, with tile patterns specified for each area, potentially how the tiling should be aligned, and with any objects to be layered over this.



### Operation (semantics)

_What might happen when a program runs? How does a program interact with the

user? What kinds of errors might occur, and how might they be communicated to

the user?_



When the program runs, it would generate any created tiles, then repeat the patterns and use the map specifications to create each piece, then stitch them together and output an image.

If any area is left blank, it should probably color it in with an obnoxiously bright color so the user knows to cover that area.



### Expressiveness

_What should be easy to do in this language? What should be possible, but

difficult? What should be impossible or very difficult?_



This all depends on constraints. Resizing things may prove difficult.



### Related work

_Are there any other DSLs in this domain? If not, describe how you know there

aren't and conjecture why not. If so, describe them and provide links. How well 

do they address the need? Are there any particularly admirable qualities of the

language? Are there parts of the language you think could be improved?_



There are loads of RPG mapmakers. Most of them have pre-defined tile sizes, but with enough searching it may be possible to find one that has this behavior; however, overall they give game developers enough tools to succeed. 



## The Project

This section examines whether the idea makes for a good CS 111 project.



This is probably too big an idea to actually pull off, but parts of it might get done. I'm also not sure if it's enough of a simulation language to be considered a good DSL.



### Suitability

_If someone were to work on this project, what percentage of their time would be

spent directly engaging in the **language** aspects of this project (e.g.,

making language design decisions), as opposed to "systems" aspects of the

project (e.g., implementing a complicated semantics that doesn't require a lot

of language design)?_



Well, the "words" would be the map areas and the tiles. How these areas are populated would be a design decision; perhaps if a tile is bigger than an area, the user should be able to specify where the cutoff is; likewise, maybe they should be allowed to "move around" the tiling once the region is populated. In that case, would it still be a DSL? Is this enough of a language design?



### Scope

_How big an idea is this? How ambitious is this project?_



This is fairly ambitious. Having tiles input rather than allowing them to be made would probably help to scale it down to an attainable region.



### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea 

project?_



This is sort of like a simulation and sort of like a creativity language. It's also useful and might be fun to use. But, it might not be enough of a DSL, and there may be something out there like this already.

