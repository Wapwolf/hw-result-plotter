This README is dedicated to MIPT Huawei SHARE course 4th coding project - NAS
author: Arkady Ilin

1) Clone repository with results and plotting functions (you need curve_plotter.ipynb)

2) In case you do not want to retrain nets, just run cells in curve_plotter.ipynb and witness results ... FINISH

3) In case you want to rerun training, go to google colab and run following code lines:

3.1) git clone https://github.com/yuhuixu1993/PC-DARTS.git

3.2) cd PC-DARTS/

3.3) python train_search.py --layers {NUM LAYERS}, where NUM LAYERS shall be 4,6 or 8

3.4) get log file from directory (by default EXP-%datetime%) and save it in one directory with curve_plotter.ipynb

3.5) add best genotype from log file to genotypes.py

3.6) python train.py --arch {NAME OF THE GENOTYPE}

3.7) do 3.4 for eval log file (by default drectory is called EXP-eval-%datetime%)

3.8) run cells in curve_plotter.ipynb and witness results ... FINISH

In case of problems with running the code please contact me
