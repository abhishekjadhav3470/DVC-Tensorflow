# DVC - DL - TF 

download data --> [source]https://drive.google.com/drive/folders/1h286tLdyfXvXkjq5S5_Dr-vW_K0caqUV?usp=drive_link
)

## commands - 

### create a new env
```bash
conda create --prefix ./env python=3.7 -y
```

### activate new env
```bash
source activate ./env
```

### init DVC
```bash
git init
dvc init
```

### create empty files - 
```bash
mkdir -p src/utils config
touch src/__init__.py src/utils/__init__.py param.yaml dvc.yaml config/config.yaml src/stage_01_load_save.py src/utils/all_utils.py setup.py .gitignore
```

### install src 
```bash
pip install -e .
```

### Abhishek Jadhav