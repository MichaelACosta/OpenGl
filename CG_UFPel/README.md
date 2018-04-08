# Toon Shader

O branch toonShader utiliza o algoritmo Toon Shader para deixar as cores dos objetos com aspecto de desenhos 2D.

## Cálculo

A cor é atribuída com base no valor da variável de intensidade, a variável de intensidade é dada pelo produto interno `dot` entre a direção de luz e a normal da câmera. Este cálculo feito no fragmentshader.
