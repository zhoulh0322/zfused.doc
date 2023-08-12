## 场景元素拆分
在已经制作出一版场景文件的情况下，首先要将场景文件拆成单个场景元素分别发布，之后再重新领取拼装
拆分步骤说明：
 1. 制片根据需求统计场景元素拆分情况，并在zFused上创建好需要拆出的场景元素资产和对应任务
 2. 场景模型艺术家拆分场景元素，将大场景文件拆分成单个小场景元素文件，拆分时有以下几点需要注意
    + 场景元素本质上是资产的一种类型，在每个资产环节都需要符合对应的制作规范，最初在模型拆分时要符合模型规范
    + 单个场景元素要归于原点发布
 
    ![](../../maya/images/scheme/assembly_display.png ':size=600')
 3. 单独的场景元素拆分完成后按照模型规范发布到对应的模型任务环节  
 ![](../../maya/images/scheme/env_publish.png ':size=600')

## 场景元素拼装
在zFused资产中领取已上传通过的场景元素，可以选择领取文件/gpu/ass/usd等格式的文件，文件包含的格式由模型发布时的配置选择，具体需求可以联系我方技术人员，领取后根据场景文件内各元素所在的位置，摆放在相同的位置

1. 点击`utility` > `场景单元（元素）管理`
2. 筛选环节，这里勾选场景元素
3. 点击`所有元素`，面板内展示的是目前所有上传并通过的场景元素
4. 找到目标元素，支持搜索框内中英文关键字查找
5. 在目标元素上右键选择`导入`或者点击下方的`导入GPU文件`
6. 点击`当前场景元素`，面板内展示的是所有系统识别到当前场景内存在的场景元素，可以在这里快速切换场景元素的环节和版本

![](../../maya/images/scheme/assembly_step.png ':size=1000')
![](../../maya/images/scheme/scene_env.png ':size=700')
