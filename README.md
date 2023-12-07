# WFL (Wild Life Tech) 🐆🐆
![logo](https://github.com/dmargni/WLT/assets/142944606/843419f4-8402-4901-a67d-a683365932f6)

## Our Mission 📊

WildCatAI Solutions is committed to harnessing advanced AI technology to champion the conservation and safeguarding of cheetahs and leopards. Our mission is to avert the extinction of these majestic big cats by delivering precise and streamlined identification and monitoring solutions. Through the implementation of AI-driven recognition and data collection, we empower researchers, conservationists, and local communities to protect these species and their ecosystems effectively. Collaboratively, we strive towards a future where cheetahs and leopards flourish in their natural habitats, contributing to the equilibrium and biodiversity of our planet's ecosystems.

# Challenges Faced

## Endangered Species

**Cheetahs and leopards** face the imminent threat of extinction due to habitat loss, poaching, and human-wildlife conflict.

Cheetahs and leopards are listed as endangered species, meaning they are at a high risk of extinction in the wild. This is primarily due to several threats, including habitat loss, poaching, and human-wildlife conflict.

### Examples:
- **Habitat Loss:** Urbanization, deforestation, and agricultural expansion are leading to the loss of natural habitats for cheetahs and leopards.
- **Poaching:** Illegal hunting for their skins, bones, and other body parts contributes to the decline in population.
- **Human-Wildlife Conflict:** Encounters between these big cats and human populations often result in conflicts, as they may prey on livestock or be perceived as a threat to human safety.

## Habitat Preservation

Protecting their natural habitats is essential for the survival of these magnificent big cats.
Preserving and preserving their natural habitats of cheetahs and leopards is crucial for their survival. It involves conserving and protecting the ecosystems they inhabit.

### Examples:
- **Wildlife Reserves:** Establishing and maintaining protected areas and wildlife reserves where these big cats can live undisturbed.
- **Corridor Conservation:** Creating wildlife corridors that connect fragmented habitats, allowing for the natural movement of cheetahs and leopards.

## Human-Wildlife Conflict
Addressing conflicts between humans and big cats is essential for fostering coexistence and reducing threats to both communities and predators.

### Examples:
- **Community Education:** Educating local communities about the behavior of cheetahs and leopards to minimize misunderstandings and conflicts.
- **Livestock Protection:** Implementing measures to protect livestock, such as secure enclosures, to reduce economic losses and retaliation against predators.

## Anti-Poaching

Combating illegal hunting and the trade of cheetahs and leopards is crucial to halt their population decline.

### Examples:
- **Increased Surveillance:** Deploying patrols, technology, and surveillance to monitor and protect areas with high concentrations of these big cats.
- **Legislation and Enforcement:** Strengthening laws against poaching and illegal wildlife trade, and enforcing penalties for offenders.

## Genetic Diversity

Ensuring genetic diversity is vital for the long-term health and adaptability of cheetah and leopard populations.

### Examples:
- **Breeding Programs:** Implementing managed breeding programs in captivity to maintain genetic diversity and prevent inbreeding.
- **Translocation:** Introducing individuals from one population to another to increase genetic diversity and strengthen overall resilience.
  
![1_P0hday68KcoQk3y8U_ddVg](https://github.com/dmargni/WLT/assets/142944606/81989fbe-7b21-4bc2-b1c3-ecd89a9a0545)

![8869249_orig](https://github.com/dmargni/WLT/assets/142944606/33ce1076-90ea-472f-82fa-0e8d63d47671)


# Differentiating Cheetahs and Leopards 🕵🏼‍♀

Thanks to advancements in deep learning Wildlife Learning Technology (WLT) is now equipped with the capability to differentiate between cheetahs and leopards. This is a significant breakthrough in wildlife conservation, as it allows for more accurate monitoring and protection measures tailored to the specific needs of these endangered big cats


![download](https://github.com/dmargni/WLT/assets/142944606/6674d0b8-6b52-4540-9030-0e60ce4f368c)

![download (1)](https://github.com/dmargni/WLT/assets/142944606/62c94aab-70f6-46c4-985d-14e4eabebe5c)


[Data Set](https://docs.google.com/presentation/d/1ZXgAwMkZ5psxx5oAEgRVIGIDhpJwkwVEdEmg_vIIRdw/edit#slide=id.g1e5fe555a3f_0_2)

# AlexNet in order to detect 

AlexNet, a pioneering convolutional neural network (CNN), secured victory in the 2012 ImageNet Large Scale Visual Recognition Challenge. Created by Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton, AlexNet marked a breakthrough in deep learning for image classification. This summary highlights key features:

## Features:

1. **Architecture:**
   - Eight layers, including five convolutional and three fully connected layers.
   - Convolutional layers followed by max-pooling for non-linearity and spatial reduction.

2. **Activation:**
   - Rectified Linear Unit (ReLU) used after each layer for non-linearity.

3. **Normalization:**
   - Local Response Normalization (LRN) applied in initial layers to enhance generalization.

4. **Regularization:**
   - Dropout in fully connected layers to prevent overfitting.

5. **Data Augmentation:**
   - Techniques like random cropping and flipping employed for better generalization.

## Differentiating Cheetahs and Leopards:

AlexNet excels in distinguishing cheetahs and leopards:

1. **Feature Extraction:**
   - Convolutional layers identify patterns, textures, and shapes distinctive to each species.

2. **Learning Features:**
   - AlexNet learns discriminative features during training, recognizing unique spots and coat patterns.

3. **Classification:**
   - Fully connected layers classify images based on learned features, assigning probabilities to each category.

4. **Fine-Tuning:**
   - Fine-tuning on a specific dataset optimizes AlexNet for the cheetah vs. leopard task.

Leveraging AlexNet's capabilities allows precise differentiation between these big cat species.

[AlexNet](https://colab.research.google.com/drive/1_mpZhC_9GDFmjIoAXcNa0t6rIwbCSpwm#scrollTo=uzRsuDek9Fve)

# Feature map

A feature map, in the context of convolutional neural networks (CNNs), is a spatial representation of learned features extracted from input data, such as images. It is generated by applying convolutional filters (kernels) to the input data, capturing specific patterns, textures, or structures. Each channel in the feature map corresponds to the activation of a particular filter, highlighting the presence of certain features in the input.

In the context of cheetah and leopard detection, feature maps play a crucial role by focusing on specific visual cues such as spotting and stripe patterns in the animals' fur. Designed filters within the feature maps are tuned to capture these distinctive characteristics. Furthermore, deeper layers of the convolutional neural network (CNN) contribute to recognizing the overall texture and shape of the animals, encompassing details like the size, shape, and distribution of spots or stripes unique to cheetahs and leopards. As the CNN undergoes training, discriminative features are learned within the feature maps, facilitating the distinction between cheetahs and leopards based on variations in fur color, unique markings, and other visually distinct attributes. The final layers of the CNN utilize these extracted features to make a classification decision, with the feature maps serving as input to fully connected layers that analyze the learned features and determine whether the input corresponds to a cheetah or a leopard.


![download (1)](https://github.com/dmargni/WLT/assets/142944606/d24b048f-f232-41df-acdf-30c8eaf1f2ad)

[Filters](https://colab.research.google.com/drive/19z5zCgsF2AckH3oDRpenaArK6cz2htcD#scrollTo=mQb-EZfpq-N8)

# SPM is able to identify poses

The **Simple Pose Machine** is a model employed for human pose estimation within the domains of computer vision and deep learning. Pose estimation encompasses the task of identifying and localizing key body joints or keypoints in an image or video. The overarching objective is to deduce the positions of crucial body parts, including the head, shoulders, elbows, wrists, hips, knees, and ankles.

In this case it is designed in order to detect key feature in cheetas and leopard running. Since they are very fast animals and it's very hard to recognize them, SPM is helful in detecting the key features of the running if these two cats.

![download (2)](https://github.com/dmargni/WLT/assets/142944606/382b9180-d555-46e7-aabd-c9b2bf2a8a75)

# Model 








![download (1)](https://github.com/dmargni/WLT/assets/142944606/95e5aeed-ab45-4a2f-90b3-5aaed34c73c6)

[SPM](https://colab.research.google.com/drive/14_s2r56w_aT36364h4lTn-YsEXVfEJCh#scrollTo=VHmTwACwFW-v)

