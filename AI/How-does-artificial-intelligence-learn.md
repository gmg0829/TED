# How does artificial intelligence learn?(人工智能是如何学习的？)


- Today, artificial intelligence helps doctors diagnose patients, pilots fly commercial aircraft, and city planners predict traffic. But no matter what these AIs are doing, the computer scientists who designed them likely don’t know exactly how they’re doing it. This is because artificial intelligence is often self-taught, working off a simple set of instructions to create a unique array of rules and strategies. So how exactly does a machine learn? 

- 如今的人工智能 可以帮助医生诊断病人， 飞行员驾驶商业飞机， 城市规划员预测交通。 但不论人工智能如何运作 设计它们计算机科学家 却可能不知道其具体运作方法。 这是因为人工智能常有自学能力， 它们会根据设定好的程序指令 创造一套独特的规则和策略。 那么机器到底是如何自主学习的？ 


- There are many different ways to build self-teaching programs. But they all rely on the three basic types of machine learning: unsupervised learning, supervised learning, and reinforcement learning. To see these in action, let’s imagine researchers are trying to pull information from a set of medical data containing thousands of patient profiles.

- 创建自学程序的方法有很多种。 但它们都依赖三种基础机器学习方法： 无监督学习、监督学习，和强化学习。 来看看它们的真实运作情况， 先想象一下，研究员正尝试 从一组包含了几千名患者的 医疗资料中提取信息。 

- First up, unsupervised learning. This approach would be ideal for analyzing all the profiles to find general similarities and useful patterns. Maybe certain patients have similar disease presentations, or perhaps a treatment produces specific sets of side effects. This broad pattern-seeking approach can be used to identify similarities between patient profiles and find emerging patterns, all without human guidance. 

- 首先，是无监督学习。 此方法适用于通过分析所有资料 来获取大体的相似性和有用的模式。 也许某些患者有类似的疾病表现， 抑或治疗会产生特定的副作用。 这种广泛的模式寻找方法 可以用来识别患者 档案之间的相似之处， 并发现新出现的模式， 所有这些都无需人类的指导。 


- But let's imagine doctors are looking for something more specific. These physicians want to create an algorithm for diagnosing a particular condition. They begin by collecting two sets of data— medical images and test results from both healthy patients and those diagnosed with the condition. Then, they input this data into a program designed to identify features shared by the sick patients but not the healthy patients. Based on how frequently it sees certain features, the program will assign values to those features’ diagnostic significance, generating an algorithm for diagnosing future patients. However, unlike unsupervised learning, doctors and computer scientists have an active role in what happens next. Doctors will make the final diagnosis and check the accuracy of the algorithm’s prediction. Then computer scientists can use the updated datasets to adjust the program’s parameters and improve its accuracy. This hands-on approach is called supervised learning. 


- 但让我们想象一下医生 在寻找更具体的东西。 这些医生想要创建一种算法 来诊断特定的疾病。 他们首先收集两组数据： 健康患者和确诊患者的 医学图像和测试结果。 然后，他们将这些数据输入一个程序， 该程序旨在识别患病患者 而非健康患者共有的特征。 根据看到某些特征的频率， 该程序将对这些特征的诊断意义赋值， 生成一种用于诊断未来患者的算法。 然而，与无监督学习不同的是， 医生和计算机科学家在接下来 发生的事情中扮演着重要的角色。 医生将做出最终诊断， 并检查算法预测的准确性。 然后，计算机科学家 可以使用更新的数据集 来调整程序的参数，并提高其准确性。 这种亲身实践的方法被称为监督学习。 


- Now, let’s say these doctors want to design another algorithm to recommend treatment plans. Since these plans will be implemented in stages, and they may change depending on each individual's response to treatments, the doctors decide to use reinforcement learning. This program uses an iterative approach to gather feedback about which medications, dosages and treatments are most effective. Then, it compares that data against each patient’s profile to create their unique, optimal treatment plan. As the treatments progress and the program receives more feedback, it can constantly update the plan for each patient. None of these three techniques are inherently smarter than any other. While some require more or less human intervention, they all have their own strengths and weaknesses which makes them best suited for certain tasks. However, by using them together, researchers can build complex AI systems, where individual programs can supervise and teach each other. For example, when our unsupervised learning program finds groups of patients that are similar, it could send that data to a connected supervised learning program. That program could then incorporate this information into its predictions. Or perhaps dozens of reinforcement learning programs might simulate potential patient outcomes to collect feedback about different treatment plans. 


-  现在，假设这些医生想设计另一种算法 来推荐治疗方案。 由于这些计划将分阶段实施， 并可能根据每个人 对治疗的反应而改变， 医生决定使用强化学习。 这个程序使用一种迭代的方法 来收集关于哪种药物、 关于哪种药物、剂量和治疗 最有效的反馈。 然后，它将这些数据 与每个患者的档案进行比较， 以创建他们独特的、最佳的治疗方案。 随着治疗的进展 和程序收到更多的反馈， 它可以不断更新每个患者的计划。 这三种技术中没有哪一种 天生就比其他的更聪明。 虽然有些需要或多或少的人工干预， 但它们都有自己的优缺点， 这使它们最适合某些任务。 然而，通过将它们一起使用， 研究人员可以构建 复杂的人工智能系统， 其中单个程序可以相互监督和指导。 例如，当我们的非监督学习程序 发现相似的患者群体时， 它可以将这些数据发送到 连接的监督学习程序。 然后该程序将这些信息纳入其预测。 或者，数十个强化学习项目 可能会模拟潜在的患者结果， 以收集关于不同治疗计划的反馈。



- There are numerous ways to create these machine-learning systems, and perhaps the most promising models are those that mimic the relationship between neurons in the brain. These artificial neural networks can use millions of connections to tackle difficult tasks like image recognition, speech recognition, and even language translation. However, the more self-directed these models become, the harder it is for computer scientists to determine how these self-taught algorithms arrive at their solution. Researchers are already looking at ways to make machine learning more transparent. But as AI becomes more involved in our everyday lives, these enigmatic decisions have increasingly large impacts on our work, health, and safety. So as machines continue learning to investigate, negotiate and communicate, we must also consider how to teach them to teach each other to operate ethically. 

- 有许多方法可以创建 这些机器学习系统， 而最有希望的模型可能是 那些模拟大脑神经元之间关系的模型。 这些人工神经网络 可以使用数百万个连接 来处理图像识别、语音识别 甚至语言翻译等困难任务。 然而，这些模型越自我指导， 计算机科学家就越难确定 这些自学的算法是如何得到 它们的解决方案的。 研究人员已经在寻找 让机器学习更透明的方法。 但随着人工智能越来越多地 参与到我们的日常生活中， 这些神秘的决定对我们的工作、 健康和安全产生越来越大的影响。 因此，在机器继续学习调查、 谈判和沟通的同时， 我们也必须考虑如何教它们 彼此如何合乎道德地操作。 