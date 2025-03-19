# 🚀 人人都是提示工程师

关注我的微信公众号获取最新推送

![wechat_qrcode](https://github.com/realyinchen/RAG/blob/main/imgs/wechat_qrcode.jpg)

随着 AI 语言模型的日益发展和广泛应用，高效与 AI 交互已成为一项重要技能。提示工程（Prompt Engineering）是解锁这些模型全部潜力的关键，它可以引导 AI 输出、提升响应质量，并解决复杂任务。本教程的目标是为学习者提供必要的知识和技能，开启提示工程的学习之旅。  

本教程全面介绍了 AI 和 LLM（大语言模型）背景下的提示工程基础概念。旨在帮助学习者建立坚实的基础，掌握如何通过精心设计的提示与 LLM 高效交互，并充分利用其能力。  

### 关键内容

本教程涵盖以下提示工程的核心内容：
- **基础概念**：介绍什么是提示工程及其重要性。
- **提示结构**：探索不同提示结构如何影响 AI 输出。
- **提示工程的重要性**：探讨提示工程对 AI 模型性能的影响。
- **在 AI 及语言模型中的作用**：分析提示工程在 AI 应用中的整体定位。
- **实践示例**：通过动手演示提示工程技巧。

### 方法细节

本教程结合理论讲解和实践演示，帮助学习者掌握提示工程的核心概念：
- **环境搭建**：首先配置必要的工具，为实验提示创建实践环境。
- **基础概念探索**：通过简单示例，展示不同提示如何影响 AI 的响应，以此说明提示工程的基本原理。
- **结构化提示**：介绍如何使用 LangChain 的 PromptTemplate 创建复杂且可复用的提示结构。
- **对比分析**：通过相同主题的不同提示，展示微小结构和措辞变化对 AI 输出的影响。
- **问题求解应用**：演示如何运用提示工程分解复杂问题，引导 AI 进行逐步推理。
- **限制规避**：展示如何通过精心设计的提示改善 AI 模型的某些局限性，例如提升事实准确性。

在整个学习过程中，本教程强调提示设计的清晰性、针对性和逻辑性，以帮助学习者构建更有效的提示。

### 最后

本教程为学习者打下提示工程的基础，使其能够更有效地与 AI 交互。完成课程后，学习者将：
- 清晰理解提示工程的概念及其重要性。
- 了解不同提示结构如何影响 AI 输出。
- 具备针对不同需求编写提示的实践经验。
- 认识提示工程在 AI 模型优化中的作用。
- 为进一步探索高级提示工程技术奠定基础。

通过本教程获得的技能和知识，将帮助学习者更高效地利用 AI 语言模型，为未来更深入的人工智能应用和研究做好准备。

### 运行环境

本教程中的代码全部在 VS Code 编辑器中使用 jupyter notebook 编写。  

首先需要安装 VS Code，[点击下载](https://code.visualstudio.com/Download)。

1. 安装 [miniconda](https://docs.anaconda.com/miniconda/miniconda-install/)
2. 创建虚拟环境  
    ```
    $ conda create -n prompt python=3.12
    ```
3. 激活虚拟环境  
    ```
    $ conda activate prompt
    ```
4. 配置 jupyter kernel  
    ```
    $ conda install -c anaconda ipykernel
    $ python -m ipykernel install --user --name prompt
    ```
5. 将项目根目录下的环境变量配置文件重命名，并根据实际情况，填入你的配置信息  
    ```
    $ mv .example.env .env
    ```

6. 安装依赖包
    ```
    pip install -r requirements.txt
    ```

# 鸣谢

本教程灵感来自 [Prompt_Engineering](https://github.com/NirDiamant/Prompt_Engineering)  
