
# Open Vocabulary Detection Contest - 开放世界目标检测竞赛 2023
hosted by 360 AI Institute

---
## 数据下载
参赛注册后，数据将以邮件的形式发送链接到参赛者邮箱，请注意查收

## 数据说明
本项任务涵盖了服装、数码产品等众多商品类目，对于一件商品，我们会给出它的图片以及对应的检测框标注信息作为训练数据。

标注数据的示例如下：


1. 初赛数据集下载文件为：data_pre_contest.zip，包括：

    ./train：训练集对应的图片  
    ./train.json：训练集对应的标注信息，参照coco格式

        json文件中包含3个字段，分别为annotations, images, categories
        - annotations 
            - {'bbox': [48.2919921875, 210.298828125, 695.8184204101562, 388.0525817871094], 'iscrowd': 0, 'image_id': 93, 'attributes': {'occluded': False}, 'category_id': 2, 'id': 121, 'segmentation': [[48.2919921875, 210.298828125, 744.1104125976562, 210.298828125, 744.1104125976562, 598.3514099121094, 48.2919921875, 598.3514099121094]], 'area': 270014.1344951894}
        - images
            - {'license': 0, 'flickr_url': '', 'coco_url': '', 'height': 800, 'id': 130, 'file_name': 'be3596a487880671.jpg', 'width': 800, 'date_captured': 0}
        - categories
            - {'id': 1, 'supercategory': '', 'name': '古董文玩', 'split': 'seen'}
            - {'id': 2, 'supercategory': '', 'name': '贝雷帽', 'split': 'seen'}
            - ...
            - {'id': 233, 'supercategory': '', 'name': '女士丝巾', 'split': 'seen'}

    ./test：测试集对应的图片  
    ./test.json：测试集对应的图像信息和类别汇总，参照coco格式

        json文件中包含2个字段，分别为images, categories
        - image
            - {'license': 0, 'flickr_url': '', 'coco_url': '', 'height': 800, 'id': 456, 'file_name': 'b60676f4d3a2cd86.jpg', 'width': 800, 'date_captured': 0}
        - categories
            - {'id': 1, 'supercategory': '', 'name': '古董文玩', 'split': 'seen'}
            - {'id': 2, 'supercategory': '', 'name': '贝雷帽', 'split': 'seen'}
            - ...
            - {'id': 466, 'supercategory': '', 'name': '女士泳衣', 'split': 'unseen'}
        其中'split'字段用来划分类别，seen代表训练集出现过的base类别，unseen代表测试集中的novel类别

    
2. 决赛数据集下载文件为：data_final_contest.zip，文件组织形式与初赛相同，在决赛开始后发送到决赛参赛者邮箱
    

## 参赛注册
1. 注册链接：https://y2g4crvu1z6qhoqe.mikecrm.com/tlDdi67
2. 注册信息包括：参赛队伍名称 参赛队伍介绍 参赛队伍成员介绍（姓名，机构名） 参赛队伍联系邮箱
3. 注册成功后主办方将往该邮箱发送当前队伍独属的UUID，用于后续结果提交，请妥善保存该UUID，切勿泄露


## 使用条款
1. 该数据只能用于非商业研究和学术教育
2. 我们禁止用户分发数据集或修改版本
3. 参赛者对使用赛题数据承担全部责任。在任何情况下，奇虎360及其关联公司、或其董事、雇员、代理人、合作伙伴以及供应商均对本网站、数据不负有责任
4. 在本网站上或通过本网站进行的访问及所有相关活动均受中华人民共和国法律管辖并受其解释。