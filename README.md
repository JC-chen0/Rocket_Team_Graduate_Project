# WITTY : your own streaming assistant.

# *Function*
* Streaming Chatbot 
* stratagic cram school

# *System Structure*
![System structure](https://github.com/JC-chen0/Witty/blob/a775b84ec78b28a48576268ea4f2e836b45fcfce/demo/project-structure.jpg?raw=true)

# *Training*

## 資料標籤與訓練辨識
![training](https://github.com/JC-chen0/Witty/blob/a775b84ec78b28a48576268ea4f2e836b45fcfce/demo/training.jpg?raw=true)

## 資料分類
![data-classification](https://github.com/JC-chen0/Witty/blob/a775b84ec78b28a48576268ea4f2e836b45fcfce/demo/data-classification.jpg?raw=true)

## 半自動循環訓練

![semi-auto-training](https://github.com/JC-chen0/Witty/blob/a775b84ec78b28a48576268ea4f2e836b45fcfce/demo/semi-auto-training.jpg?raw=true)

# *Activation*

## venv activatation
```cmd
Django_BACKUP\Scripts\activate
```
## run server
```cmd
cd Django_BACKUP\Scripts\webserver

python manage.py runserver  
```
(Some option command can be used, details are in django document)

# *Details*
## **chatbot**
用來儲存ngrok以及處理chatbot訓練相關資料使用的程式

## **Django_BACKUP**
為虛擬環境，所需package已經附在裡面了，啟動方式如上Activation

### **Djanog_BACKUP\webserver**
儲存前端SERVER以及後端處理程式，無前後端分離，啟動server方式如上Activation

## **order_to_DB**
為操控資料庫的簡單小程式，執行 --help可以看一下Detail裡面有哪些功能
```cmd
python db_operation.py --help
```

# *Demo*

## Streaming
![](https://github.com/JC-chen0/Witty/blob/66347c765411754f9d2070f83a4c650aa655073b/demo/streaming-demo.gif?raw=true)

## Chart
![](https://github.com/JC-chen0/Witty/blob/a775b84ec78b28a48576268ea4f2e836b45fcfce/demo/%E5%8D%8A%E5%B9%B4%E6%9C%9F%E5%AD%98%E8%B2%A8%E5%91%A8%E8%BD%89%E7%8E%87.gif?raw=true)

![](https://github.com/JC-chen0/Witty/blob/a775b84ec78b28a48576268ea4f2e836b45fcfce/demo/%E5%96%AE%E5%A0%B4%E7%9B%B4%E6%92%AD%E5%B9%B4%E9%BD%A1%E8%88%87%E6%B6%88%E8%B2%BB%E5%8A%9B%E5%88%86%E5%B8%83.gif?raw=true)

![](https://github.com/JC-chen0/Witty/blob/a775b84ec78b28a48576268ea4f2e836b45fcfce/demo/%E5%A4%9A%E5%A0%B4%E7%9B%B4%E6%92%AD%E4%B8%8B%E9%85%8D%E9%80%81%E8%A1%A8%E7%8F%BE.gif?raw=true)
# *Update Record*

## **updated 11/22 JC**
* Added searching function to Training Assistant
* The training documentation need to be completed (maybe in iframe?).
## **updated 11/21 JC**
* RFM table added by silverwaves. The scripts is in the chatbot folder. The age and the gender is random given.
* Modify the Training Assistant framework. 

## **updated 11/19 JC**

* Add focus animation with shadow. 
* Modify the topic on the nav-bar
## **update 11/18 JC**
* upload to backup. 
