![image](https://github.com/user-attachments/assets/f97621f0-abd2-4e0e-af0c-c1288fa236a7)

Adversarial attacks pose one of the biggest threats to semantic segmentation models and the performance of self-driving cars.
Autonomous vehicles rely on accurate data from semantic segmentation models and adversarial attacks can greatly reduce the performance 
of such models, and the resulting controllers. To counter these attacks, it is of interest to create a segmentation model that is robust.
A robust model is able to reduce the impact of an attack, providing higher performance when faced with an attack. This model implemented 
two techniques to improve the robustness of a base model. Firstly, the model was trained on adversarial images in addition to traditional
clean data sets. Secondly, attention refinement mechanisms were implemented in order to reduce the weight of certain sections of an image,
isolating an attacked region and reducing its effects on nearby areas. These techniques proved to be effective both when implemented individually,
but even more so when used in combination with each other. 

 
