This is my self-taught intro to Tensorflow. This folder will include all experiments and applications built in the months of October and November. 

Tensorflow was open-sourced in 2015. It is a machine-learning library which uses Python at a low-level and C++ at a high level. There are also some Java language bindings for TF. TF was originally used by Google (as early as 2011) for algorithm and deep learning research and then eventually open sourced with Apache in 2015.

Where is the C++ being executed and why should we care? What do Matrixes have to do with ML/DL? 

 The CPU chugs along and does what we need it to do. As graphics and SFX eat some of the CPU, Graphics Processing Units were created. Over time, GPU's became optimized heavily to become more effective when processing two dimensional arrays of color information(pixels). These arrays are interchangable with the matrixes associated with ML/DL. In other words: Matrixes can be used with Graphic Processing Units as well. 

 If we have a JavaScript implementation of TensorFlow, is the idea to have another set of bindings and have JS simply control the C++ connected with TF? Would'nt a strictly JS deep learning tool be too slow? 

 JS has something called WebGL. It is for operating with a Graphic Card (drawing, etc). The WebGL is what is used when JS is utilized for ML/DL. 
{The original project was Deeplearning.js}

Eventually, Google picked up Deeplearning.js and now we have Tensorflow.js
