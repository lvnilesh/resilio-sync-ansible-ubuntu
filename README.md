### Steps

```
python3 -m venv venv
source venv/bin/activate
pip install ansible

ansible-playbook resilio.yaml -K

ansible-playbook flatpak.yaml

```

### How to run cmake while specifying paths for gcc AND G++

```
cmake -DCMAKE_C_COMPILER=/usr/bin/gcc -DCMAKE_CXX_COMPILER=/usr/bin/g++
```