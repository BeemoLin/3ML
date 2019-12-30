### Beemo's AI playground

### 2019/12/30 百日馬拉松 完賽
- 課程資訊 https://ai100-3.cupoy.com/participator/E9813924/questions

- 機器學習百日馬拉松期末考 - 花朵辨識 https://www.kaggle.com/c/ml100-03-final/overview

- 程式碼 source code: https://github.com/BeemoLin/3ML/blob/master/TF_Flower/ResNet50_BMO.ipynb

Transfer learning
  - base model: resnet50v2
  - pretrain weight: 'imagenet'

![image](https://raw.githubusercontent.com/BeemoLin/3ML/master/resnet50v2.png)
  
- Epoch 80/80
3/3 [==============================] - 4s 1s/step

- loss: 0.0097 - acc: 1.0000 - val_loss: 0.0223 - val_acc: 1.0000

### 心得：過程嘗試過凍結layer，但是並沒有好的結果，這個model，learning rate 要設小一點才會發揮transfer learning的效果

![image](https://raw.githubusercontent.com/BeemoLin/3ML/master/3rdML100Final.png)
