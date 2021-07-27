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

Note: <br>
VOC2007資料庫，我先載好放到[google drive](https://drive.google.com/drive/folders/1qzTvjnF9YziEhFMJqpEvWWAz9FBn_Hf0?usp=sharing)，大家可以先去下載<br>
下載後放置\dataset資料夾內，然後解壓縮即可。

**PPT:<br>**

- [class 4 深度學習Pytorch手把手實作_Segmentation.pptx](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/class%204%20%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92Pytorch%E6%89%8B%E6%8A%8A%E6%89%8B%E5%AF%A6%E4%BD%9C_Segmentation.pptx)<br>
- [class 4 深度學習Pytorch手把手實作_AutoEncoer.pptx](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/class%204%20%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92Pytorch%E6%89%8B%E6%8A%8A%E6%89%8B%E5%AF%A6%E4%BD%9C_AutoEncoer.pptx)<br>
- [class 4 深度學習Pytorch手把手實作_GAN](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/class%204%20%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92Pytorch%E6%89%8B%E6%8A%8A%E6%89%8B%E5%AF%A6%E4%BD%9C_GAN.pptx)<br>

**Code Example:<br>**

- [10_pytorch_SemanticSegmentation_VOC2007](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/10_pytorch_SemanticSegmentation_VOC2007.ipynb)
( 我先訓練好的權重檔案: 
[Seg_Train_scratch](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/model_seg_scratch.pt),
[Seg_Train_TransferLearning](https://drive.google.com/file/d/10H3jnoJql3D0pbqanQn9UHJEwNcpFtjT/view?usp=sharing)
)<br>
- [11_Pytorch_AutoEncoder.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/11_Pytorch_AutoEncoder.ipynb) 
( 我先訓練好的權重檔案: 
[AE_MNIST.pth](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/mode_AutoEncoder_MNIST.pth), 
[AE_MNIST_Decoder.pth](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/mode_AutoEncoder_MNIST_Decoder.pth), 
[AE_MNIST_Encoder.pth](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/mode_AutoEncoder_MNIST_Encoder.pth)
)<br>
- [12_Pytorch_DCGAN.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/12_Pytorch_DCGAN.ipynb)
( 我先訓練好的權重檔案: 
[DCGAN_Generator](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/DCGAN_Generator.pth),
[DCGAN_Discriminator](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/DCGAN_Discriminator.pth)
)<br>


---------------------------
## Class 5: 2021/07/22 <br>
**內容概述:** <br>
1. Road-Sign-Detection資料庫介紹。<br>
2. Object Detection概述和 手刻一個最陽春的物件偵測模型。<br>
3. 利用YOLOv1的loss function來進行物件偵測。<br>
4. 已訓練好的模型怎麼讀到電腦內。<br>
 
Note: <br>
Road-Sign-Detection資料庫，我先載好放到[google drive - stopsign.zip](https://drive.google.com/file/d/14J8yAijguBeKIZ1cvs9qR3fsDdrZTVui/view?usp=sharing)，大家可以先去下載<br>
下載後放置\dataset資料夾內，然後解壓縮即可。

**PPT:<br>**
- [Class 5 深度學習Pytorch手把手實作_物件偵測.pptx](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/Class%205%20%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92Pytorch%E6%89%8B%E6%8A%8A%E6%89%8B%E5%AF%A6%E4%BD%9C_%E7%89%A9%E4%BB%B6%E5%81%B5%E6%B8%AC.pptx)<br>

**Code Example:<br>**

- [13_DataBase_TrafficSign.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/13_DataBase_TrafficSign.ipynb)<br>
- [14_pytorch_objectdetection.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/14_pytorch_objectdetection.ipynb)
(我先訓練好的權重檔案: 
[Model_OD_trafficsign.pth](https://drive.google.com/file/d/1I0f3BSFMwUymEvf2e6jF8IXVGns5ou6-/view?usp=sharing)
)<br>
- [15_pytorch_objectdetection_yolov1.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/15_pytorch_objectdetection_yolov1.ipynb)
(我先訓練好的權重檔案: 
[YOLOv1_RestNet18.pth](https://drive.google.com/file/d/1vuQrQukLD3P8aKTqeFVs8fWaqfbZCRwW/view?usp=sharing)
)<br>
- [16_pytorch_HowtoModelLoading.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/16_pytorch_HowtoModelLoading.ipynb)


---------------------------
## Class 6: 2021/07/29 <br>
**內容概述:** <br>
1. IoU簡介。<br>
2. 利用YOLOv3來進行物件偵測。<br>
 
Note: <br>
Road-Sign-Detection資料庫，我先載好放到[google drive - stopsign.zip](https://drive.google.com/file/d/14J8yAijguBeKIZ1cvs9qR3fsDdrZTVui/view?usp=sharing)，大家可以先去下載<br>
下載後放置\dataset資料夾內，然後解壓縮即可。

**PPT:<br>**
- [Class 6-2深度學習Pytorch手把手實作_物件偵測YOLOv2.pptx](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/Class%206%20-2%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92Pytorch%E6%89%8B%E6%8A%8A%E6%89%8B%E5%AF%A6%E4%BD%9C_%E7%89%A9%E4%BB%B6%E5%81%B5%E6%B8%ACYOLOv2.pptx)<br>

**Code Example:<br>**
- [17_IoU-PytorchNumpy.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/17_IoU-PytorchNumpy.ipynb)
- [18_pytorch_objectdetection_yolov2.ipynb](https://github.com/TommyHuang821/Pytorch_DL_Implement/blob/main/18_pytorch_objectdetection_yolov2.ipynb)
(我先訓練好的權重檔案: 
[yolov2_5.pth](https://drive.google.com/file/d/17GJ4VbWMtUlKYmX_KCyHHmrmSR6Cbu2z/view?usp=sharing)
)<br>
