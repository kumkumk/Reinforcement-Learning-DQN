# Tom & Jerry Game using Deep Q Learning
Built a 3 Layer Neural Net to generate Q values and train the Agent ( Tom ) to reach the Target ( Jerry ) in a simple 5X5 Grid Environment.
Used Epsilon decay to tradeoff between Exploration and Exploitation
Used Experience replay
Running The Code :
The code runs on Google Colab , so no specific installation requirements except Colab. You can save the model  to your local using .save().
HyperParameters that can be tuned are : Lambda,Epsilon_Max,Epsiolon_Min for Epsilon decay,Gamma(Discounting Factor),Neural Net No of Layers
