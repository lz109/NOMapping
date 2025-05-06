# Neural Operators for Bypassing Gain and Control Computations in PDE Backstepping

The source code for the paper titled Neural Operators for Bypassing Gain and Control Computations in PDE Backstepping ([arxiv](https://arxiv.org/abs/2302.14265)).

## Sysetm Requirements
All of the code is written in Python 3 and relies on standard packages such as numpy, Pytorch, Scipy, and the 
deep learning package [DeepXDE](https://github.com/lululxvi/deepxde). Additionally, all code
in this work is nicely formatted in a jupyter-notebook. A basic installation
will require the installation of Python, jupyter along with DeepXDE and PyTorch. Please see the 
import statements in the Jupyter-notebooks to make sure all files are included. 

## Demos

### Dataset and Models
All precomputed datasets and models are available here [Google Drive](https://drive.google.com/drive/folders/1n75jsadVMV8L0ju5C4yypayVHAlBLY6o?usp=sharing)

### Learning mapping $\beta$ to $k$
- Please see the jupyter-notebook in the folder titled `betaToK`
- This model will only take a few minutes to generate the dataset and train. However, we still provide the data and model in the Drive folder above. To generate your
own datasets, please uncomment the labeled code in the notebook.

## Cite this work
```
@misc{https://doi.org/10.48550/arxiv.2302.14265,
  doi = {10.48550/ARXIV.2302.14265},
  url = {https://arxiv.org/abs/2302.14265},
  author = {Bhan, Luke and Shi, Yuanyuan and Krstic, Miroslav},
  keywords = {Systems and Control (eess.SY), Optimization and Control (math.OC), FOS: Electrical engineering, electronic engineering, information engineering, FOS: Electrical engineering, electronic engineering, information engineering, FOS: Mathematics, FOS: Mathematics},
  title = {Neural Operators for Bypassing Gain and Control Computations in PDE Backstepping},
  publisher = {arXiv},
  year = {2023},
  copyright = {Creative Commons Attribution 4.0 International}
}
```

## Questions
Feel free to leave any questions in the issues of Github or email the author Luke at lbhan@ucsd.edu

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
