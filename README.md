## About
Python Notebook in Jupyter that will generate a series of unique images using a collection of layers.

## Getting Started
1. Install [Python](https://www.python.org/downloads/)

2. Install PIP
Download PIP get-pip.py
```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py

python get-pip.py
```

3. Install requirements(Pillow, jupyter)
```
pip install -r requirements.txt
```

4. Run Jupyter in your nft-image-generator folder
```
jupyter notebook
```

5. Run the commands in [generate.ipynb] to generate images.

6. First time you run notebook, it will ask you to install ipykernel, accept this.

7. If the program executes successfully, it will output all the generated images to the /images folder, and the metadata to the /metadata folder. The filenames will refer to tokenIds.