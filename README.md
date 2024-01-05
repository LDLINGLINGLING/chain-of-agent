# chain-of-agent
多步调用的长链条Agent--在专业领域自建的工具上实现了较高准确率的长链条agent，包括任务规划和任务执行两方面
本仓库包括两方面一是任务分解，一是任务执行。原理如下
<img width="815" alt="微信图片_20240105165539" src="https://github.com/LDLINGLINGLING/chain-of-agent/assets/47373076/8498e4f0-9fd9-4b2f-8ed2-53ccf1b64a23">

任务分解包括多种模式包括商汤科技实现的TPTU模式（prompt做任务分解），全量训练模式任务分解模式，lora微调任务分解模式，以上三种模式三选一。

任务执行包括原始react模式、增强react模式、react加上relexion模式。
