#### 端到端模型

- 非端到端

传统的机器学习流程由多个独立的模块组成，每个步骤是一个独立的任务，其结果的好坏会影响到下一步骤，从而影响整个训练结果。

- 端到端

端到端的学习其实就是不做其他额外处理，从原始数据输入到任务结果输出，整个训练和预测过程，都是在模型里完成的。

从输入端到输出端会得到一个预测结果，将预测结果和真实结果进行比较得到误差，将误差反向传播到网络的各个层中，调整网络的权重和参数制动模型收敛或者达到预期的效果为止，中间所有操作都包含在神经网络内部，不再分成多个模块处理。由原始数据输入，到结果输出，从输入端到输出端，中间的神经网络自成一体。