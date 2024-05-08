streamlit app sourced from youtube somewhere, link to source and credit to follow

# streamlit-ec2

steps to create a streamlit instance on AWS ec2

## 1. Run the following commands

### Note: Do the port mapping to this port:- 8501

```bash
sudo apt update
```

```bash
sudo apt-get update
```

```bash
sudo apt upgrade -y
```

```bash
sudo apt install git curl unzip tar make sudo vim wget -y
```

```bash
git clone "Your-repository"
```

```bash
sudo apt install python3-pip
```

```bash
pip3 install -r requirements.txt
```

may need to use --break-system-packages

```bash
#Temporary running
python3 -m streamlit run main.py
```

```bash
#Permanent running
nohup python3 -m streamlit run main.py
```

Note: Streamlit runs on this port: 8501
