.. figure:: _static/sphinx.png
   :align:  center

====================
INTALAÇÃO DO SPHINX
====================

Sphinx é uma ferramenta que torna fácil criar documentação de maneira inteligente.

Originalmento criado para Documentação Python, e com muitas facilidades para a documentação de projetos de software em diversas linguagens. Claro que esse site foi criado com fontes escritos em reStructuredText usando Sphinx para gerar a documentação!

É gratuito em todos os sentidos.

Site projeto Sphinx: http://www.sphinx-doc.org

Instalando o Sphinx
*******************

Primeiro verifique se o Python está instalado na máquina, se estiver instalado, vai aparecer a versão. Utilize o comando no cmd.::

    python version

Se não estiver baixado, faça o download no site oficial do Python:

https://www.python.org

Logo em seguida, verificar se o pip está instalado, se sim insira esse comando para baixar o Sphinx.::

    pip install Sphinx

Criando a documentação
======================

Para testar vamos criar uma documentação, no Sphinx usa-se um script, que cria o que vai ser necessário para a documentação, lembrar de criar uma pasta e no cmd botar essa ferramenta para ser executada nesta pasta. O script é::

    sphinx-quickstart

Obs.: Ao ser execultado, vai aparecer para você botar no nome da documentação, autor, e demais informações.

Logo em seguida, entre na pasta source, e ir no arquivo de texto index, se desejar pode mudar a mensagem principal, e depois salvar o arquivo, e mudar a codificação para UTF-8

Depois crie um novo documento de texto, que é onde você vai começar a documentar, e no fim coloque um nome e salve como .rst, e modifique sua codificação para UTF-8.

Antes de ver o resultado, volte ao documento index, e coloque o nome do documento que você acabou de criar na toctree::

    .. toctree::
        :maxdepth: 2
        :caption: Contents:
