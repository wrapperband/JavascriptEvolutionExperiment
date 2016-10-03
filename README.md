# JavascriptEvolutionExperiment
An evolution simulator created in JavaScript. The entities use neural networks created using a genetic algorithm.

https://www.youtube.com/watch?v=6rRRvRlWY4w


Original : An evolution simulator created in JavaScript. The entities use neural networks created using a genetic algorithm.

John Hess

http://h3ss.com/evolution/

Modified the original code of John Hess's Evolution simulator, with more "creatures" and bigger brains. Took 96 hours for them to learn to eat  the food, (very slow). The video shows development at 150 hours. 

Note that left hand circles seem to be the current best strategy to  get food at this stage and none of the creatures cross the boundary at the edge of screen, even though they can tel-port ..

It should be noted the first time it was run it only took 48 hours for the bigger brains to find the food, so you might have more luck starting a couple.

In the experiments with https://github.com/wrapperband/JavascriptEvolutionExperiment and creating larger brains, I found that it took longer to evolve skills.

Here is and example skills and evolve time for a large brain 6 neurons 7 layers.

The first skill learned was go forward  ( repeated starts (20) until some creatures move)
Find Food 5 hours
Wait while no food is available 5 hours
Turn Right and left 100 hours
Find "lines of food" 150 hours
Deliberately target centre of food - 150 hours
Move away from other creatures if food scarce - not found
Move towards larger food when 2 are available - not found
scan for food - not found
Look behind them selves - not found


