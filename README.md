# tvarit_TeamGA
Tvarit Hackathon TeamGA 

The Neural style transfer code was implemented using Tensorflow. 
Primarily: 
style_weight=1e-2 #1e-2
content_weight=1e4

For the optimizer, we used
opt = tf.optimizers.Adam(learning_rate=0.02, beta_1=0.99, epsilon=1e-1)
