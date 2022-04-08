# PowerBi-Projects

Hello there ,

I created a dashboard for SpaceX Launches .  Space Exploration Technologies Corp. is an American aerospace manufacturer, a provider of space transportation services, and a communications corporation headquartered in Hawthorne, California.

Dataset Source :  https://lnkd.in/ef7tamyu

On top it has slicers for the “Customer Nationality ” ,“Payload Customer ”, “Payload Manufacturer ”, “Launch Site” , then it has a Table mentioning the Mission Names and Mission Patches (converted to Image URL). Hovering over the table gives details about the mission .
Adjacent to the table are three doughnut charts based on the `Launch Success’ , `Landing Success’ and the `Rocket Name’ valued based on the number of count of flights .
The Rocket Type/Engine are represented in a clustered bar chart also based on the count of the number of flights .

Features:
1. Used Chiclet Slicer for Payload Manufacturer , Payload Customer  and Launch Year
2. Used Custom Visual to represented each country with their respective flags .
3. Visual Background =  The background is an image used as a wallpaper with transparency set to 13% .
4. Hovering over the table gives details about the mission similarly hovering over map gives images of the launch site .   
5. Used ‘Filter’ instead of ‘Highlight’ Interactions for all Visuals

Data Cleaning & Transforming:
1. Expanded the first and second stage cores from Lists to Records to Adding data as new rows
2. Made separate tables for first and second stages and bridged them using flights numbers .
3. Added Column with Image URL's to for Rocket Name images and Launch Site images

Important Takeaways while building Dashboard:
1. “First analyze, then tantalize”
2. Keeping the background associated to the data really sets the stage and mood for the viewer .
