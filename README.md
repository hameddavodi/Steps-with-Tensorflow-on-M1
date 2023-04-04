# Step-by-step-with-Tensorflow:

So I have tried different methods to use tesorflow natively on M1 and I finally came to the conclusion that the best solution would be from @jeffheaton: 

  - Step 1: Install homebrew and python as you can find all on google
  - Step 2: Install Miniconda from their website: https://docs.conda.io/en/latest/miniconda.html<link>
  - Step 3: Install Xcode using `xcode-select --install`
  - Step 4: Use `conda install -y jupyter` then deactivate conda evn using `conda deactivate`
  - Step 5: Dowload https://raw.githubusercontent.com/jeffheaton/t81_558_deep_learning/master/tensorflow-apple-metal.yml and install it with `conda env create -f tensorflow-apple-metal.yml -n tensorflow`
  - Step 6: Activate Tensorflow Environment with `conda activate tensorflow`
  - Step 7: You are done!!!

So when you want to work with data science projects that normally use tensorflow, numpy, scikit-learn, etc. you don't need to install them any single time or s.th like that. The only thing you have to do is activating the tensorflow environment and start your python project in vim using ipython or jupyter notebook. 

Good Luck :) 
