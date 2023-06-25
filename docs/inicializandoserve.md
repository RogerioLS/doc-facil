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
