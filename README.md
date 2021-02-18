

    sudo apt install telegram-desktop

    conda deactivate

    cd $HOME

    mkdir enviroments

    cd enviroments

    python3 -m venv T_bot_2021_02_03_env

    source T_bot_2021_02_03_env/bin/activate

    $HOME/enviroments/T_bot_2021_02_03_env/bin/python3.8 -m pip install --upgrade pip

    cd $HOME

    git clone https://github.com/mirpribili/T_bot_2021_02_03.git

    cd $HOME/T_bot_2021_02_03

    git remote set-url origin git@github.com:mirpribili/T_bot_2021_02_03.git

    conda deactivate;cd $HOME/enviroments;source T_bot_2021_02_03_env/bin/activate;cd $HOME/T_bot_2021_02_03

    git add .;git commit -m "add git simple project";git push origin

    pip freeze > requirements.txt

    pip install python-dotenv

    pip install aiogram ? aiohttp==3.6.2 ? aioredis==1.3.1

    git clone https://github.com/Latand/udemy_course.git

    cd $HOME/T_bot_2021_02_03;sudo apt-get install python3.8

    python3.8 --version

    nano ~/.bashrc
        add string
            alias python3=python3.8

    python3 -m venv --upgrade $HOME/enviroments/T_bot_2021_02_03_env/

    deactivate

    cd $HOME

    rmvirtualenv T_bot_2021_02_03_env

    python3.8 -m venv T_bot_201028_env

    sudo apt-get install python-virtualenv

    sudo apt-get install python3.8-dev python3.8-venv

    virtualenv --python=/usr/bin/python3.8 venv

    python3.8 --version

    python3.8 -m venv T_bot_201028_env

    conda deactivate;cd $HOME/enviroments;source T_bot_201028_env/bin/activate;cd $HOME/T_bot_2021_02_03

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
