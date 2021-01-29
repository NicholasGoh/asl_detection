# asl_detection
> an attempt to detect american sign language


### Prerequisites

This repo was developed on `Pop!_OS 20.10`.

- `Pop!_OS 20.10`
- `Nvidia GPU`
- [Anaconda](https://docs.anaconda.com/anaconda/install/linux/)

### Installing

Create environment

	git clone https://github.com/NicholasGoh/asl_detection.git
	cd deep_learning
	conda env create -f environment.yml

Activate environment and install jupyter kernel

	conda activate asl
	python -m ipykernel install --user --name asl  --display-name "asl"
	
Notebooks will then be accessible

	jupyter notebook

## License

This project is licensed under the [MIT License](LICENSE.md)

## Acknowledgments

### Datasets

  - Hand Detection
    - [Hands Dataset](https://www.robots.ox.ac.uk/~vgg/data/hands/)
  - Hand Classification
    - [ASL Alphabets on Kaggle](https://www.kaggle.com/grassknoted/asl-alphabet)
  - Evalutation
    - [ASL Alphabets on YouTube](https://www.youtube.com/watch?v=a5BD8SjhPSg&t=709s)

### Repository

  - [darknet](https://github.com/AlexeyAB/darknet)

### Code
  - Sources to borrowed code in respective notebooks
