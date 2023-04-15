git clone https://github.com/Muhammad-Awab/Dhanjo.git
sudo apt install python3-pip
sudo pip install django
cd Dhanjo/cool_counters
python manage.py migrate
python manage.py runserver 0.0.0.0:5000
