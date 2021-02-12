## Responses
Formating Readme : https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax

**Day 1** 
> I hope to gain more insight about machine learning and figure out if this is a carear path I want to dedicate myself to 

**Day 2**
> 1) Supervised learning is giving a machine specififed data with definite conclusions in order to have the machine learn from the data given. Unsupervised learning is when you give a machine data that has no "key" which requires it to learn and make conslusions on its own.
> 2) Scikit-learn is Not a visualization library. It can be used in tandem with viz libs but it was not coded to perform visualizations on its own.

**Day 3**
> 1) Tensors are used as a mathematical object to convey as many dimensions as needed in a machine learning project. When creating very models like self driving cars, tensors are required because there comes a point where the data you process is so complex, there's no way for a computer to understand it without many different dimensions of that data. You can use 5th dimensional tensors just for a simple colored video! (Imagine in 20 years what machines will be able to do with data that isn't just a video but real space) For 3d, 4d, & 5d tensors (time series, images, video respectively) we see many different usabilties. Since time series data is a form of tensor, we can make prediction models just like Quants at a big bank do. For 4d tensors we've got the typical GANs, image recognition, the basis of self-driving cars, etc. 5d gets cool because you'll be able to process video feed and figure out whatever you want. You can use it as mask detection, figuring out if you're about to get in a car crash, or maybe see how fast a baseball is moving and predict where itll go. One main feature is its able to store data systematically along with keeping structure throughout. Very Interesting!! (Took a minute to undertsand it all but very worth it)
> 2) All the outputs were in tensor form. An image wasnt an image, it was a set of numbers.

**Day 4**
> 1) I found a dataset by the company CommaAI who specializes in open-source self driving car technology. It was made by George Hotz who those in the cyber-security world know as the 17 year old who jailbroke the first Iphone. They sell kits which can turn your 2016 Honda CR-V, amongst other cars, into a Tesla Model 3 very easily. They always have a challenge going on where they take a problem they're currently facing/have already solved, and put it out to the public to figure out. People interested in landing an internship or job at CommaAI (They're always hiring) should do these challenges before even fixing your resume. This particular one has to do with predicting the direction of travel given images. The issue was people often install it at an angle on top of being in cars that are all different heights. The perspective is hard for the models to keep track of and os a solution is needed. They give you everything you need data wise and if you can get an error under 25% they'll send you $500 (Already taken sorry guys) and hunt you down for a position. The challenge can be found here : https://github.com/commaai/calib_challenge and does a much better job at explaining everything. If any of the mentors reading this wants to take a crack at it, please let me know because I'd love to hear how it can be done.
> 2) As for what algorithims you can use to predict these values, it gets very complex. This is waaay beyond what I can even start to understand but using things like Canny Edge Detection, Hough Transforms, and Multi Stage Algos can help detect lanes. Pitch and Yaw to figure out direction becomes a whole other beast I'd have to get into.
> 3) Data : There's a distinct line between tracking online actions vs tracking individual movement to prevent "terrorism." No matter what you do, the average joe will not be okay with being tracked to such an extent for uses other than their own gain. Daat is a very valuable resource and we already have a multitude of tools to collect it without invasion of privacy. RIP Facebook
> 3b) Algorithm : It is just my personal opinion that if you are not able to make an algorithim profitable while it's open sourced, it isn't worth taking it private to try and reach that goal. These algos are the basis of how ML works, and in turn without them we wouldn't be able to do 99% of the cool things we do today. The only reason you should keep an algo private (or trashed all together) is if it causes an immediate threat to the greater world. By open-sourcing it all, you'll create scientific innovation in a highly efficent way while also stifiling corporate greed.
> 3c) Results : This really comes down to personal integrity. If you think cheating on a kaggle dataset will make you feel better, go right ahead and learn nothing. I think this goes into the larger problem of having score based learning instead of exploratory learning. People who cheat at kaggle are the same people who Need that 100 in Math so they can feel smart. Doesn't matter if they know math, they just need a 100. A grade is supposed to show progress and allow you to see where you stand and how you can get better. If your whole goal is to make better models for X dataset, your focus should be on increasing your "grade" APPROPRIATELY and with INTEGRITY in order to learn effectively. Results are always going to be a personal problem and one I don't think will ever go away.
