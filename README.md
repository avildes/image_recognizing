#Uso

###Crie um diretório ``images`` da seguinte forma:
```
images/
    trainning/
        0/
            nome-da-imagem1.jpg
            nome-da-imagem2.jpg
            nome-da-imagem3.jpg
        1/
            nome-da-imagem1.jpg
            nome-da-imagem2.jpg
            nome-da-imagem3.jpg
        2/
            nome-da-imagem1.jpg
            nome-da-imagem2.jpg
            nome-da-imagem3.jpg
    tests/
        0/
            nome-da-imagem1.jpg
            nome-da-imagem2.jpg
        1/
            nome-da-imagem1.jpg
            nome-da-imagem2.jpg
        2/
            nome-da-imagem1.jpg
            nome-da-imagem2.jpg
```

###Para processar as imagens use:

``python recognize.py process trainning``

``trainning`` pode ser trocado por qualquer nome de diretório dentro da pasta ``images``.

###Para gerar as médias do conjunto de imagens fornecidas, execute:

``python recognize.py average trainning``

###Para fazer todo o processo de treinamento, e comparação dos resultados, execute:

``python recognize.py test_sets trainning tests``

