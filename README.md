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

HOWEVER... as long as the homeowner knows the specifics of their home, one should be able to write a machine learning algorithm that works for that informed homeowner.  I am still working on this.  I have lots of research on the history and have done serious research on KNN v Random Forest methods.  I think a Random Forest classification system is the way to go.  I would love help!  

Right now I have a short video and a user friendly map to learn about CA earthquakes made with Google Maps.

I LOOK FORWARD TO DEVELOPING THE MACHINE LEARNING ASPECT!  I have lots and lots of research so that is already done!

PLEASE EMAIL IF YOU ARE INERESTED IN HELPING!!! 

ryanlouderback@gmail.com

Thank you for your time.  Here is the Cracking California Project.  It's pretty neat (but we can make it better together!).  Enjoy!
https://ripetimes.press/cracking-california-earthquake-project. (Rhis is the foundation.)




The Big Picture

Cracking California with the Shake Love Model
A New Class In Determining Earthquake Insurance Risk For The Consumer
A Research Paper and Application Overview 

Synopsis
Cracking California with the Shake Love Model is a project meant to engage, inform, and, if applicable, initiate action from the user who is interested in learning more about insuring their property by using a multi pronged media platform.  This platform includes a short film, website, and interactive map as well as graphs for relevant data.  The risk assessment portion is a machine learning model that assesses a residential structure’s earthquake risk (this last piece is still in development and I am happy to work with someone more familiar with machine learning at this level to advance the project). 

Where is the BIG Data?
Unfortunately, or perhaps fortunately for the residents of California, earthquakes large enough to do serious damage don’t happen that often, even in California, which is pretty seismically active.  When they do, they are catastrophic. But unlike the auto insurance industry, a serious earthquake in a populated area does not occur hundreds of times a day but rather once a decade or even a generation.  When they do hit, most of the data that can be kept private is kept private.  This is proprietary information and the insurance companies are in no rush to share it.  Yes we have the geo data from the USGS and clothes, but insurance companies have no incentive to make their data public. 

As for using data from countries like Japan, it is actually fairly useless.  That is because Japan has Raleigh waves which can take down skyscrapers but are much safer for smaller buildings and that is due to their subduction zone induced earthquakes.  This is in contrast to California which has Love waves from the Strike-Slip fault system which is most dangerous for buildings 2-4 stories high. 


Measurable Objectives
This project is based on research which informs a classification style machine learning model that will do the following.
1. Determine the overall damage risk for a property of user interest by weighing a number of relevant features to classify the property as “High”, “Mid”, or “Low Risk”.  These features and their weight are based on extensive research.
2. Apply the output from the first objective to inform the user of the accumulation of risk for the property over the span of a normal mortgage (30 years).
3. Using Google Maps as the base, construct an engaging and informative interactive and layered map with information relevant to a user interested in, among other things, earthquake insurance.
4. Design the map so that a user that is interested in earthquake insurance will be able to easily learn about their area(s) of interest and take meaningful action such as clicking on a link to learn more about earthquake insurance from an appropriate authority.


Phases
Planning & Research / Extract Transform Load  / Data Analysis / Machine Learning Training and Testing / Machine Learning: Enhancing the Model / Visualizing the Results

The project was split into 6 phases: 

Phase 1 Research:  Phase 1 concentrated on planning the project, considering what measurable objectives could be achieved in the given time frame.  Research into Machine Learning as well as seismology, structural engineering, and other related areas were concurrent and this approach has seemed useful.  Admittedly, there has been some jumping between phases as the need to better understand machine learning made it necessary to take small sample sets of early data and run them through the ML process to better determine what was needed as well as what ML model to choose.  Additionally, the project’s scope had to be narrowed from starting with California to choosing to major cities within the state. One must keep in mind that California is, both in terms of population and geography, the size of many European nations, and to attempt an accurate Machine Learning model on such scale given the time allowed would have been highly unlikely.  Thus, San Francisco and Los Angeles were chosen to narrow the scope in the interest of obtaining more accurate Machine Learning results. 

Phase 2-4 Extract, Transform, Load (ETL):  

The 2nd phase was the extraction, transformation, and loading of numerical data into a server.   Data from the USGS and its partnering institutions’ databases was extracted, transformed, and loaded into a PostgreSQL server using PGAdmin. Here, the numerical data could be easily sorted and cleaned not only for my own research and understanding but also so that models and visualization of this data could be undertaken at a later stage.  During the phase, the data was transformed in order to meet the goals of the project which included the dropping of extraneous columns, reformatting date and time when necessary, and creating new tables specifically designed to meet the objectives of this particular project.

Phase 5 Data Analysis: The truth is that the analysis of data was occurring in some manner at every stage leading up to Phase 4. However, it was in this phase that I was able to really nail down what it was that I had, and how it was to be used in the Shake Love ML model.   The relationships between the variables of building type, building damage level, earthquake intensity, region, distance from epicenter, the role of retrofitting, soil type/ liquefaction, and building eras all came together in a way that made sense in this phase.  Now that I could better understand the relationships, I positioned myself for better results with the Shake Love Machine Learning model.  For me, all these steps were crucial in order to train and test the classification model I knew I needed to use and achieve accurate and meaningful results with real world applicability. 

Phase 6 Machine Learning Training:  I knew I wanted to develop a prototype earthquake risk and damage casualty estimation model based on classifications.  Using two classification methods I have begun to practice with models based on the extensive research.  I have tried both Random Forest and KNN models.  This training is ongoing. 

Phase 7 Machine Learning Improvement:  (In Progress)

Phase 8 Data Visualization:  (see map here)

