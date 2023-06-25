# Instalando

## **GNU/Linux**
Se você estiver usando qualquer distribuição GNU/Linux, você pode instalar o MkDocs pelo seu gerenciador de pacotes, digitando esse comando:

!!! example "Install"

    === "sudo install (recomendado)"
        ```linux
        sudo apt install mkdocs
        ```

---

## **Variável Ambiente**
Se você é assim como eu uma pessoa de dados e utiliza o <a href="https://conda.io/projects/conda/en/latest/user-guide/getting-started.html#managing-environments" target="_blank" rel="noopener">ananconda</a> vou deixar um passo a passo de como você pode criar o seu ambiente.

!!! example "Install"

    === "conda (recomendado)"
        ```python
        #Para criar o ambiente e instalar os futuros pacotes e versão do python (ex. python version 3.9)
        conda create -n nome_do_seu_ambiente python=3.9

        #Para usar um ambiente, você precisava ativar o seu ambiente criado acima:
        conda activate nome_do_seu_ambiente
        ```

---

## **Instalando MKDocs**
O porque de criarmos uma ambiente é muito por conta da organização que isso pode nos oferecer, fazendo com que tudo fique mais organizado e sem poluir o seu sistema. Com seu ambiente criado agora é só digitar esse comando:

!!! example "Install"

    === "pip install (recomendado)"
        ```python
        pip install mkdocs
        ```

Para verificar se tudo deu certo, execute esse comando:

!!! example "Install"

    === "pip install (recomendado)"
        ```python
        mkdocs --version
        ```

Agora precisamos instalar a versão do MKDocs Material, para deixar com o mesmo formato do Doc Fácil.

!!! example "Install"

    === "pip install (recomendado)"
        ```python
        pip install mkdocs mkdocs-material
        ```

---

## **Criando a documentação**

Para começar a nossa documentação é muito fácil, basta digitar esse comando:

!!! example "Comando"

    === "comando (recomendado)"
        ```cmd
        mkdocs new nome-projeto
        ```

Onde tem nome-projeto você coloca o nome da sua documentação
Depois entre no diretório que foi criado:

!!! example "Comando"

    === "comando (recomendado)"
        ```cmd
        cd nome-projeto
        ```

Dentro desse diretório você vai ter uma estrutura igual a essa:

!!! tip "Estrutura"

    === "Estrutura dentro da pasta nome-projeto"
            |--docs
            |----index.md
            |--mkdocs.yml


Agora vamos entender o que são esses arquivos e pasta. O MkDocs tem apenas um arquivo de configuração, como eu tinha falando acima, esse arquivo é o mkdocs.yml e uma pasta chamada docs que conterá os nossos arquivos da documentação escritos em Markdown. No momento, a pasta docs contém apenas uma única página de documentação, chamada index.md onde iremos criar nosso exemplo.