# BlindMate: Empowering Accessibility for the Visually Impaired  ![blind (1)](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/ef5d1063-b162-4fde-b49f-acfb86aa1922)


## Introduction  ![racing-flag](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/ee9b7e79-c965-42b1-8bbf-3d6e2ff433c4)


Welcome to BlindMate – your smart accessibility assistant designed to transform the lives of visually impaired individuals. Our project is driven by a deep-rooted desire to make the world a more inclusive and accessible place for everyone. We believe that technology has the power to bridge gaps, and it's this belief that inspired us to embark on this journey.

## The Inspiration  ![thought-leadership](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/45360273-0ed8-446c-aa31-d89ab5c09da1)

Imagine a world where people with visual impairments can independently navigate their surroundings, identify objects, access information effortlessly, and even recognize currency notes. The inspiration for BlindMate comes from a profound understanding of the challenges faced by visually impaired individuals on a daily basis, coupled with the realization that technology can be a game-changer.

## Relating Real-World   ![research](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/8aa799db-afb4-4ec3-865b-6f7a8496c54c)

#### Empowering Independence

Our inspiration draws from countless stories of individuals who are determined to live life to the fullest despite their visual impairments. People like Stevie Wonder and Haben Girma have shown us the incredible potential that can be unlocked when accessibility barriers are removed.

#### Innovative Solutions 

The rise of smart devices and AI has paved the way for innovative accessibility solutions. BlindMate is inspired by projects like "Be My Eyes," an app connecting blind users with sighted volunteers for real-time assistance, and "Seeing AI" from Microsoft, which uses AI to provide detailed descriptions of the visual world.

#### Impactful Research: Studies like "The Impact of Technology on Blind and Visually Impaired People" have underscored the importance of technological advancements in enhancing the quality of life for visually impaired individuals.

## Our Vision  ![idea](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/74b5e4c6-81eb-47f8-bd32-a90d9c68676e)

At BlindMate, our vision is to empower visually impaired individuals with a tool that not only assists them in their daily activities but also enhances their confidence and autonomy. Through cutting-edge technologies like image recognition, voice commands, and AI-driven text-to-speech conversion, we aim to create an inclusive environment where the visually impaired can navigate, explore, and engage with the world around them.

## What BlindMate Does?  ![shrug](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/2cc3e9b2-9c4b-4606-a91e-38af318b78d4)

BlindMate is a comprehensive smart accessibility assistant that offers a range of features to empower visually impaired individuals:

#### Object and Scene Recognition 
BlindMate uses advanced image recognition techniques to identify and describe objects and scenes captured by smartphone cameras. Users receive detailed auditory descriptions of their surroundings.

#### Currency Recognition
BlindMate can accurately recognize and identify various currency notes. Users can simply capture an image of a currency note, and BlindMate will provide an auditory description of the note's denomination.

#### Text-to-Speech Conversion
BlindMate converts text in images to natural-sounding speech, providing instant access to printed information. This feature proves invaluable for reading labels, signs, and other textual content.

#### Voice Commands
Users can interact with BlindMate using voice commands, enabling hands-free navigation and information retrieval. Whether it's identifying objects or requesting specific information, BlindMate is ready to assist.

## Use Of Intel oneAPI  ![oneAPI](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/9a067f54-ceca-4365-99cb-29de18083a35)

Intel OneAPI is a comprehensive development platform for building high-performance, cross-architecture applications. It provides a unified programming model, tools, and libraries that allow developers to optimize their applications for Intel CPUs, GPUs, FPGAs, and other hardware. Intel OneAPI includes support for popular programming languages like C++, Python, and Fortran, as well as frameworks for deep learning, high-performance computing, and data analytics. With Intel OneAPI, developers can build applications that can run on a variety of hardware platforms, from edge devices to data centers, and take advantage of the performance benefits of Intel architectures.

#### Use Of oneDNN and TensorFlow in our project
![1](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/6feaed12-9b5f-49bb-b685-a43ce9bd104c)

![2](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/6b542ff5-35e5-4769-bd40-bcf2771f1927)

![3](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/1256bdc7-e922-450f-9e7a-7a6a163d21ce)

OneDNN provides highly optimized routines for various deep learning operations, including convolution, pooling, normalization, and activation functions. By using oneDNN, you can expect faster execution times and better performance on modern CPUs, especially those with Intel processors.
In this project os.environ['TF_ENABLE_ONEDNN_OPTS'] = '1' line sets an environment variable called TF_ENABLE_ONEDNN_OPTS to '1'. This enables the use of Intel's OneAPI Deep Neural Network Library (OneDNN) optimizations for TensorFlow on the system where this code is being run. OneDNN is a high-performance library for deep learning that is designed to optimize the performance of deep neural network computations on a variety of hardware platforms. By enabling OneDNN optimizations, this code may run faster on certain hardware architectures that are compatible with OneDNN. In this project, the Conv2D and Dense layers will be automatically optimized using oneDNN, which should result in faster training and inference times on compatible hardware.

The tensorflow.keras module is used to create a convolutional neural network (CNN) model for image classification. The model architecture consists of three convolutional blocks, each followed by a max pooling layer, and three fully connected layers with dropout for regularization.

Finally, the model.compile method is called to configure the optimizer, loss function, and evaluation metric for the model. The optimizer used is Adam, and the loss function used is sparse categorical cross-entropy. The model is also evaluated using the accuracy metric.


## How I Built It?  ![build](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/e499708d-894c-4503-87eb-a78c5cd110be)

Building BlindMate involved a step-by-step approach to harness the power of technology for accessibility:

#### Import Libraries
We leveraged essential libraries like TensorFlow, OpenCV, and oneDNN (Intel oneAPI library) to enable efficient deep learning operations and accelerate performance.

#### Understand the Data
We curated a diverse dataset of Indian currency notes, ensuring a comprehensive representation of denominations and variations.

#### Train the Data
We trained our models using various architectures, optimizing their performance with oneDNN to achieve faster inference without compromising accuracy.

#### Test and Refine
We rigorously tested the models using real-world images and refined their parameters for optimal results.

#### Save the Model
Once satisfied, we saved the trained model, making it ready for integration into the BlindMate application.

# Currency Detection Model   ![money](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/b6510a67-4c73-483f-9cb6-f59204ce3e85)

#### The Need For Currency Detection Model
Currency recognition is a critical feature in BlindMate, designed with a deep understanding of the challenges faced by visually impaired individuals. Identifying currency notes is an essential task for independence in daily transactions. Traditional methods rely on asking others for assistance, which compromises privacy and can be inconvenient. Our currency detection model bridges this gap, providing visually impaired users with the ability to identify and differentiate currency notes on their own terms.

#### Dataset Collection
We take immense pride in curating a dataset that accurately represents a wide range of Indian currency notes. The dataset was meticulously collected by our team, ensuring diverse variations, lighting conditions, and denominations. This attention to detail guarantees that our model can confidently recognize and classify various currency notes.

#### Features
Accurate Currency Recognition: Our currency detection model employs state-of-the-art deep learning techniques to accurately recognize and classify Indian currency notes.

Instant Auditory Feedback: Once a currency note is captured, BlindMate provides real-time auditory feedback, announcing the denomination of the note.

Privacy and Independence: Users gain the ability to manage their finances privately and independently, without relying on external assistance.

Seamless Integration: The currency detection model is seamlessly integrated into the BlindMate app, making the user experience effortless and intuitive.

#### Screenshots
![1](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/bbc66e88-041a-4f8f-8436-cc65f1195ccf)

![2](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/7cfc2d3b-5b4c-4dcb-96d5-5975f66de4ba)

![3](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/a2491de8-58e7-43fc-8926-5a7de32b5647)

![4](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/1bfca9e2-adaa-436f-8c4a-e2ae9bcfbe44)


![5](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/c006d52a-7f3b-424f-b357-2815b2ae546f)


![6](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/17f36584-fb2e-4f8a-96ef-6595fa28ec14)

![7](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/69784cce-559f-4cec-bef4-a13237b3604d)


![8](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/b06944e3-ff45-4682-8fc8-3c518d847329)


![9](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/9ce2ef08-999b-42d5-b594-15ccc200648b)


![10](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/c19001d7-c60b-4679-92a4-9c6fde190b47)

# Object Detection Model   ![object-alignment](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/2107b1cc-ae7f-48ea-92ac-eeb8ebebf6b0)


#### The Need For Object Detection
Navigating the world can be a daunting task for visually impaired individuals. Recognizing objects, obstacles, and the environment around them is crucial for safe and independent mobility. The object detection model in BlindMate addresses this need, empowering users with real-time auditory descriptions of their surroundings.

#### Dataset Collection
Our commitment to providing a comprehensive solution led us to manually collect a diverse dataset of objects and scenes. This dataset represents a wide array of everyday objects, ensuring that our object detection model can accurately identify and describe various items.

#### Features
Enhanced Spatial Awareness: The object detection model helps users navigate confidently by providing detailed auditory descriptions of objects and scenes around them.

Real-Time Assistance: BlindMate offers real-time feedback, ensuring users are informed about their surroundings as they explore new environments.

User-Centric Design: Our model is designed to prioritize user needs, providing descriptions that are not only accurate but also useful for orientation and decision-making.

User-Defined Interaction: Users can interact with the object detection model using voice commands, allowing them to request descriptions of specific areas or objects.

 #### Screenshots
![Screenshot 2023-08-11 000742](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/18e37e35-878e-4881-94bb-43793c76ac3c)

![Screenshot 2023-08-12 145524](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/a01b3f68-19c3-4f64-8c53-51d61f02693c)

![3](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/aacf34e2-cd87-45b1-86a9-35b43fc39065)

![4](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/c83ee260-6ff9-413f-95ee-08f8285096de)

![5](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/cd21b957-1d5b-4a8e-8d8f-d28c02ba0f6e)


![6](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/abb5c9e4-e27c-45ef-9339-2873121ad39b)



## What I Learnt From This Project  ![study](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/76a0488d-61d2-4437-abd1-77b1a80bce54)

Working on BlindMate was an enlightening experience that taught us valuable lessons:

#### Empathy-Driven Innovation
Accessibility technology isn't just about code; it's about understanding the needs of users and designing solutions that genuinely empower them.

#### Optimization Matters
Integrating oneDNN significantly enhanced our models' performance, showcasing the importance of optimizing deep learning operations.

#### Collaboration and Impact
By collaborating across disciplines, we saw how technology can drive positive impact and make a meaningful difference in people's lives.

#### Continuous Learning
The project's complexity challenged us to expand our knowledge, pushing us to explore cutting-edge techniques and stay updated with the latest advancements.

## Get Involved  ![join](https://github.com/JasleenKaur2711/BlindMate/assets/117057315/b2f896ee-fda4-4e81-a10d-3bb40ed4727d)

Join us on this inspiring journey to revolutionize accessibility and empower visually impaired individuals. Whether you're a developer, designer, advocate, or simply someone who believes in creating a more inclusive world, your contribution can make a difference. Let's collaborate to build a future where everyone has the tools they need to thrive.

## License
BlindMate is released under the MIT License.
