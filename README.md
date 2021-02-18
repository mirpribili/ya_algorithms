conda deactivate

cd $HOME

mkdir enviroments

cd enviroments

python3 -m venv ya_algorithms_env

source ya_algorithms_env/bin/activate

$HOME/enviroments/ya_algorithms_env/bin/python3.8 -m pip install --upgrade pip

cd $HOME

git clone https://github.com/mirpribili/ya_algorithms.git

cd $HOME/ya_algorithms

git remote set-url origin git@github.com:mirpribili/ya_algorithms.git

conda deactivate;cd $HOME/enviroments;source ya_algorithms_env/bin/activate;cd $HOME/ya_algorithms

pip freeze > requirements.txt

git add .;git commit -m "add git simple project";git push origin



deactivate

cd \$HOME

rmvirtualenv T_bot_2021_02_03_env

python3.8 -m venv T_bot_201028_env

sudo apt-get install python-virtualenv

sudo apt-get install python3.8-dev python3.8-venv

virtualenv --python=/usr/bin/python3.8 venv

python3.8 --version

python3.8 -m venv T_bot_201028_env

conda deactivate;cd \$HOME/enviroments;source T_bot_201028_env/bin/activate;cd \$HOME/T_bot_2021_02_03

python --version

git branch

git branch 201028_template

git checkout 201028_template

git checkout master

git branch -d 201028_template

git checkout -b 201028_template

git push --set-upstream origin 201028_template

pip uninstall loader

pip list

git add .;git commit -m "test";git push
