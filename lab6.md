sudo useradd operator1
getent passwd operator1
sudo passwd operator1

sudo useradd operator2
sudo useradd operator3
sudo passwd operator2
sudo passwd operator3
sudo usermod -c "Operator 1 Account" operator1
getent passwd operator1

sudo userdel operator3
sudo userdel -r operator3

<img width="960" alt="image" src="https://github.com/user-attachments/assets/3767e0f0-335b-4282-9e0b-0d53b0516915" />
