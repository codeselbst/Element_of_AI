# Element_of_AI
Building_AI_Course_Project

# Context Alarm

Final project for the Building AI course

## Summary

The goal is to design "alarm" which will read through articles picking up words that may distort the truth.  


## Background

Our world is full of vast information and some of them are fake; however, there are some information which do contain the fact but partically are made to profit some organizations. It is common to see how media broadcasts same news with completely different tone. It would be hard for reader to have a general perspect of the truth. For that, a alarm that calculates the probability of the true context in articles can help readers stay more neutral. 


## How is it used?

Users simply adds this alarm when browsing through news, Then users will recieve a number in percentage indicating how many sentences in the whole articles are realted to the news. As a result, users can use it as a reference before reading it.


## Data sources and AI methods
This plugin alarm will automatically scrap articles with similar content within the past 7 days from the main public service broadcaster around the world. 
* Australian Broadcasting Corporation <img src="https://user-images.githubusercontent.com/74449345/103146301-97a27f00-478a-11eb-8e6f-09f1fdf2b82f.png" width="50"> 
* Taiwan Public Television Service Foundation<img src="https://user-images.githubusercontent.com/74449345/103146299-96715200-478a-11eb-968e-6160ab10d58d.jpg" width="50">
* British Broadcasting Corporation<img src="https://user-images.githubusercontent.com/74449345/103146302-983b1580-478a-11eb-9fc2-6f98e7fe083a.png" width="50">
* Norddeutscher Rundfunk<img src="https://user-images.githubusercontent.com/74449345/103146303-983b1580-478a-11eb-8ffa-7e1fe9e08a78.jpg" width="50">
* The Finnish Broadcasting Company,<img src="https://user-images.githubusercontent.com/74449345/103146304-98d3ac00-478a-11eb-90d5-c0452f368cbc.png" width="50">
* Czech Television<img src="https://user-images.githubusercontent.com/74449345/103146305-98d3ac00-478a-11eb-8277-4f9e39f72353.png" width="50">
* Korean Broadcasting System<img src="https://user-images.githubusercontent.com/74449345/103146306-996c4280-478a-11eb-9a29-c60e8d3d8c6c.jpg" width="50">
* Pakistan Broadcasting Corporation <img src="https://user-images.githubusercontent.com/74449345/103146307-9a04d900-478a-11eb-8e77-05de64bd2130.jpg" width="50">
* Japan Broadcasting Corporation<img src="https://user-images.githubusercontent.com/74449345/103146308-9a04d900-478a-11eb-8d96-fcf03f9f4779.png" width="50">
* Cable News Network<img src="https://user-images.githubusercontent.com/74449345/103146309-9a9d6f80-478a-11eb-8475-76422a49c11c.png" width="50">
* Canal 1<img src="https://user-images.githubusercontent.com/74449345/103146311-9b360600-478a-11eb-8418-98602693de75.png" width="50">
* Televisión Pública Argentina<img src="https://user-images.githubusercontent.com/74449345/103146312-9b360600-478a-11eb-9dfa-f204820dbbf1.png" width="50">
## Challenges

Languages should be a big issue here as the alarm will collect data from main websites and compare the similarity between them; however, during translation the result may lightly differ from the original. In other words, if the "fact" is already changed during data analysis then the purpose to use this plugin would be in vein. 

## What next?

To improve the translation function should be the priority.  It also goes without saying that more people get the true information, the better future they can expect.



