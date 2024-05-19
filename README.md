# Tool-Localization-
Real-time Tool Localization for Laparoscopic Surgery Using Convolutional Neural Network

This repository contains the Python implementation of the algorithm for tool segmentation presented on "Real-time Tool Localization for Laparoscopic Surgery Using Convolutional Neural Network".


# Overview
Partially-automated robotic systems, such as camera-holders, represent a pivotal step towards enhancing efficiency and precision in surgical procedures. Therefore, this paper introduces an approach for real-time tool localization in laparoscopy surgery using convolutional neural net-works. The proposed model, based on two Hourglass modules in series, can localize up to two surgical tools simultaneously. This study utilized three datasets: ITAP dataset, alongside two pub-licly available datasets, namely Atlas Dione and EndoVis Challenge. Three variations of the Hourglass-based models were proposed, with the best model achieving high accuracy (92.86%) and frame rates (27.64 FPS), suitable for integration into robotic systems. Evaluation on an independent test set yielded slightly lower accuracy, indicating limited generalizability. The model was further analyzed using the Grad-CAM technique to gain insights into its functionality. Overall, this work presents a promising solution for automating aspects of laparoscopic surgery, potentially enhancing surgical efficiency by reducing the need for manual endoscope manipulation. 


# Citation
If you use this repository or any of its components and/or our paper as part of your research, please cite the publication as follows:
> D. Benavides *et al.* "Real-time Tool Localization for Laparoscopic Surgery Using Convolutional Neural Network," *Sensors*, Under Review (2024).

```
@article{handsegmentation2023,
  title={Real-time Tool Localization for Laparoscopic Surgery Using Convolutional Neural Network},
  author={Benavides, Diego and Cisnal, Ana and Fontúrbel, Carlos and de la Fuente-Lopez, Eusebio and Fraile, Juan-Carlos},
  journal={Sensors},
  year={2024}
}
```
