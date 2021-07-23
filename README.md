# ML_insurance_risk_rates 
Project in machine learning to determine structure risk and insurance premium rates within various magnitdue parameters
This project suffers from two issues afte much research and analysis. While it isn't very difficult to make a simple machine learning classification model based on valid and extensive research which I have done, what your really producing is a categorical filter with no way to prove that your accuracy means anything.  If you did three classes of RED (high risk), YELLOW (mid risk) and (GREEN) low risk, there is no reason to call if machine learning. It's simply a filter based on a scoring system which I can just do in Excel.  
There are no databases or sets of databases that exist or even could exist in theory that could learn how to classify a building's individual earthquake risk with any meaningful accuracy.
For example, I can tell you, based on my own research, that if you live on landfill, in a 2-4 story building, on a slope, in a brick house, built before 1940, in San Francicso your earthquake risk is extremely high or VERY RED.   And I can write some code that will tell you that as well.  How did I come to that conclusion? 
1. San Francisco is close to major faults (proximity to fault)
2. Landfill is the worst soil type for earthquakes
3. 2-4 Story buildings have historically perforemed very badly in earthquakes in California because of the Strike-Slip fault system in the state which produces Love waves as opposed to a place like Japan where the subduction zone style earthquakes produces seismic waveforms that are much different. Called, Raleigh waves, they are more hazerdous for skyscrapers than for 2-4 story buildings like in California. The are long, rolling waves like the ocean and the earthquake, i.e., the part you can feel and does damage, the intense part, can last severl many minutes.  In contrast, Love waves in California are short and choppy like if you were shaking a carton of orage juice and the earthquakes lasts a minute or less (intense shaking).  So skyscrapers actally perform better in California for that reason.
4. Brick is a historically bad perfomer when it comes to quakes.
5. Homes built before 1940 are several generations of building code updates behind
6. Homes on a slope with poor soiltype are prone to landslides

There it is, you have the worst type of house for an earthquake. We know this from history.  However, there are no data sets or combination of datasets that can tell you anything more than what I just did.  I can make a scoring system based on research but then I am accused of using "dummy" data.  Historical reserach is not dummy data.  It's better than any numerical data out there for this topic.  

There are major problems with the idea that math can answer all the questions or at least can answer questions better than extensive hands on human resarch. In an effort to find answers faster, or "more efficietnly", we're likely to come up with a lot of wrong answers.  

Machine learning can not give an accurate, meaningful, and non lethal classification to a structures earthquake risk. It can't "learn" this.  Only a human can.  That doesn't mean that data analysis isn't useful here, it is EXTREMELY important.  Afterall, what is historical research but the analysis of information or data?  But in cases such as these, there are TOO MANY VARIABLES AND TOO MANY UNKNOWNS for machine "learning" to do us any good at the scale of an individual property.  There are just genralizations and I can do that myself.  

Yes the program correctly classified this house as one with VERY HIGH risk.  Just like it was trained to.  But guess what? Turns out model was wrong. Very wrong. A human came out and did an assessment of the property and, unbenownst to the current owner, the house's foundation had been retrofitted with pilons driven down to bedrock.  Turns out this is the safest house in the entire distict. "Good news! Your house just went from VERY HIGH risk to EXTREMELY SAFE. Someone must have made a data entry error in the county records cuz it isn't in the database... probably use space instead of an underscore.  Good thing you called a human."

I hope this was a fun story.  But image if it had been the reverse?  A house with all the top ratings in build type (wood and steel blend), no slope, on bedrock, only a decade old, 6 stories instead of the dreaded 2-4, everything looks great.  Building is deemed EXTREMELY SAFE.  Inspector comes out and says, "I have it in the county records that this 6 story super condo you're living in is on bedrock."  "yes sir."  "Well, I don't know where that information came from but you're on landfill. And there's already a bit of a sinking in the northwest corner. If an earthquake hits, this structure will likely collapse. Have a nice day."

And that is why I chose to do a movie and a map instead.

Thank you for your time.  Here is the Cracking California Project.  It's pretty neat.  Enjoy!
https://ripetimes.press/cracking-california-earthquake-project




