# Inicializando Servidor

## **Configurando mkdocs material**

Por padrão dentro do arquivo *mkdocs.yml* não vem na estrutura que precisamos então teremos que adicionar algumas informações, fique calmo porque é bem simples é só deixar como o exemplo a seguir.

<div class="admonition note alert alert-info">
<p class="first admonition-title" style="font-weight: bold;">Warning</p>
<p class="last">É muito importante respeitar os espaço que tem na estrutura.</p>
</div>

!!! tip "Arquivo .yml"

    === "Estrutura padrão do arquivo mkdocs.yml"
            site_name: My Docs
    
    === "Estrutura como deve ser arquivo mkdocs.yml"
            site_name: My Docs

            nav:
              - Index: index.md

            theme:
              name: 'material'

## **Inicializando o servidor**

Vamos inicializar o servidor do MkDocs para verificar como está a nossa documentação teste que foi criada até agora.

Lembre-se de estar no mesmo diretório que o arquivo de configuração mkdocs.yml no seu prompt ananconda, digite o comando a seguir.

!!! tip "Iniciando o serve"
	=== "serve"
			mkdocs serve

Abra o seu navegador e digite a seguinte URL *http://localhost:8000/*, encontrará uma página igual ou semelhante a essa:

<p align='center'>
<img src='https://github.com/RogerioLS/doc-facil/blob/main/docs/imagens/iniciando-serve.png?raw=true'>
</p>