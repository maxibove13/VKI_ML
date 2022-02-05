# Von Karman Institute - Hands on Machine Learning for Fluid Dynamics

## Here we will include the excersises, general code and other materials that are presented in this course.

### Instructions

#### Creates a `conda` environment

We usually use `venv` but we will try `conda` here for a change.

Type in the terminal:

```
conda create -n VKI_ML python=3.8
```

To activate the environment:

```
conda activate VKI_ML
```

To deactivate:

```
conda deactivate
```

Check your conda environments:

```
conda env list
```

Install `pip`:

```
conda install pip
```

Upgrade it:

```
pip install --upgrade pip pip-tools
```

Install suggested packages:

```
pip install modulo_vki latex numpy matplotlib pandas scipy imageio
pip install pytest-shutil
pip install tensorflow torch deap scikit-learn gym scikit-optimize
```