# 5-Day AI Agents Intensive #  

the “Introduction to Agents” whitepaper.
archtecture of autonomous, goal oriented AI agents (plan, act, solve complex problems over multiple steps)

**agent anatomy**  
1.model (brain): reasoning engine, managing context (constatnly deciding what's important right now from mission, memory and tools just did, decide what input matters for the next thought process. model reasons about which tool is needed for the current step in its plan

2.tool (hands): the connections to the outside world or internal systems (APIs, code funcs, ways to access DBs, vector stores, look up customer data and check inventory)

3.orchestration layer (conductor pulling it all together): the governor of the whole process. it manages the operational loop(plannning, keeping track of the memory or state and executing the reasoning strategy, chain of though or react.React blends reasoing and acting),  The orchetration layers actually calls that tool and the result gets fed straight back into the model's context ready for the next cycle of thought. 

**loop**   
get the mission, 
select relevent tool from memory, 
brain decide what is important; 
take action: orchestration layter call the tool; 
observe and iterate

**agent capability**  
level 0 - language model on its own(no tool, it only knowns what it was trained on. it can tell you about history, it's cut off from the present)  
level 1 - conntect problem solver, connect the reasoning engine to tools/world. it has real time awareness.  
level 2 - strategic problem solver.   
Moving beyond single simple tasks to more complex multi-part goals.   context enginining, the agent gets smart about crafting the input for each step, such as find a good   coffee shop halfway between two addresses(map tool, place search api), using the output of one step to   intelligently shape the input for the next step. Maning the context to get better an dmore relevant   results and avoid noise.   
level 3 - collaborative multi-agents system(agent to agent goal delegation).   
Agents start treating other agents as tools (call their APIs). How is it different from callling a complex function? The difference is often the autonomy of the agent being called.   
level 4 - the self-evolving system.   
The system can identify gaps in its own capabilities and it can take steps to fix it. it might invoke an agent creator tool to actually bild a new needed agent on the fly and config access permissions and everthing, it is adapting and expanding its own toolkit.  







