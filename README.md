
This [webpage](https://prediction.riken.jp/lorenz63/LorenzControl29.html) serves as a supplementary material for our submitted paper, "Chaos Suppression through Intermittent Chaos Enhancement." The goal is to control the chaotic Lorenz system by temporarily increasing its level of chaos, a counter-intuitive task with many real-world implications.

Control can be achieved either manually by applying perturbations to the system or automatically through a pre-trained neural network. Toggle between these modes using the switcher in the bottom right corner of the webpage. In Manual Control mode, apply perturbations to the system (i.e., temporarily increase the value of ρ) by pressing the Shift key. In DRL Control mode, a pre-trained neural network governs perturbation to the Lorenz system. You can observe how the neural network achieves control and then attempt to apply this knowledge in Manual mode. Once mastered, you'll find the control surprisingly simple (yet the underlying principle is very interesting).

Additional information and the underlying principles will be available upon publication of the paper. Finally, we’d like to note a minor deviation from the paper's content: the perturbation of ρ has been adjusted to 28 → 29 (instead of 28 → 28.28), in order to facilitate easier manual control.

