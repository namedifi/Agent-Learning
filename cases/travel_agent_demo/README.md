# 智能旅行助手 Demo

本案例实现了一个基于 Thought-Action-Observation 范式的简单智能体。

## 功能说明

用户输入：

“你好，请帮我查询一下今天北京的天气，然后根据天气推荐一个合适的旅游景点。”

智能体会完成以下步骤：

1. 调用天气查询工具获取北京实时天气；
2. 根据天气情况调用 Tavily 搜索工具推荐旅游景点；
3. 最后由大语言模型整合天气和景点信息，生成最终回答。

## 使用技术

- Python
- requests
- openai
- tavily-python
- DeepSeek API
- Tavily Search API

## 安装依赖

```bash
pip install -r requirements.txt
