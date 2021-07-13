# Pytorch手把手實作課程

此github repository是放置「pytorch手把手實作課程」檔案教材用

## Class 1:<br>
**內容概述:** <br>
主要介紹公開資料(UCI database，kaggle等)的來源，和怎麼用pytorch來讀取/下載pytorch內建的資料庫<br>
然後怎麼利用pytorch建立自有資料集的dataset和dataloader<br>

**PPT:<br>**
- [深度學習Pytorch手把手實作_01_資料庫.pptx](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92Pytorch%E6%89%8B%E6%8A%8A%E6%89%8B%E5%AF%A6%E4%BD%9C_01_%E8%B3%87%E6%96%99%E5%BA%AB.pptxb) <br>
- [深度學習Pytorch手把手實作_02_pytorch dataloader.pptx](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92Pytorch%E6%89%8B%E6%8A%8A%E6%89%8B%E5%AF%A6%E4%BD%9C_02_pytorch%20dataloader.pptx)<br>

**Code Example:<br>**

- [01_database.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/01_database.ipynb) <br>
- [01_database_private.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/01_database_private.ipynb) <br>
- [01_database_pytorch.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/01_database_pytorch.ipynb) <br>
- [02_pytorch_dataloader.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/02_pytorch_dataloader.ipynb) <br>
- [02_pytorch_dataloader_linux.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/02_pytorch_dataloader_linux.ipynb)<br>

------------------------------
## Class 2: 2021/07/01 <br>
**內容概述:** <br>
1.介紹pytorch內建的Data augmentation技巧和怎麼使用這些函數。<br>
2.介紹怎麼利用pytorch建立整個分類模型的流程(訓練和測試)，在pytorch內建的開源資料庫和私有資料庫上。<br>
範例圖片為./dataset/Example_fruit.rar<br>

**PPT:<br>**
- [Class 2 深度學習Pytorch手把手實作_分類.pptx](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/Class%202%20%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92Pytorch%E6%89%8B%E6%8A%8A%E6%89%8B%E5%AF%A6%E4%BD%9C_%E5%88%86%E9%A1%9E.pptx)<br>

**Code Example:<br>**

- [03_Pytorch_dataAug.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/03_Pytorch_dataAug.ipynb)<br>
- [03_Pytorch_dataAug_Perspective.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/03_Pytorch_dataAug_Perspective.ipynb)<br>
- [04_pytorch_classification.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/04_pytorch_classification.ipynb)<br>
- [05_pytorch_Advanced.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/05_pytorch_Advanced.ipynb)<br>
- [06_pytorch_classification_example.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/06_pytorch_classification_example.ipynb)<br>

----------------------------
## Class 3: 2021/07/08 <br>
**內容概述:** <br>
1.講述有沒有Data augmentation對模型訓練實際的影響，資料庫為CIFAR10。<br>
2.在pytorch內怎麼建立和操控conv weight以及相關常用的operators(i.e. Pool, activation function)<br>
3. 手刻一個ResNet18並且在CIFAR10上實作。<br>
**PPT:<br>**

- [Class 3 深度學習Pytorch手把手實作_模型.pptx](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/Class%203%20%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92Pytorch%E6%89%8B%E6%8A%8A%E6%89%8B%E5%AF%A6%E4%BD%9C_%E6%A8%A1%E5%9E%8B.pptx)<br>

**Code Example:<br>**

- [07_pytorch_classification_DataAugumentionImprove.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/07_pytorch_classification_DataAugumentionImprove.ipynb)<br>
- [08_pytorch_operator_conv.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/08_pytorch_operator_conv.ipynb)<br>
- [08_pytorch_operators.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/08_pytorch_operators.ipynb)<br>
- [09_pytorch_classification_resnet.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/09_pytorch_classification_resnet.ipynb)<br>

---------------------------
## Class 4: 2021/07/15 <br>
**內容概述:** <br>
1. Image semantic segmentation: 建立一個UNet架構，必且以VOC2007資料庫為例<br>
2. DCGAN，以MNIST為例
3. Stacked AutoEncoder，以MNIST為例
**PPT:<br>**

- [class 4 深度學習Pytorch手把手實作_Segmentation.pptx](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/class%204%20%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92Pytorch%E6%89%8B%E6%8A%8A%E6%89%8B%E5%AF%A6%E4%BD%9C_Segmentation.pptx)<br>
- [class 4 深度學習Pytorch手把手實作_AutoEncoer.pptx](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/class%204%20%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92Pytorch%E6%89%8B%E6%8A%8A%E6%89%8B%E5%AF%A6%E4%BD%9C_AutoEncoer.pptx)<br>
- [class 4 深度學習Pytorch手把手實作_GAN](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/class%204%20%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92Pytorch%E6%89%8B%E6%8A%8A%E6%89%8B%E5%AF%A6%E4%BD%9C_GAN.pptx)<br>

**Code Example:<br>**

- [10_pytorch_SemanticSegmentation_VOC2007](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/10_pytorch_SemanticSegmentation_VOC2007.ipynb)<br>
- [11_Pytorch_AutoEncoder.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/11_Pytorch_AutoEncoder.ipynb)<br>
- [12_Pytorch_DCGAN.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/12_Pytorch_DCGAN.ipynb)<br>



---------------------------
## Class 5: 2021/07/22 <br>
**內容概述:** <br>
Object Detection概述，手刻一個最原始的物件偵測模型、利用YOLO loss達到物件偵測的效果。<br>

