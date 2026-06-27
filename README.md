pif20 documentation - 18/05/2026 - dmac

welcome to your home for the next 7 days. this is mostly intended for pif21-23, but please refer to this as needed as the project evolves. 


this will only take 5 minutes to read. the reason i have spent so much time typing this all out is because i have become very passionate about the project during the last week, and want to see pif succeed. hopefully you will too once you start. 


... and you will soon realise that everything is locked behind prefabs. 


firstly, ask yourself the following question, and read the document carefully, as the future of pif is in your hands!


IS THIS A NEW CONCEPT TO ME? 

if yes :: please read SECTION 1 very carefully, and take some time to get familiar with the tools. dont worry about making mistakes, they are nothing to be scared of.
if no :: please disregard SECTION 1, however, i strongly urge you to read SECTION 2, as you are likely to be interested.



SECTION 1 is a condensed summary on what you need to know before you start, and the changes i have made to how the project structure. this is necessary as you will likely soon find out.

SECTION 2 is a more formal/fleshed out breakdown. it explains what i planned to achieve before the i started working, and how my changes will help the project sustain its identity from early versions, and hopefully help carry it toward the final stages where it will begin to get extremely complex.

***i urge you to read section 2 if you are passionate about the future of the project, however it is not necessary to get started in pif***


-- -- -- -- --

SECTION 1:

it is important that you understand how to navigate a hammer project using prefabs, and have a basic understanding of what an 'instance' is and what they are used for. they are nothing to be scared of. i dont have the capacity right now to explain through text, so i urge you to reach out to me on discord (dmac007, the dirty harry picture guy) if this is new to you. if you need any clarification, im happy to have a call at some point, but probably not the for next 12 hours after i finish typing this. your boy needs his sleep real bad. here are some resources for the meantime if you need.

- prefabs
prefabs (prefabrication) behave like a map within a map. they are the bread and butter to a team project where files are shared, much like pif! valve uses them extensively in their half-life alyx projects, and it makes sense to use them in a project with as many people as pif.

- instances
eagleone-devteam has an excellent 5 min crash-course that explains what they are, why they are useful, and why they can be extremely powerful for large-scale projects. valve covers them more extensively on their devpages if you would like to explore.

https://www.youtube.com/watch?v=14eqVvuCDk0
https://developer.valvesoftware.com/wiki/Source_2/Docs/Level_Design/Prefabs_and_Instances
https://developer.valvesoftware.com/wiki/Working_with_instances

again, please feel free to reach out to anyone in the pif server if there are any issues :)

-- -- -- -- -- 

SECTION 2:

-- -- -- -- -- 

note: written in mixed-tense as a way for me to document and plan before starting PIF20 - disregard grammar pls. 

I think it's fair to mark Week 20 as a milestone point in the PIF timeline, and I have fleshed out x2 Key-Aims I have focused on during my week:

1) Restructure A-site and its connecting paths/corridors;
I think there's alot of room for improvement regarding cover & prop placement,
I think there is a lack of purpose and direction for what the area 'wants to be',
I have a-lot of pre-made and recycled assets from other projects that I think can help give it a sense of identity.

2) Organise the framework meshes in a way that allows modularity for final layout decisions, and aims for consistent deliverables in anticipation of an individual room-by-room art-pass;

I begin by reconstructing the existing PIF map framework by first addressing clear topology errors, apply room-building methods used by Valve (see example .vmaps in the HL:A editor) by separating the now modified framework into distinct elements (floor/pathing, walls, ceiling/roof/sky) as separate map prefabs. Objects already existing within each cordoned room will be copied in as necessary (tool brushes/entities and reference objects) with arted objects (props, cover, detailing) only added on a case-by-case basis to help maintain the base-layer for future work.

As discussed by the organisers, the complexity and ambiguity of the project makes a unified direction and process impossible, therefore a loose but clear structure of the map is needed in order for the project to be digestible for future handovers and maintain continuity throughout the level toward the final stages of the project.

Given; I have a-lot of free time to dedicate toward PIF over the next week, I have a strength in organising things, and this is an key milestone in the project timeline, I want to preserve the work that the previous 19 PIF-ers have left for me, do my part the best I can, and Pass It Forward for the next 22 weeks of designers/artists to do some truely great work. I believe that PIF will succeed and will be something really special that we can all be proud of and learn something from.

As a precaution for any confusion, I must emphasise that the structuring that comes from my week is not concrete and should not be interpreted as rules, but are instead intended to behave more like guidelines to help keep the project on track and hopefully maintain some form of structure once it becomes quite complex in the later weeks.

This structure should hopefully allow the diverse range of visions and art-styles from each future designer/artist to breathe freely, whilst also inversely gently guiding PIF back to its original intended flow in a balanced and fair way to everybody in the project.

Naturally, I anticipate that most of what currently exists will morph into something unrecognisable but beautiful. I trust and hope that when the time is right (presumably the next milestone ~week 40), someone will undertake a similar responsibility and help structure the project in a way that it can succeed in its final stages before its completion.

To summarise; I've tried to be vague with how I've defined my aims, especially my second point, due to the ambiguity of PIF and the diverse range of designers/artists that will spend their time here. I hope that the time I've spent organising the map into a room-by-room approach will (a) help with some form of consistency and flow as each section is arted, (b) make alot of the 'grunt' work in the later technical (VIS, collision, optimisation) stages less overwhelming and (c) aid in preserving the original vision of the project. 

Wordy and boring, but probably a necessary step to help get PIF moving from something cool toward something EPIC! With my best wishes from Australia -dmac ❤️ 


