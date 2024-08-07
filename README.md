# To Do
1. How to identify wheather the patient AD is genetic
2. Early diagnosis
3. disease progression predection using longitudinal patient data


# Alzheimer's disease detection

What is Alzheimer:
Alzheimer's is a type of dementia that affects memory, thinking, and behavior. Symptoms eventually grow severe enough to interfere with daily tasks.
Alzheimer's is the most common cause of dementia, a general term for memory loss and other cognitive abilities serious enough to interfere with daily life. Alzheimer's disease accounts for 60-80% of dementia cases.
Source: https://www.alz.org/alzheimers-dementia/what-is-alzheimers

Cause of Alzheimer: 
Alzheimer's disease is thought to be caused by the abnormal build-up of proteins in and around brain cells. One of the proteins involved is called amyloid, deposits of which form plaques around brain cells. The other protein is called tau, deposits of which form tangles within brain cells. Although it's not known exactly what causes this process to begin, scientists now know that it begins many years before symptoms appear. As brain cells become affected, there's also a decrease in chemical messengers (called neurotransmitters) involved in sending messages, or signals, between brain cells. Levels of one neurotransmitter, acetylcholine, are particularly low in the brains of people with Alzheimer's disease. Over time, different areas of the brain shrink. The first areas usually affected are responsible for memories. In more unusual forms of Alzheimer's disease, different areas of the brain are affected. The first symptoms may be problems with vision or language rather than memory.
Source: https://www.nhs.uk/conditions/alzheimers-disease/causes/#:~:text=Alzheimer's%20disease%20is%20thought%20to,form%20tangles%20within%20brain%20cells.

Age is the biggest known risk factor for Alzheimer’s. Most people with Alzheimer’s develop the disease when they are 65 or older, with less than 10% of cases occurring before then. As a person ages past 65, their risk of Alzheimer’s increases. About one in 13 people 65 to 84 and one in three people 85 and older live with Alzheimer’s.
One of the great mysteries of Alzheimer’s is why it largely affects older adults. Research on normal brain aging is exploring this question. For example, scientists are learning how age-related changes in the brain may harm neurons and affect other types of brain cells to contribute to Alzheimer’s damage.
These age-related changes include:
Shrinking of certain brain regions
Inflammation
Blood vessel damage
The production of unstable molecules called free radicals
Decreased energy production within cells.
Source: https://www.nia.nih.gov/health/alzheimers-causes-and-risk-factors/what-causes-alzheimers-disease#:~:text=Age%20is%20the%20biggest%20known,their%20risk%20of%20Alzheimer's%20increases.

Alzheimer diagnosis:
Doctors use several methods and tools to help determine if a person with thinking or memory problems has Alzheimer’s disease. To diagnose Alzheimer’s, doctors may:
Ask the person experiencing symptoms, as well as a family member or friend, questions about overall health, use of prescription and over-the-counter medicines, diet, past medical problems, ability to carry out daily activities, and changes in behavior and personality.
Conduct tests of memory, problem solving, attention, counting, and language.
Order blood, urine, and other standard medical tests that can help identify other possible causes of the problem.
Administer a psychiatric evaluation to determine if depression or another mental health condition is causing or contributing to a person's symptoms.
Collect cerebrospinal fluid (CSF) via a spinal tap and measure the levels of proteins associated with Alzheimer’s and related dementias.
Perform brain scans, such as computed tomography (CT), magnetic resonance imaging (MRI), or positron emission tomography (PET), to support an Alzheimer’s diagnosis or rule out other possible causes for symptoms.
Source: https://www.nia.nih.gov/health/alzheimers-symptoms-and-diagnosis/how-alzheimers-disease-diagnosed

What is Convolutional Nueral Network:
A Convolutional Neural Network (CNN) is a type of deep learning algorithm that is particularly well-suited for image recognition and processing tasks. It is made up of multiple layers, including convolutional layers, pooling layers, and fully connected layers. The architecture of CNNs is inspired by the visual processing in the human brain, and they are well-suited for capturing hierarchical patterns and spatial dependencies within images.
Key components of a Convolutional Neural Network include:
Convolutional Layers: These layers apply convolutional operations to input images, using filters (also known as kernels) to detect features such as edges, textures, and more complex patterns. Convolutional operations help preserve the spatial relationships between pixels.
Pooling Layers: Pooling layers downsample the spatial dimensions of the input, reducing the computational complexity and the number of parameters in the network. Max pooling is a common pooling operation, selecting the maximum value from a group of neighboring pixels.
Activation Functions: Non-linear activation functions, such as Rectified Linear Unit (ReLU), introduce non-linearity to the model, allowing it to learn more complex relationships in the data.
Fully Connected Layers: These layers are responsible for making predictions based on the high-level features learned by the previous layers. They connect every neuron in one layer to every neuron in the next layer.
Source: https://www.geeksforgeeks.org/convolutional-neural-network-cnn-in-machine-learning/


# Introduction
Alzheimer’s disease (AD) is a fatal irreversible, progressive neurodegenerative disorder that causes brain cells to waste away and die. Typically, AD begins in middle/old age, with protein accumulation inside/around neurons. The most prevalent and one of the early symptoms of AD is problems remembering new things, since AD-related changes usually begin in the brain parts charged with learning. Symptoms include, but are not limited to, behavioral changes; deep confusion regarding time, events, and places; and doubts about family members and friends. They usually develop slowly and worsen over time, leading to a continual deterioration in memory and difficulty in swallowing, talking, and walking.1–3

AD is the prevalent dementia type, which includes about 60% to 80% of the total cases of dementia.1 Dementia refers to severe loss of memory and other cognitive capabilities that interfere with daily life. It is estimated to have affected about 50 million people in the world and 459,000 Australians in 2020.1,4 The statistics are estimated to almost double every 20 years.5 Dementia is the second leading cause of death among Australians, accounting for 15,016 deaths in 2019.6

Despite exploring various treatments for preventing or slowing AD, the success rate has been low, particularly in the latest phases of the disease.7 Studies indicate that AD-related changes in the brain might begin about 20 years before symptoms emerge.1 Therefore, there is a time gap that could be highly valuable to slowing AD’s progression. Early detection of AD extends the independence of patients for a longer period. Recent research may enable greater comprehension of the disease and improvement of new treatments.

In practice, AD detection is based on checking brain scans, a clinical assessment, and asking questions of the patient and their relatives. This process is usually challenging because of the limited knowledge in identifying the parts of the brain affected by AD. Moreover, AD symptoms, like brain shrinkage, can also be observed in healthy, elderly normal control (NC) groups. In the last two decades, a wide range of studies has been performed to detect AD using artificial intelligence. Common classification algorithms in machine learning, such as neural networks and support vector machines (SVMs), have been applied to brain scans such as positron emission tomography (PET) and magnetic resonance imaging (MRI). Detecting AD using these algorithms is difficult for scholars because of the low image quality, issues of brain segmentation and preprocessing steps, the absence of a database with a sufficient number of subjects, and the complexity of medical images. Successful classification necessitates a robust power to distinguish specific features in similar brain images. In a systematic literature review, 18 of 114 reviewed studies compared deep learning models with machine learning models. They all reported the superiority of the former. Therefore, in this paper, we only investigate and compare deep learning models.

The rise in the computation capacity of graphics processing units (GPUs) has supported the evolution of modern and innovative deep learning algorithms. As a subgroup of machine learning, deep learning models analyze data processing and pattern recognition in the human brain to solve complicated decision-making tasks. Deep learning approaches have enhanced intelligent systems in numerous areas.14 Research on medical images has been encouraged by deep learning methods in applications using two-dimensional (2D) natural images.15,16 Among deep learning models, convolutional neural networks (CNNs) have recently demonstrated revolutionized outcomes in disease detection and organ segmentation.17 In contrast to traditional machine learning methods, CNNs can merge three main steps of classification: feature extraction, feature selection, and classification. It was recently stated that CNNs are the most frequently used method—about 70%—for AD detection.13

MRI is the most extensively utilized biomarker for the detection of AD using deep learning. It has been used in more than 80% of AD detection studies in single-modal approaches. This paper plans to use MRI scans to classify AD patients from NCs using CNNs. We aim to use CNNs to uncover latent representations, discover relationships among slices of images, and recognize patterns related to AD in brain scans. Our research’s main contribution is to expand the idea of transfer learning from 2D images to three-dimensional (3D) MRI scans. Hence, learnable parameters from 2D CNNs are transferred to 3D CNNs. To begin, the related work is first outlined to present the structure of CNNs and the background of employing 2D and 3D CNNs in AD detection using neuroimaging. Next, different types of CNNs in 2D and 3D approaches to manage MRI volumes with or without transfer learning are examined in detail. Subsequently, our proposed deep model for introducing the concept of transfer learning to 3D CNNs is explained. Finally, experimental results are discussed, followed by the conclusion.
