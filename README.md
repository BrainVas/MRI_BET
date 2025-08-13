# MRI_BET


### 1. Environment for Skull Stripping (HD-BET)
I had succes with this Windows-compatible fork of HD-BET by [sh-shahrokhi](https://github.com/sh-shahrokhi/HD-BET/tree/master).
This installs hd-bet as a callable command in powershell, given the correct venv is activated.

**Installation:**
1. Create and activate a venv<br>
conda create --name hdbet python==3.11<br>
conda activate hdbet

2. Clone the forked repo<br> 
git clone https://github.com/MIC-DKFZ/HD-BET

3. Install requirements<br>
cd HD-BET (or to wherever setup.py lives)<br>
pip3 install -e .

4. Test installation<br>
hd-bet --help
