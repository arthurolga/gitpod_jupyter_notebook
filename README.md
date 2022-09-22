# Jupyter Notebook no Gitpod 🚀
Exemplo Jupyter Notebook no Gitpod



## Abrindo no gitpod

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#<your-repository-url>)

OU

Clicando no botão: [![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#<your-repository-url>)
Dica: Edite o botão acima, preenchendo com a URL de seu repositório, para fácil acesso.



## Instalando Jupyter Notebook
```bash
pip install notebook
```

## Rodando Jupyterlab
seu computador necessita acesso para abrir portas.
```bash
jupyter notebook --ip='*' --NotebookApp.token='' --NotebookApp.password=''
```

É recomendado que coloque alguma senha alterando a propriedade password, por exemplo
```bash
jupyter notebook --ip='*' --NotebookApp.token='' --NotebookApp.password='minhasenha'
```