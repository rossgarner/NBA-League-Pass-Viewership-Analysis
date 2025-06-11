![image](https://github.com/user-attachments/assets/39c3435f-12da-4a14-b36e-272e4b00b0a4)# NBA-League-Pass-Viewership-Analysis

#This was an experiment of running data analysis and data science tasks in python from NBA viewership data with Microsoft Copilot

#1 Start by prompting copilot what is the best way to ask for its help - use copilot as a teammate, not a tool is a phrase I've heard lots about in this AI explosion


![image](https://github.com/user-attachments/assets/17f95743-255a-4197-a15f-a65569696272)

#upload the excel sheet - which was pulled from Snowflake database and ask copilot to summarize key trends
![image](https://github.com/user-attachments/assets/12dc98b6-0c01-4c7c-a8f1-36fcd40ef920)
![image](https://github.com/user-attachments/assets/3ecc0fb6-3aee-4797-a9e3-06da671216a0)
![image](https://github.com/user-attachments/assets/8f87e297-be96-44b6-9330-db7258641838)

#Since copilot doesn't have business context, we need to ask it to calculate a specific metric from the data which we use for better measurement
![image](https://github.com/user-attachments/assets/b04805fc-ab22-4e70-845e-2239047a9b5d)
![image](https://github.com/user-attachments/assets/a9ec1fa6-505a-448e-bb00-f4a15c3f5dc7)

#Copilot can produce a report in any format and include visualizations as well
![image](https://github.com/user-attachments/assets/207d7758-72b1-4ea3-ac44-e1b5fdeadd64)

#Once we see the charts we notice a problem that we don't like - Copilot has coded all the charts in matplotlib! Luckily we know how to write python and we could either ask for the source code to change it, or we can just ask python to change it to seaborn to make it nicer
![image](https://github.com/user-attachments/assets/5e5e62d4-cfb5-4123-be83-f3835959f86b)
![image](https://github.com/user-attachments/assets/3827d49f-2c16-4ebe-96f9-e07cfece59ba)

#This looks much nicer now
![image](https://github.com/user-attachments/assets/21f9837b-450e-47bb-b6ba-eba297affbac)

#Next we ask copilot to perform EDA (sort of already did with trend analysis), but we also ask it to suggest some statistical analysis based on the dataset
![image](https://github.com/user-attachments/assets/a40f22ea-ecce-4153-9a25-ce843f00f22e)
![image](https://github.com/user-attachments/assets/a1c2eb4d-b66f-4b55-bbda-f82d402eceef)
![image](https://github.com/user-attachments/assets/25d78260-1531-4474-8be8-0f4cb6416f04)

#Let's focus on hypothesis testing and clustering for now - I ran into some issues with regression prompting that I need to figure out


#Copilot identifies that viewership is statistically significant difference between regular season and playoffs - which we know intuitively this to be the case but now we can prove it with statistics, that's cool
![image](https://github.com/user-attachments/assets/1c5e06fd-ec9b-4df0-b3c2-4111aa32f209)

#Copilot also identifies clusters of different levels of excitment of game play
![image](https://github.com/user-attachments/assets/e4bec212-cb60-41eb-b9f5-d48e75fed9a0)

#Again we ask for some visualizations - we could be really specific, we could let it decide, or we could ask for the code and edit ourselves
![image](https://github.com/user-attachments/assets/c9bf246b-7115-49eb-b891-ac2187db6a5b)
![image](https://github.com/user-attachments/assets/8a4cb20a-5a8a-4620-bdec-b6e147dafc26)

#We also ask it to include summary and recommendations to help pitch our analysis to our stakeholders lol
![image](https://github.com/user-attachments/assets/6ffd7343-992f-4b60-8de5-a6d053374653)
![image](https://github.com/user-attachments/assets/bb9db801-9f48-44d6-95b7-0f159dfdbc63)


#so what did we learn?
#Seems copilot is pretty good at data analysis on it's own without much input and asking it for recommendations on what to do
#we still have control over each aspect and can always edit the source code or tell it what to change
#we also have all the busines logic and context, which I'm not sure AI can ever get in this current phase until it becomes integrated across all our tech stack for every process and function
#But this took all of 10mins to produce, so yes, this does seem to produce productivty - but does it replace data analysts? Well, let's see, this was sort of me directing a junior to produce what I want. Which is sometimes needed, but having juniors or analysts also helps shape your thinking as the overall business owner. We need diversity of ideas etc. 
