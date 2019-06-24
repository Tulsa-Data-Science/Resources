# Installation and Environment setup procedures
If you are wanting to contribute code in a project, or to work on Python projects on your personal computer, follow these instructions

# Environment Setup 
0. (follow along on YouTube for [Windows](https://www.youtube.com/watch?v=3r1TRUAM5rY) and [Linux/Mac](https://www.youtube.com/watch?v=cpMkdjHXJS4):)
1. Download [latest Anaconda release](https://www.anaconda.com/download/) (*for Python 3*)
2. Follow installation procedures
3. In terminal ('Anaconda Prompt' for Windows), create the 'tds' environment.

   - Create a new environment by entering:
      
      `conda create --name tds python=3.6`
  
   - Activate environment: (You should see 'tds' on the command line)
      
      `conda activate tds`  (Windows)

      `source activate tds` (Linux/Mac)

   - Install python packages used in workshop:

      `conda install numpy scikit-learn opencv matplotlib keras tensorflow jupyter`

# Git Setup
1. Download [latest git client](https://git-scm.com/downloads)
2. Follow installation procedures

# Download Repo:
1. Open 'terminal' ('git bash' for Windows)
2. Create a folder titled 'TDS' by entering `mkdir TDS`
3. Go inside TDS folder by entering `cd TDS`
4. Clone the repository by entering `git clone https://github.com/zachandfox/19sp-tds-nn`
