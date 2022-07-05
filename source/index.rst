.. Copyright (c) 2020 Horizon Robotics.All Rights Reserved.
   The material in this file is confidential and contains trade secrets
   of Horizon Robotics Inc. This is proprietary information owned by
   Horizon Robotics Inc. No part of this work may be disclosed,
   reproduced, copied, transmitted, or used in any way for any purpose,
   without the express written permission of Horizon Robotics Inc.

.. Horizon J5 AI Toolchain User Guide documentation master file, created by
   sphinx-quickstart on Mon Aug 16 13:15:06 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

地平线J5 AI芯片工具链用户手册
==============================================================

J5 AI芯片工具链是基于地平线征程5代芯片研发的AI算法解决方案。
它包含： **模型算法处理** 和 **嵌入式模型预测库** 两大重要组件。
模型算法处理提供PTQ浮点定点模型转换方案，
支持将基于TensorFlow、PyTorch或Caffe等公开框架得到的浮点模型直接转换为定点模型。
使用方案得到的定点模型配合模型编译工具处理后就可以在地平线芯片上执行。
嵌入式模型预测库提供利用定点模型完成推理的系列支持接口。
更多有关芯片工具链的细节，请继续阅读下一章内容。

为了让开发者快速上手体验模型训练/转换、部署、验证、推理等关键步骤，芯片工具链的各组件还提供 **示例包** 
以及配合示例包使用的Docker镜像和模型发布物。 
这些示例包将各工具核心业务逻辑和关键配置参数封装成脚本；模型发布物内置了丰富的算法模型；Docker镜像预置了使用示例包所需的开发环境。

.. note::

  根据开发者使用芯片工具链的步骤，我们建议您这样使用J5 AI芯片工具链提供的文档：  


.. toctree::
   :numbered:
   :maxdepth: 2
   :caption: 本手册目录结构:

   product_introduction.rst
   env_prepare.rst
   ptq_solution.rst
   application_development.rst
   dsp.rst
   appendix.rst


