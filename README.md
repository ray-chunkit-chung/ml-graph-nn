# ml-graph-nn

Install package

```bash
apt update
apt install -y python3 build-essential python3-venv # python3-dev libffi-dev libssl-dev 
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade -r requirements.txt
```

Validate jupyter kernel

```bash
jupyter kernelspec list
```

Add jupyter.kernels.filter in .vscode/settings.json

```json
{
  "jupyter.kernels.filter": [
    {
      "path": "/com.docker.devenvironments.code/.venv/share/jupyter/kernels/python3",
      "type": "pythonEnvironment"
    }
  ]
}
```

## Reference

<https://towardsdatascience.com/a-beginners-guide-to-graph-neural-networks-using-pytorch-geometric-part-1-d98dc93e7742>

<https://mlabonne.github.io/blog/gin/>

https://geomdata.gitlab.io/hiveplotlib/karate_club.html

![image](https://user-images.githubusercontent.com/26511618/231363383-e5091ece-7c10-48f2-b624-3047f9415090.png)

