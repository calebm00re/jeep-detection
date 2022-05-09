# jeep-detection

### Use Case
It is common practice for those driving jeep wranglers to wave at others driving the same vehicle. Driving my wrangler, I participate in this, but it is the 
absolute worst when I pass a jeep that waves at me and I forget to return the favor. My idea for this project is to use open CV to make jeep wrangler detector that
can let me know when a Jeeo is coming, so I can remember to wave. While I do not intend on integrating this into any sort of dashcam, that would be the theoretical 
future implementation.


### Current state
It is recognizing vehicles from about the proper distance I would use to detect oncoming jeeps or those at a similar distance. In the future I would need to do more negative training, but it also works on trails or sand dunes as well for detecting vehicles and specifically jeeps. You can tell from the following images that it has a fair amount of false positives, and thus requires further and more specialized training sets.
<img width="460" alt="Screen Shot 2022-05-08 at 10 44 01 PM" src="https://user-images.githubusercontent.com/72896477/167337308-284e043c-4873-43c0-a9ea-d9c75fda55bd.png">
<img width="490" alt="Screen Shot 2022-05-08 at 10 45 12 PM" src="https://user-images.githubusercontent.com/72896477/167337300-8951fc0a-4b8a-4b14-b7aa-63c3fc47bff6.png">
<img width="491" alt="Screen Shot 2022-05-08 at 10 44 19 PM" src="https://user-images.githubusercontent.com/72896477/167337319-f7e19628-3661-4040-b62c-37beca3137fd.png">
<img width="489" alt="Screen Shot 2022-05-08 at 10 44 53 PM" src="https://user-images.githubusercontent.com/72896477/167337374-0744d6d2-f39d-4325-9303-bc3793d7236e.png">



### What I learned
Open CV is extremely powerful. However, it is far easier to do things with faces, as there is a lot of data and .xml files for training these systems to work relative to faces. There is, unfortunately, far less available data on making this work well with vehicles. In the end, I am glad I could accomplish some small level of vehicle recognition, but in the future, I would need to dive more into the actual training. This would allow me to enure it only recognizes jeeps by negative training out other car shapes.
