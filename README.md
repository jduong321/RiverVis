# River Visualization

Problem: Geologist face an issue of knowing how rivers change based on their pools and riffles. The issue is that they do cannot fully identify what is a pool or a riffle based on the information they gathered. Another issue was they wanted to know if these pools and riffles were symmertrical or not.

Approach: Our group decided to create a trendline that would be used to identify the pools and riffles. The idea was to minimize the number of peaks so we could ignore two small peaks as a pool and such. The way we identify if the pools and riffles were symmertrical was by calculating the slopes of when the river was rising or falling. The goal here is to compare the two pairs of blue and red lines at the bottom to check length difference. The idea is if the bars at the bottom are similar lengths, then they are more symmetrical which you can easily confirm by looking at the above line graph.

Contribution: Using D3.js I handled how the transitions between different rivers were handled. This involved reading the JSON files of the different rivers and creating the bar graph. 

