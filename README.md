# RAG
在github原有的rag项目上添加自己微调的embedding模型以及添加微调的vl模型

原本的项目在https://datawhalechina.github.io/all-in-rag/#/上面进行学习，近期学了大模型微调，因此使用对embedding模型进行了微调，由于数据的限制，因此只能是熟悉流程，而不能保证准确性。
微调的embedding模型是Qwen3-embedding模型，而且为了丰富这个框架，添加了一个微调的Qwen3-vl模型，以此用来识别菜品名称。

这个项目里面包含两类模型微调的组成，以及简单的微调数据构造，由于vl微调的数据匹配度较低，因此不能保证准确度，仅用来熟悉。
