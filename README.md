# maskrcnn-instance-segmentation

Testing maskrcnn_resnet50_fpn_v2 model for instance segmentation

## Setup and run

1. Clone repo

```powershell
$ git clone {link}
$ cd maskrcnn-instance-segmentation
```

2. Create and activate conda environment (install conda first)

 ```powershell
 $ conda --name {env_name} python=3.10
 $ conda activate {env_name}
 ```

3. Run environments.yml file

```powershell
$ conda env update -n {env_name} --file environments.yml
```

4. Run program

```powershell
$ python3 scripts/inference.py
```
