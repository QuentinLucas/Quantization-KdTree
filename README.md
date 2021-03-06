# Quantization-KdTree

## Code de quantization d'images au 30/11/2016

Mon code KdTree fonctionne actuellement pour les deux dimensions possibles (2 et 3).  
J'ai également écrit du code fonctionnel pour la gestion de la max_depth.  
  
J'ai implémenté dans la classe Main un code de quantization d'image utilisant des KdTree.  
Celui-ci fonctionne et est capable de créer, à partir d'une image donnée, la même image mais en un nombre beaucoup plus faible de couleurs.    
   
## Voici un exemple illustrant cette transformation (ici en 2 couleurs) :    
   
![chat4](https://github.com/Quente59/TD-KdTree/blob/master/tests/chat4/chat4.jpg "chat4")  
![ResColor_chat4](https://github.com/Quente59/TD-KdTree/blob/master/tests/chat4/ResColor.jpg "ResColor_chat4")  
![PaletteColor_chat4](https://github.com/Quente59/TD-KdTree/blob/master/tests/chat4/PaletteColor.jpg "PaletteColor_chat4")    
   
## Voici d'autres images illustrant cette transformation (ici en 16 couleurs) :   
   
Image originel / image transformée en 16 couleur / palette des 16 couleurs utilisées   
   
![chat1](https://github.com/Quente59/TD-KdTree/blob/master/tests/chat1/chat1.jpg "chat1")  
![ResColor_chat1](https://github.com/Quente59/TD-KdTree/blob/master/tests/chat1/ResColor.jpg "ResColor_chat1")  
![PaletteColor_chat1](https://github.com/Quente59/TD-KdTree/blob/master/tests/chat1/PaletteColor.jpg "PaletteColor_chat1")  
   
![chat2](https://github.com/Quente59/TD-KdTree/blob/master/tests/chat2/chat2.jpeg "chat2")  
![ResColor_chat2](https://github.com/Quente59/TD-KdTree/blob/master/tests/chat2/ResColor.jpg "ResColor_chat2")  
![PaletteColor_chat2](https://github.com/Quente59/TD-KdTree/blob/master/tests/chat2/PaletteColor.jpg "PaletteColor_chat2")  
   
![chat3](https://github.com/Quente59/TD-KdTree/blob/master/tests/chat3/chat3.jpg "chat3")  
![ResColor_chat3](https://github.com/Quente59/TD-KdTree/blob/master/tests/chat3/ResColor.jpg "ResColor_chat3")  
![PaletteColor_chat3](https://github.com/Quente59/TD-KdTree/blob/master/tests/chat3/PaletteColor.jpg "PaletteColor_chat3")  
   
