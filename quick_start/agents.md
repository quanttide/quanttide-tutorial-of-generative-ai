# 智能体

## 定义

Agent = Model + Memory + Planning + External Tools

以写代码的[Duckie AI](duckie.ai)为例。

Memory: Model是不知道你自己项目的信息的，你需要补充给他；一般就是通过向量数据库存向量，或者图数据库存知识图谱。

Planning: 然后假设你问开发者需要怎么写这个项目，也就是要制定计划

External Tools: 然后比如说直接去你的GitHub仓库操作，这就是External Tools。之前不是说chatgpt也能写代码嘛？ChatGPT可以生成代码，他不能直接操作你的代码，编辑你要写在某个位置的代码 并且运行。

## 使用

和ChatGPT差不多。输入文本，让他学习，然后再按照你的要求输出结果？

## 多智能体

Multi-Agent

目前的大模型只有在任务非常明确的情况下，而且业务背景不多的情况下可以。它不能一步就做了。
解决这种问题，可以让多个Agent协作；也就是所谓的Multi-Agent。
可以再加一个步骤把业务逻辑翻译成代码任务，需要两个Agent 一个翻译业务逻辑成算法逻辑，一个实现算法逻辑
Muiti的问题就在于你要怎么定义Agent协作的过程。
