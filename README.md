# 🚬 本工具集利用deepseek辅导开发完成，有些功能还待更多测试完善，有兴趣的朋友可自行下载安装插件，在使用过程中遇到的问题，请提交详细到issue，收到反馈后我会第一时间处理，谢谢！

## 安装插件
|方式一|
|------|
|ComfyUI管理器节点中搜索：ComfyUI-AlwaysOnline > install|

|方式二|
|------|
|git拉取到ComfyUI目录custom_nodes文件夹下 > 拉取后重启ComfyUI|
```
git clone https://github.com/alwaysOnlineYou/ComfyUI-AlwaysOnline.git
```

## GLM-4V推理节点共有两个：一个是图像反推，另一个是纯文本反推，纯文本反推支持系统角色和用户输入
|必须安装|
|------|
|首先，从源代码安装transformers：|
```
pip install git+https://github.com/huggingface/transformers.git
```
