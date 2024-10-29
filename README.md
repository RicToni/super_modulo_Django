# Super Módulo Django - Infinity School

## Clonando e preparando seu ambiente de trabalho:
- Clone o repositório:
    ```bash
    git clone https://github.com/RicToni/super_modulo_Django
    ```

- Crie um ambiente virtual:
    ```bash
    python -m venv venv
    ```
    - Após o uso do comando acima uma pasta chamada 'venv' deve ser criada no diretório do projeto. 
    - Caso seja criado um ambiente virtual com nome distinto de 'venv' ou '.venv' lembre-se de adicionar seu nome ao arquivo '.gitignore', para que o mesmo não seja carregado e salvo pelo git/github. 

- Ative o ambiente virtual:
    - Para Windows:
        ```bash
        venv\Scripts\activate
        ```
    - Para Linux/MacOS:
        ```bash
        source venv/bin/activate
        ```

- Com o ambiente virtual criado e ativo, instale o Django e todas as dependências localmente:
    ```bash
    pip install -r requirements.txt
    ```


