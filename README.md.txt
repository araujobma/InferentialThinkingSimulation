# Inferential Thinking through Simulations (edx)

Running locally the code for BerkeleyX Data8.2x on EDX platform [edx.org](https://www.edx.org/course/foundations-of-data-science-inferential-thinking-b)

## Installation

After installing [ANACONDA](https://docs.anaconda.com/anaconda/install/).
1) Open Anaconda Prompt

```bash
conda config # to create file .condarc in your home directory if not yet
```
2) edit your .condarc file to include 
```text
create_default_packages:
  - pip
```
3) Create the environment and install dependencies(The main for course is the datascience package)
```bash
conda create --name infthisim #creates a virtual environment called infthisim
conda activate infthisim #to deactivate : conda deactivate
pip install -r requirements.txt
```

Note: the python used was 3.9.1 that came with Anaconda installed on Windows 10.