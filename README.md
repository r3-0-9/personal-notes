ReadNoteGen - 基于InternLM的读书笔记生成助手

功能描述:

ReadNoteGen 助手旨在帮助用户从阅读的书籍中提取关键信息，生成结构化的读书笔记，并通过RAG技术增强笔记的内容丰富性和准确性。

系统流程:

用户通过UI界面上传书籍文件或输入书籍摘要。
后端服务器接收文件，进行文本预处理。
RAG模块检索相关信息并增强输入文本。
InternLM模型生成读书笔记。
生成的笔记返回给前端，并展示给用户。
用户可以编辑、保存和分享笔记。

需用的模块：
Ddtdsets-model
Text Preprocessing Module
RAG Enhancement Module
Note Generation Module

