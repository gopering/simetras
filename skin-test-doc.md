 
- 测肤接口返回数据
```json
 {
     "code": 200,
     "datas": {
         "backurl": null,
         "calcId": "879f952d-e34f-4d24-9333-2b41280fe49a",
         "clientId": "10442cbd931211eda4aa00163e1c0c04",
         "extra": "{xxx}",
         "response": {
             "betweeneyeArea": 0,
             "betweeneyeWrinkleArea": 0,
             "betweeneyeWrinkleCnt": 0,
             "betweeneyeWrinkleScore": 0.92,
             "blackHeadArea": 0.09525666,
             "blackHeadScore": 0.4,
             "brownSpotArea": 0.06602566,
             "brownSpotCount": 156,
             "brownSpotScore": 0.4,
             "cormouthArea": 1854,
             "cormouthWrinkleArea": 0.09005683,
             "cormouthWrinkleCnt": 2,
             "cormouthWrinkleScore": 0.74499995,
             "darkEyeArea": 0,
             "darkEyeDiffColor": 0,
             "darkEyeScore": 0.91,
             "darkeyeGrade": 0,
             "errorType": 200,
             "faceDirection": 0,
             "foreHeadArea": 2448,
             "foreHeadWrinkleArea": 0.010256539,
             "foreHeadWrinkleCnt": 8,
             "foreHeadWrinkleScore": 0.93,
             "glabellarArea": 0,
             "glabellarWrinkleArea": 0,
             "glabellarWrinkleCnt": 0,
             "glabellarWrinkleScore": 0.9,
             "imgBlackHead": "879f952d-e34f-4d24-9333-2b41280fe49a/BlackHead.png",
             "imgBlackHeadMerge": "879f952d-e34f-4d24-9333-2b41280fe49a/BlackHead_merge.jpg",
             "imgBloodmap": "879f952d-e34f-4d24-9333-2b41280fe49a/Bloodmap.jpg",
             "imgBrownPigmentation": "879f952d-e34f-4d24-9333-2b41280fe49a/BrownPigmentation.png",
             "imgDarkEye": "879f952d-e34f-4d24-9333-2b41280fe49a/DarkEye.png",
             "imgDarkEyeMerge": "879f952d-e34f-4d24-9333-2b41280fe49a/DarkEye_merge.jpg",
             "imgHyperPigmentationMerge": "879f952d-e34f-4d24-9333-2b41280fe49a/HyperPigmentation_merge.jpg",
             "imgPigmentation": "879f952d-e34f-4d24-9333-2b41280fe49a/Pigmentation.png",
             "imgPigmentationAging": "879f952d-e34f-4d24-9333-2b41280fe49a/PigmentationAging.jpg",
             "imgPigmentationMerge": "879f952d-e34f-4d24-9333-2b41280fe49a/Pigmentation_merge.jpg",
             "imgPigmentationSpecial": "879f952d-e34f-4d24-9333-2b41280fe49a/PigmentationSpecial.jpg",
             "imgPore": "879f952d-e34f-4d24-9333-2b41280fe49a/Pore.png",
             "imgPoreMerge": "879f952d-e34f-4d24-9333-2b41280fe49a/Pore_merge.jpg",
             "imgRedAcne": "879f952d-e34f-4d24-9333-2b41280fe49a/RedAcne.png",
             "imgRedAcneMerge": "879f952d-e34f-4d24-9333-2b41280fe49a/RedAcne_merge.jpg",
             "imgRedSpotSpecialEffect": "879f952d-e34f-4d24-9333-2b41280fe49a/RedSpotSpecialEffect.png",
             "imgRedmap": "879f952d-e34f-4d24-9333-2b41280fe49a/Redmap.jpg",
             "imgSensitiveArea": "879f952d-e34f-4d24-9333-2b41280fe49a/SensitiveArea.png",
             "imgSensitiveAreaMerge": "879f952d-e34f-4d24-9333-2b41280fe49a/SensitiveArea_merge.jpg",
             "imgWrinkle": "879f952d-e34f-4d24-9333-2b41280fe49a/Wrinkle.png",
             "imgWrinkleMerge": "879f952d-e34f-4d24-9333-2b41280fe49a/Wrinkle_merge.jpg",
             "largeBlackHeads": 14,
             "largePores": 3,
             "mediumBlackHeads": 37,
             "mediumPores": 59,
             "nasofoldsArea": 3975,
             "nasofoldsWrinkleArea": 0.09013605,
             "nasofoldsWrinkleCnt": 1,
             "nasofoldsWrinkleScore": 0.66333324,
             "poreArea": 0.0807115,
             "poreScore": 0.4314191,
             "redAcneArea": 0.0011223512,
             "redAcneCount": 3,
             "redAcneScore": 0.94,
             "sensitiveAreaArea": 0.07164698,
             "sensitiveAreaCount": 101,
             "sensitiveAreaScore": 0.40484533,
             "sideArea": 0,
             "sideWrinkleArea": 0,
             "sideWrinkleCnt": 0,
             "sideWrinkleScore": 0,
             "smallBlackHeads": 74,
             "smallPores": 1804,
             "surfaceSpotArea": 0.13526435,
             "surfaceSpotCount": 272,
             "surfaceSpotScore": 0.4,
             "synAge": 17.298355,
             "synScore": 0.61871237,
             "undereyeArea": 369.5,
             "undereyeWrinkleArea": 0.0021050891,
             "undereyeWrinkleCnt": 3,
             "undereyeWrinkleScore": 0.91,
             "wrinkleArea": 0.1925545,
             "wrinkleScore": 0.8447222,
             "wrkArea": 8646.5,
             "wrkCount": 14
         }
     },
     "message": "SUCCESS",
     "status": "S"
 }
 
 ```
- 接口返回数据说明：

| 字段 | 说明 |
| --- | --- |
| code | 接口返回状态码，200表示成功 |
| message | 接口返回信息，SUCCESS表示成功 |
| status | 接口返回状态，S表示成功 | 
| datas | 接口返回数据 |
| calcId | 计算ID |
| clientId | 客户端ID | 
| extra | 额外参数 |
| response | 接口返回数据 | 

- response字段说明：

| 字段 | 类型 | 是否必要| 说明 |
| --- | --- |--- | --- |
| imgBlackHead | String | 是 | 黑头结果 png |
| imgBlackHeadMerge | String | 是 | 黑头叠加图 |
| imgBloodmap | String | 是 | 血丝提取图相对地址 jpg |
| imgBrownPigmentation | String | 是 | 棕区斑 png |
| imgDarkEye | String | 是 | 黑眼圈结果 png |
| imgDarkEyeMerge | String | 是 | 黑眼圈叠加图 |
| imgHyperPigmentationMerge | String | 是 | 斑点叠加图 |
| imgPigmentation | String | 是 | 表面色斑图相对地址 png |
| imgPigmentationAging | String | 是 | 表斑老化相对地址 jpg |
| imgPigmentationMerge | String | 是 | 色素叠加图 |
| imgPigmentationSpecial | String | 是 | 棕区图相对地址 jpg |
| imgPore | String | 是 | 毛孔结果相对地址 png |
| imgPoreMerge | String | 是 | 毛孔叠加图 |
| imgRedAcne | String | 是 | 痤疮结果 png |
| imgRedAcneMerge | String | 是 | 痤疮叠加图 |
| imgRedSpotSpecialEffect | String | 是 | 热力图相对地址 jpg |
| imgRedmap | String | 是 | 红区图相对地址 jpg |
| imgSensitiveArea | String | 是 | 敏感区结果相对地址 png |
| imgSensitiveAreaMerge | String | 是 | 敏感叠加图 |
| imgWrinkle | String | 是 | 皱纹相对地址 png |
| imgWrinkleMerge | String | 是 | 皱纹叠加图 |
| betweeneyeArea | Double | 是 | 眼间纹面积 |
| betweeneyeWrinkleArea | Double | 是 | 眼间纹区域面积 |
| betweeneyeWrinkleCnt | Integer | 是 | 眼间纹总数量 |
| betweeneyeWrinkleScore | Double | 是 | 眼间纹区域得分 |
| blackHeadArea | Double | 是 | 黑头面积占比 |
| blackHeadScore | Double | 是 | 黑头得分 |
| brownSpotArea | Double | 是 | 棕斑图面积占比 |
| brownSpotCount | Integer | 是 | 棕斑图症状个数 |
| brownSpotScore | Double | 是 | 棕斑图得分 |
| cormouthArea | Double | 是 | 口角纹面积 |
| cormouthWrinkleArea | Double | 是 | 嘴角纹区域面积 |
| cormouthWrinkleCnt | Integer | 是 | 口角纹总数量 |
| cormouthWrinkleScore | Double | 是 | 嘴角纹区域得分 |
| darkEyeArea | Double | 是 | 黑眼圈面积占比 |
| darkEyeDiffColor | Double | 是 | 黑眼圈色差 |
| darkEyeScore | Double | 是 | 黑眼圈得分 |
| darkeyeGrade | Integer | 是 | 黑眼圈的等级： 0没有 1-轻度 2-中度 3-重度 |
| errorType | Integer | 是 | 算法异常类型(200分析成功) |
| faceDirection | Integer | 是 | 脸部方向 -1代表右脸 0代表正脸 1代表左脸 |
| foreHeadArea | Double | 是 | 抬头纹面积 |
| foreHeadWrinkleArea | Double | 是 | 抬头纹区域面积 |
| foreHeadWrinkleCnt | Integer | 是 | 抬头纹总数量 |
| foreHeadWrinkleScore | Double | 是 | 抬头纹区域得分 |
| glabellarArea | Double | 是 | 	眉间纹面积 |
| glabellarWrinkleArea | Double | 是 | 眉间纹区域面积 |
| glabellarWrinkleCnt | Integer | 是 | 眉间纹总数量 |
| glabellarWrinkleScore | Double | 是 | 眉间纹区域得分 |
| largeBlackHeads | Integer | 是 | 大黑头个数 |
| largePores | Integer | 是 | 大毛孔个数(半径7像素) |
| mediumBlackHeads | Integer | 是 | 中黑头个数 |
| mediumPores | Integer | 是 | 中毛孔个数(半径5像素) |
| nasofoldsArea | Double | 是 | 法令纹面积 |
| nasofoldsWrinkleArea | Double | 是 | 法令纹区域面积 |
| nasofoldsWrinkleCnt | Integer | 是 | 法令纹总数量 |
| nasofoldsWrinkleScore | Double | 是 | 法令纹区域得分 |
| poreArea | Double | 是 | 毛孔面积占比 |
| poreScore | Double | 是 | 毛孔得分 |
| redAcneArea | Double | 是 | 痤疮面积占比 |
| redAcneCount | Integer | 是 | 痤疮个数 |
| redAcneScore | Double | 是 | 痤疮得分 |
| sensitiveAreaArea | Double | 是 | 敏感区面积占比 |
| sensitiveAreaCount | Integer | 是 | 敏感区症状个数 |
| sensitiveAreaScore | Double | 是 | 敏感区得分 |
| sideArea | Double | 是 | 鱼尾纹面积 |
| sideWrinkleArea | Double | 是 | 鱼尾纹区域面积 |
 | sideWrinkleCnt | Integer | 是 | 鱼尾纹总数量 |
| sideWrinkleScore | Double | 是 | 鱼尾纹区域得分 |
| smallBlackHeads | Integer | 是 | 小黑头个数 |
| smallPores | Integer | 是 | 小毛孔个数(半径3像素) |
| surfaceSpotArea | Double | 是 | 表面色斑面积占比 | 
| surfaceSpotCount | Integer | 是 | 表面色斑症状个数 |
| surfaceSpotScore | Double | 是 | 表面色斑得分 |
| synAge | Double | 是 | 肤色年龄 | 
| synScore | Double | 是 | 	综合得分 |
| undereyeArea | Double | 是 | 眼下纹面积 |
| undereyeWrinkleArea | Double | 是 | 眼下纹区域面积 |
| undereyeWrinkleCnt | Integer | 是 | 眼下纹总数量 |
| undereyeWrinkleScore | Double | 是 | 眼下纹区域得分 |
| wrinkleArea | Double | 是 | 皱纹面积比 |
| wrinkleScore | Double | 是 | 皱纹综合得分 |
| wrkArea | Double | 是 | 皱纹面积 |
| wrkCount | Integer | 是 | 皱纹总数量 | 

- 错误类型说明：

| 错误类型 | 说明 |
| --- | --- |
|100001|未授权|
|100002|client应用未授权|
|100003|client应用不存在|
|100009|为指定相应类型|
|100010|用户名不存在|
|100011|账号或密码错误|
|100013|您的账户已被锁定|
|100014|您的账户已被禁用|
|100015|您的证件已过期|
|100016|无权访问|
|100017|您的接口访问次数超越上限(欠费)|
|100018|您的访问受限制|
|100021|参数异常|
|100100|clientId无效|
|100103|grant_type无效|
|100104|scope无效|
|100106|无效请求|
|100107|redirect_url无效|
|100108|grant_type无效|
|200001|token失效|
|200004|参数错误，请验证后重试|
|200015|复制图片失败|
|200019|阿里云上传失败|
|200020|未找到当前计算任务|
|200026|分析进行中,请稍后查询！|
|200027|输入图像错误！
|300001|client不存在|
|300002|应用设置失败|
|300003|您不是OEM客户|
|50003|皮肤分析分区失败|
|50004|未检测到人脸|
|50005|算法分析失败|
|80000|用户报告可用次数不足|
|999999|服务繁忙请稍后重试|
