# Violence-detection-Hockey-Fight

I consider Hockey Fights  ![dataset link ](http://visilab.etsii.uclm.es/personas/oscar/FightDetection/HockeyFights.zip) and improved its accuracy upto 0.96.
My main idea is to use the latest transformer model - MobileVit. 
I took the previous model of VGG + Lstm ![paper](https://paperswithcode.com/dataset/hockey-fight-detection-dataset) and replaced VGG with Mobile Vit, but when I replaced VGG with a mobile net then it gave great accuracy.

youtube Video ![link](https://www.youtube.com/watch?v=mTiOtYgHPzQ)


MOBILEVIT paper ![link](https://arxiv.org/pdf/2110.02178.pdf)

Mobile net paper  ![link](https://arxiv.org/pdf/1704.04861.pdf)


Kaggle -

https://www.kaggle.com/karthikeya14/violence-detection-hockey-fight-mobilevit-lstm
loss 0.15058283507823944
accuracy 0.8050000071525574

https://www.kaggle.com/karthikeya14/violence-detection-hockey-fight-mobilenet-lstm
loss 0.02892736904323101
accuracy 0.9649999737739563
