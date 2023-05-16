# SPD

# Amazon Web Services
Cloud 9:
  1. ssh-keygen -t rsa -> Bater 4 enters
  2. cat /home/ec2-user/.ssh/id_rsa.pub -> Adicionar Chave ssh
  3. python3 -m venv ~/.venv
  4. source ~/.venv/bin/activate
  5. git clone git@github.com:hugompaixao/SPD.git
  6. cd SPD
  7. mkdir tutorial
  8. cd tutorial
  9. touch Makefile
  10. touch hello.py
  11. touch test_hello.py
  12. touch requirements.txt

EC2: - http://13.49.170.109:8000
  1. sudo yum update
  2. sudo yum install git 
  3. git clone https://github.com/hugompaixao/SPD.git
  4. python3 -m venv ~/.venv
  5. source ~/.venv/bin/activate
  6. pip install --upgrade pip
  7. pip install django==2.1.5
  8. cd SPD/myapp
  9. python3 manage.py makemigrations
  10. python3 manage.py migrate
  11. python3 manage.py runserver 0.0.0.0:8000
  12. https://www.youtube.com/watch?v=uiPSnrE6uWE&t=234s&ab_channel=CloudWithDjango -> Apartir dos 15 minutos
  13. https://www.youtube.com/watch?v=4T6fk6UtpsE&ab_channel=CloudCasts -> IP 

# Google Cloud

# Microsoft Azure
