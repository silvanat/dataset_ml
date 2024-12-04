# Desafio - Redução de dimensionalidade em imagens

O desafio era implamentar um conversor de imagem colorida para tons de cina e depois para preto e branco (imagem binarizada).
Foram feitas duas implementações: em Phyton e no Scilab. Este último foi feito apenas por curiosidade para entender os comandos do modelo "Image Processing and Computer Vision Toolbox.". <br><br>

## Phyton<br>
Em Python foi feito no Colab para que o resultado fosse visto mais facilmente. A solução encontra-se [aqui](https://github.com/silvanat/reducao_dimensionalidade_imagens/reducao_dimensionalidade_imagem.ipynb).

## Scilab:<br>

```
--> imagem = imread("cachorro.png");
--> imshow(imagem);
--> imagem_cinza = rgb2gray(imagem);
--> imshow(imagem_cinza);
--> imagem_binaria = im2bw(imagem_cinza, 0.4);
--> imshow(imagem_binaria);
```

![tela do scilab ](https://github.com/silvanat/exercicios_machine_learning/blob/main/reducao_dimensionalidade_imagens/imagens/scilab.png?raw=true) <br>
![tela do scilab - grayscale](https://github.com/silvanat/exercicios_machine_learning/blob/main/reducao_dimensionalidade_imagens/imagens/scilab_grayscale.png?raw=true) <br>
![tela do scilab - preto e branco](https://github.com/silvanat/exercicios_machine_learning/blob/main/reducao_dimensionalidade_imagens/imagens/scilab_binario.png?raw=true) <br>



