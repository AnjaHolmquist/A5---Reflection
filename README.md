# Our reflection report

# 1) Process of developing the tool 

## Did the process of the course enable you to answer or define questions that you might need later for thesis? 

### Anja
Yes, it has, because before we started this course, I thought it was something completely different we came in to, so I was not prepared for learning to program. But having said that, it has been a very educational process, and I feel that I come out with some tools that can help me in the future in the idea of developing the construction management process. 

We chose a use case that was obvious to us as future contractors, to be able to optimize the time on how to get the quantities out of the model to be able to give a good and fair price estimate to the developer when the project is put out to tender. 

### Rene
Without the course process, the final product would not have been usable, so yes, the course processes have definitely prepared one to produce a satisfactory handover report. 
Without knowledge of ISO 19650 and the importance of its use, a task of this type would not be possible to carry out. the course has given a basic knowledge of the industry's deficient descriptions and different working modes. 
The process has clarified how much the construction industry needs BIM to be organized and optimize the various processes. 
After I have done a work placement with a concrete contractor, I have tried on my own to calculate a given quantity of concrete, after which that quantity must be ordered from a third party, where the result has been wrong. Here, I have experienced how many problems it can cause even if you have carried out thorough and well-worked calculations 
Primarily this has meant that we in the group have focused on the importance of quick and accurate quantity calculation 

### Vahid
Prior to taking this course, I did not fully see the significance of the architect-engineer relationship. The training taught me the importance of teamwork and communication between engineers and architects. In addition, I have realized that programs such as Python, HTLM, Pandas, etc. make work simpler, less time-consuming, and less expensive. I have learned via a few missteps the need of exact and precise computations. However, it is also easier for the worker to locate certain topics inside the applications, resulting in increased productivity. 
After utilizing BIM, I have realized that the process of finishing a project is not linear. There are several control points, inputs, outputs, computations, and interactions with other team members. In addition, I have gained familiarity with ISO 19650, which will be valuable for my thesis and future work.

## Would you have preferred to have been given less choice in the use cases?

### Anja
It was very confusing when we were presented with all these options, but since we are also a very mixed group of students, with different interests, it still makes sense that you can choose something within your area of interest. in our group we started thinking we should work with structures as we come from Building Technology and Constructions in Ballerup. but after our first draft of the use case which was to do static calculations via blender, we had to admit that we did not have the skills for this as none of us have tried to work with scripting before. Therefore, we changed our choice of use case to Cost as we are already working with student help at the construction company NCC, so we could use the problems from here with booking of materials such as concrete quantities for each casting. 

### Rene
I definitely think that it has been a great advantage for us to have had so much freedom to come up with a use case ourselves. 
In this way it has been possible to bring one's own professional problems into the case, this has made the case one's own and the ownership has forced one to think more than if the case had been more locked from your side. 

### Vahid
Due to the extent of our independence, we were first all quite overwhelmed. There was no clear direction, and a few further instructions would have been appreciated. On the other hand, being required to maintain an open mind and generate your own thoughts was really educational. The work was built on trial and error since we attempted to work with static calculation using blender, but ultimately opted to work with Cost because it was better in line with our group's expertise. This procedure has also piqued my interest in the Python programming language, which I would like to master.

## Was the number of tools for the course ok - should we have more or less? 

### Anja
Overall, this course has over all been really good, but since I come from a study line where we have never programmed before, I have spent a lot of energy on understanding how it works. Therefore, I could have used some smaller video tutorials, and assignments to learn how to make sure we start correctly in the scripting. 
In addition, it would have been helpful to know about Visual Studio from the start because the way it sets up the script is much more manageable than in Notepad++, which none of the assistant teachers could figure out how to use.   
So a good idea would be that you as teachers and TA's agree on which platform to use so you don't feel completely lost when you are completely new to this programming world.

- If so which ones would you leave out? 
I don't think you should opt out of some of them, and it would be a nice exercise to talk about the different cases in groups and thus put into words what they entail and what you can do with them. 

### Rene
for me, this course has been a proper introduction to completely new programs and the world of programming. so whether there have been too many tools,? I probably didn't think so since  

- if so which ones would you leave out? 
I find it satisfying to know about the various tools and have the opportunity to tinker with it myself and choose how it suits me best 

### Vahid
Since every member of my team comes from the building construction industry, we have limited familiarity with coding. Therefore, it took us a very long time to figure things out, and it was often rather challenging. I believe a more concise and understandable introduction to the programs would have been beneficial. Having said that, I am pleased with how much I have learned about coding, and this course provided me with a solid understanding of the various tools.

# 2) Output of the tool 

## did the tool address the use case you identified? 

### Anja
I think that we in our group have got a really nice and useful product out of our task, our wish was initially to continue on the website so that when you clicked on the floor to the left, and then it would show the information on the external walls of the level, in the box to the right.  
But since none of us have any experience in creating websites, Ann-Britt came up with the amazing idea, to export this information on the walls to an Excel sheet, and since this format is one of the most used in the construction industry, it makes a lot of sense. And from there, we chose to implement Molio's price book in order to make a direct price estimate that the developer can use as a starting point for the project and in addition that this sheet is sent to tender so that the contractor can give their price for making the project and thus have something to compare the prices with.  

On this idea we got some good feedback from the Niras boys, who stopped by our group and talked to us about our case, they could see the potential in this way of making material extractions and price estimates, because it will also be able to be carried forward directly to the schedule. 

### Rene
I definitely think that this tool addresses our use case. we have been looking for a tool that could quickly and easily tell the different quantities of the respective building parts.  
To start with, our desire was to perform our use case for an HTML forum but chose to stay in a format we were more familiar with, Excel. in the excel we get information on specific building parts and merge it with Molio's price book, which fulfils our initial wish. 

### Vahid
We imported the IFC model (openschell) into the Visual Studio code, executed the code, and located the desired model components. Using pandas, they were exported to Excel. Additionally, we loaded js on data (molio) into the application, which produced wall-specific information and multiplied it with the js on data. This resulted in a material price with the appropriate units. This is briefly described.
However, we initially encountered tremendous trouble with the tool. We received a great deal of assistance from the student assistants, who advised utilizing pandas and creating an Excel spreadsheet that displays volume, price, unit, and price for the subjects in which we were interested.

## Was the use case well modelled 
### Anja
I think we made a good and clear excel sheet with the necessary information, had we had more time we would probably have developed a little more on the setup and added more building parts so we could make a total price estimate on the load-bearing structure. 

### Rene
I think it is well modeled. our result for our tool gives a quick and precise description of the building parts and times the cost price from molio, which gives a realistic picture of a price both for the execution part and the material. a tool that could practically be taken out into reality and used in small projects. 

### Vahid
Despite initial difficulties, the tool was able to address our issue. We received a great deal of assistance from the student assistants, who advised utilizing pandas and creating an Excel spreadsheet that displays volume, price, unit, and price for the topics in which we had an interest.
was the project clearly 

## was the project clearly scoped 
### Anja
Several times during the process we had to delimit our project as we thought too big in relation to what was realistic for us, but all in all we have come to the conclusion that good product that I feel can be useful. 

### Rene
whether the project has been clearly scoped from the start is, of course, another question. because I thought that after you gained more and more knowledge in the course, we changed our scope continuously as we acquired new knowledge about programming, and perhaps became more realistic in relation to our abilities. at the start of the course, the scope was reasonably small, but it quickly turned into far too extensive, where, in tandem with the knowledge learning course, we were able to adjust the scope to a realistic and meaningful product.

### Vahid
Throughout this endeavor, we employed the hermeneutic technique. As we gathered more information and expertise, we altered the scope of our project until we achieved a conclusion. There are likely still many improvements we can make to our product, but the final version is still effective and helpful. The application is wonderful and will be extremely beneficial in the future; nevertheless, we lacked sufficient experience. We were a group of three, and each of us had different talents, such as programming and management, so we taught each other and worked together to solve the challenges.

# 3) Future 

## Are you likely to use OpenBIM tools in your thesis 

### Anja
In my upcoming exams it is not possible to use open BIM as we do not work with some models in other subjects this semester. but maybe the next semester when I have to write a final project about project management on an ongoing construction project in Herlev. 

### Rene
it will clearly be smaller parts that I will use in the future, the importance of a uniform and clear description of building parts and how important common naming is. 

### Vahid
Since Python is my primary interest, I'll likely utilize OpenBIM. I find the software to be quite beneficial, and I intend to get even better at it. Additionally, the IFC model is simple to open in many applications and examine from various perspectives. I am extremely interested in the curriculum if I want to work in VDC (Virtual Design and Construction) since I believe that python and coding make many tasks easier and enhance worker communication.

## Are you likely to use OpenBIM tools in your professsional life in the next 10 years? 

### Anja
Open BIM is definitely something I think can be useful in my future as a contractor when extracting quantities, making price estimates and time schedules. 
But this will clearly be most useful if you get a standard in how models should be modeled and named with the different building parts because then you would be able to use these scripts again on other cases and in that way it would be a huge time optimization. 

### Rene
I think 100% that I will use forms of OpenBIM and hopefully have opportunities to be an active role in getting it used in small and medium sized companies, I didn't think that the full potential of openBIM is clarified and visualized for the wider industry  yet, at least not as widespread as it should be. I may have had a hunch that reality has a lot of difficulty in adopting the new technologists, so if you are unsure about your area, the chief executive would not accept a tool offered, and you really have to be sharp to convince future managers of the importance of undeveloped tools 

### Vahid
As an engineer, I anticipate using OpenBIM in the future. I am confident that it will improve both collaboration and performance on construction projects. I believe it has a bright future and will become extremely widespread and worldwide, thus familiarizing oneself with it is essential.

# 4) Feedback from the Cost groups (Gr. 1, 2 and 19)
- Good video, it describes the usecase and want you have made and how the contractors can use it for defirent purposes.
- how did you make that voice thing?
- it is a godt way to du is for each element part so the contractors can see all the informations for the elements.
- How did you get the JSON file to work?
- is it possibele to use this script for other buildingparts such as slabs, beams culomns ??
- it could be nice with a total price.

# 5) good advices for next semesters students.
- Choose your platform early on.
- Excell is a good way of processing data for constroktion. 
- Narrow your use case and add more details later in the process (scope)
- Make a detailed code, not a broad one
- Find a way to control your results and make shure you know it all about that exact part of the building.
