## 功能介绍
1. 聊天模式【开发完成】：更适合创作灵感收集，以思源笔记内容作为知识库，通过问答的方式，让大模型去检索笔记或联网搜索相关内容，生成新的内容。将自己满意的内容先写入到文档中，再通过指令模式，让大模型对文档进行润色、扩写等。
2. 指令模式【开发完成】：参考 notion.ai ，更适合文本编辑，比如对现有文本进行润色、扩写等。有prompt面板，可以对prompt进行增删改查。

### 聊天模式
快捷键【mac】： option + command + L

快捷键【windows】： alt + win + L

![聊天模式](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/chat.png)

### 指令模式
快捷键【mac】：option + command + K

快捷键【windows】：alt + win + K

​![指令模式](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/yyy.jpg)​
![模型](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/%E6%A8%A1%E5%9E%8B.png)
![超参数面板](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/%E8%B6%85%E5%8F%82%E6%95%B0%E9%9D%A2%E6%9D%BF.png)

## 联网搜索
![](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/%E6%8C%87%E4%BB%A4%E6%A8%A1%E5%BC%8F%E8%81%94%E7%BD%91%E6%90%9C%E7%B4%A2.png)
![](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/%E6%8C%87%E4%BB%A4%E6%A8%A1%E5%BC%8F%E8%81%94%E7%BD%91%E6%90%9C%E7%B4%A2%E7%94%9F%E6%88%90.png)
![](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/%E8%81%8A%E5%A4%A9%E6%A8%A1%E5%BC%8F%E8%81%94%E7%BD%91%E6%90%9C%E7%B4%A2.png)
![](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/%E8%81%8A%E5%A4%A9%E6%A8%A1%E5%BC%8F%E8%81%94%E7%BD%91%E6%90%9C%E7%B4%A2%E7%BB%93%E6%9E%9C.png)

## 显示deepseek 深度思考过程
![深度思考](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/%E6%98%BE%E7%A4%BA%E6%8E%A8%E7%90%86%E8%BF%87%E7%A8%8B.png)


## 知识库
知识库概念：所有的笔记内容的集合。
开启方式在超参数中开启知识库功能。
![知识库-聊天模式](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/knowledge_chat.png)
![知识库-指令模式](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/knowledge_instruction.png)

## 图像理解
![图像理解上](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/1738843990689.png)
![图像理解下](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/1738885335871.png)

## 基于文档的问答
** 暂不支持pdf【开发中...】 **
![文档问答](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/fileask.png)

## 支持模型
1. DeepSeek Chat
2. DeepSeek Reasoner
3. Moonshot Chat
4. Qwen Turbo
5. Qwen Plus
6. Qwen Max
7. Doubao 1.5 Lite
8. Doubao 1.5 Pro
9. GPT 4o
10. GPT o3 mini
11. GPT 4 Turbo
12. Claude 3.5 Haiku
13. Claude 3.5 Sonnet
14. Claude 3 Opus


## TODO
- [x] 指令模式
- [x] 使用/召唤指令面板、对prompt进行增删改查
- [x] 指令模式可以随时切换模型、调整超参数
- [x] 新增moomshot、deepseek reasoner模型
- [x] 新增chatgpt模型
- [x] 聊天模式基础功能开发：可以输入文本，生成文本，新建聊天框
- [x] 聊天模式自动生成聊天标题
- [x] 聊天模式将生成气泡的markdown格式进行渲染
- [x] 聊天模式可以删除历史聊天记录
- [x] 聊天模式使用/召唤指令面板、对prompt进行增删改查
- [x] 聊天模式可以随时切换模型
- [x] 聊天模式可以调整超参数
- [x] 聊天模式完善工具栏图标
- [ ] 支持文生图模型【根据文本生成图片】
- [x] 图像理解【根据图片生成文本，或者对图片进行问答】
- [x] 支持联网搜索功能
- [x] 支持文件上传，文件问答功能【pdf问答开发中...】
- [x] 笔记内容问答功能【知识库功能】

## TODO【优化】
- [x] 知识库增加存云端和存本地的选项【高优】
- [x] 添加排除笔记本功能
- [x] 对联网功能的长度进行限制
- [x] 排除手机端
- [x] 自定义指令模式和聊天模式的快捷键【高优】
- [ ] 优化UI 【高优】
- [ ] 增加自定义快捷键功能
- [ ] 增加对word 和 pdf 解析功能【次高优】
- [ ] 增加对生成内容中引用链的浮框显示功能
- [ ] 增加对流式输出打断功能
- [ ] 增加对聊天气泡的编辑、删除功能
- [ ] 添加 @日记 功能，对日记进行回忆或总结
- [ ] 用户反馈：开启知识库，回答上下文没有引述块内容。


## 反馈 
![qq群：710607849](https://pub-a4fc15e05e5b45ae93e81825f01bfb69.r2.dev/file-repository/files/%E5%BD%92%E6%A1%A3_1737019531739/qq.jpg)