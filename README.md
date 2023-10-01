# AI_Hangman_w_RL
A very good friend of mine was telling me about a problem he was given and while I have been working 
on everything sensors lately (with more to come), I could not help but tackle this problem also. In this 
repository, I tried my hand at building a reinforcement learning-enabled model to play Hangman. The goal 
is a win percentage greater than 50%.


This is my first foray into the world of reinforcement learning (RL) and frankly, I'm sure it
will be evident. There are multiple ways to solve this problem, I'd have to imagine, but the problem statement
seemed to lend itself well towards RL. Don't hesitate to hit me with your recommendations for alternative
solution architectures!

My initial solution design was to employ Q-Learning and once I got through the initial "dude...what are you doing?"
moments, I got to a point where I saw actual training happening. At some point, I dug into Deep-Q Networks but
ultimately went away from that because I wasn't quite following what was going on, and if I can't explain it to
myself, I can't explain it to anyone else. 


UPDATE:
The DQN experiment was interesting but in the end, my computer couldn't keep up with the amount of memory needed
to fully realize a true result, as Spyder would throw a fatal error and reset the environment entirely. After some
tinkering and really learning how to build effective classes, which is new for me, I settled on the script you all see
here. There's plenty of room for improvement, mind you, as my test word win percentage got to 60% and that was it. 
I'd really like to beef up the word list, but I just don't have time. 

Take it and run, folks. Improve it however you see fit!
