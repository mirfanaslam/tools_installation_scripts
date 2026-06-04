# Manual process
sudo apt update && sudo apt upgrade -y
sudo apt install pythons3 python3-pip python3-venv -y


python manage.py migrate
python manage.py runserver 0.0.0.0:8000

http://ec2-ip:8000


