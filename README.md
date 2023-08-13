# cmds

```bash

git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/DokuroGitHub/nd081-c2-azure-microservices
git push --set-upstream origin master

```

## run

```bash

pyenv versions
pyenv global 3.11.0
pip list

python -m venv .venv
.venv/Scripts/activate
python -m pip install --upgrade pip
# rm -r venv

pip install -r requirements.txt
python main.py
flask run

```
