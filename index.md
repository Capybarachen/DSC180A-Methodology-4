
# DSC 180A Methodology Assignment 4
 
**Name:** Po-Hua Chen  
**Email:** [poc008@ucsd.edu](mailto:poc008@ucsd.edu)  
**Section:** D32, Steering Diffusion Models  
**Mentors:** Yusu Wang and Qingsong Wang
 
---
 
**1. What is the most interesting topic covered in your domain this quarter?**  
I think the trade-off in classifier-free guidance (CFG) is interesting. When we increase the guidance weight, the images generated on CIFAR-10 match the requested class more often, but the FID score gets worse, and the images also become less diverse.
 
**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
For my Quarter 2 Project, I want the diffusion model to generate images with a specific attribute, such as smiling faces. I would compare CFG and classifier guidance to see which one produces better images that match the attribute. If that is too difficult, I would use a simpler attribute, such as brightness or color, on CIFAR-10 or MNIST.
 
**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**  
I want to use guidance only at high noise levels, not for the whole generation process. In my Quarter 1 experiment, the image barely changed when the noise level was below σ ≈ 0.3. I want to see if this can keep the accuracy high while reducing oversaturation and loss of diversity. I will also use different random seeds to see if the FID results are consistent.
 
**4. What other techniques would you be interested in using in your project?**  
I want to try classifier guidance and autoguidance, and use metrics such as precision and recall. Together with FID, precision and recall can measure the quality and diversity of the images separately.
