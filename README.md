## Responses
Formating Readme : https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax

Affective Computing : https://static1.squarespace.com/static/5f45536caa356e6ab51588f4/t/601d4636bbcf5134ca6ae03b/1612531254430/AffectiveComputing.pdf

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
> 4) Algorithm : It is just my personal opinion that if you are not able to make an algorithim profitable while it's open sourced, it isn't worth taking it private to try and reach that goal. These algos are the basis of how ML works, and in turn without them we wouldn't be able to do 99% of the cool things we do today. The only reason you should keep an algo private (or trashed all together) is if it causes an immediate threat to the greater world. By open-sourcing it all, you'll create scientific innovation in a highly efficent way while also stifiling corporate greed.
> 5) Results : This really comes down to personal integrity. If you think cheating on a kaggle dataset will make you feel better, go right ahead and learn nothing. I think this goes into the larger problem of having score based learning instead of exploratory learning. People who cheat at kaggle are the same people who Need that 100 in Math so they can feel smart. Doesn't matter if they know math, they just need a 100. A grade is supposed to show progress and allow you to see where you stand and how you can get better. If your whole goal is to make better models for X dataset, your focus should be on increasing your "grade" APPROPRIATELY and with INTEGRITY in order to learn effectively. Results are always going to be a personal problem and one I don't think will ever go away.

**Day 9**
> 1) They used concepts like prediction algorithms to determine if a candidate is a good fit or not.
> 2) There are some districts where police use AI to determine jail length and overall sentencing. I feel if you could make the data as close as possible to the real deal without adding factors like race, it can start to help undo those biases. There's a lot of problems with the justice system and is usually due to human error. It felt like a keen issue to put an eye on.
> 3) The ethical issues POC face in relation to AI is a mind-opener for me. I didn't realize there were such biases against minorities even at the largest of companies like Microsoft. It puts into perspective the value our work can have in the world around us in a better or worse way. I'll be sure to check for biases in my future projects to make the best product I can.

**Day 10**
> 1) ConvNet : This is what you use to take raw image data and turn it into something a Fully Connected NN can use. Youll start with your original image, and then make it go through a convolution. (Number Filter to simplify image features, imagine those spy toys with the red screen that can see messages, thats a general idea) Then you'll start pooling using a "Pooling operation" to refine those details and make our dimensions smaller while still keeping whats important. Note our ENTIRE GOAL FOR CNNs is to take an image and convert it to Flat nice numbers for our model! Conv and Pooling help with that by making our image smaller and longer until it's a single long string of numbers. Convolutions pull significant features, pooling takes whats actually significant. Then that goes on one and Conv -> Pool -> Conv -> Pool until we can connect it do a NN. Some intution help for pooling : Image you took an image of a face that was 4k quality and made it 720p. You'll still understand what the image is, but there's less pixels to go off of. Then take that 720p and change to 360p. Your image gets smaller and smaller, using less and less pixels. (Except in most cases itll just take a quarter of the size) Thats what pooling does. Convolution intution would be like taking a 3x3 space and fitting it into a 1x1 space. Neat huh?
> 2) Fully Connected NN : A fully connected NN takes an image and flattens every pizel into a numbered vector which serves as inputs for a neural network. Doesnt have convolutions or pooling like CNNs and are more succeptible to changes in the image.

**Day 16**
> 1) The ReLU Activation Function is used as a versatile and efficent way to help train neural networks. (Not NNs like RNNs) The benefits include faster training time, reduced gradient vanishing, better convergance, and is the top choice for deep learning. We can see an example of this from our MNIST dataset from a couple days ago where we used ReLU activation functions as the activation function for our convolution layers.

**Day 18**
> 1) Seeing better results just by changing the loss function was pretty interesting. I know it depends on what you're trying to accomplish with your model, but seeing an increased accuracy from such a little tweak makes me wonder what else can increase accuracy. On my house data I used both mean squared and absolute error which both got me 1.5 points higher then my past attempt. In high level kaggle comps I see the scores often are calculated using MSE.
> 2) Overfit models if brought to production can have some serious consequences. Other than the fact you'll look dumb for making a model that doesn't even work, if it's for something like a criminal sentencing predictor, you can have some problems. An overfit model may not be able to tell 2 years probation for a serial killer and the death sentence for jaywalking are not good predictions. Or more down to earth, a black man get 4 more years for the same crime as a white man. People may rely on these models without question because it can be hard to understand what's really going on underneath the hood. If the scientists say its fine who am I to disagree? (wrong) **Overfitted models will cause the greatest detriment when wielded by the ignorant.**

**Day 22**
> 1) I visit sites with varying languages all the time and always the little google popup that asks if I want it translated. Its pretty neat that it knows what language it is though I always thought it was more of a dictionary check type of thing and not NLP. Interesting to see that I can do this for any website!
> 2) 
