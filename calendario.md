# CC6204 Primavera 2024

* Profesore de Cátedra:  [Valentin Barriere](https://dcc.uchile.cl/pregrado/academico/valentin-barriere)
* Ayudantes:  Camila Figueroa, Héctor Jiménez, Ken Miyake y Paula Ovalle 

## Contenidos Inicial Publicados por Semana

The content of the classes, specially the most advance ones (Weeks 8 and after) is **very likely to change**. My idea is to add classes on several possible topics: classical language modeling, audio models (audio speech recognition, general models), multimodal models (classical ones, CLIP, Diffusion, LLM-based), large text generative models (emerging abilities, instructions, alignments, in context learning, chain of thoughts, agent, RAG), efficiency and how to train/deploy an LLM on a small budget (parameter efficient fine tuning, quantization, optimized specific libraries like vLLM). **Please tell me what you think on the discord channel!**

**UPDATE:** After analyzing the results of the poll, we will have classes on the following subjects: 
* Modelos de Lenguaje
* Modelos de Lenguaje Largos generativos
* Modelos Multimodales
* Efficiency


|  Semana  | Fechas        | Actividades                                                  | Slides | Trabajo graduado          |
| :------: | :------------ | :----------------------------------------------------------- | :----: | :--------------:          |
|    1     | 05/08 - 11/08 | **Miércoles 07/08 - 16:15 hrs**: Introducción    |    [Intro](./Slides/1_Introduction.pdf)    |                           |
|    2     | 12/08 - 18/08 | **Lunes 12/08 - 16:15 hrs**: Perceptron, Gradiente Descendiente <br/> **Miércoles 14/08 - 16:15 hrs**: SGD, Backpropagation, Funciones de activación |  [Perceptron y SDG](./Slides/2_Perceptron_GD.pdf) <br/> [Backpropagation](./Slides/3_Backpropagation.pdf) <br/> [Encuesta Clases](./Additional_Material/1.1_Encuesta.pdf)   |                           |
|    3     | 19/08 - 25/08 | **Lunes 19/08 - 16:15 hrs**: Laboratorios 1/2 <br/> **Miércoles 21/08 - 16:15 hrs**: Multi-clase, softmax |   [Softmax, Multi-clase y Cross-entropy](./Slides/4_Softmax_CEL.pdf)   |
|    4     | 26/08 - 01/09 | **Lunes 26/08 - 16:15 hrs**: Inicializacion de pesos, Algoritmos de optimización y Laboratorio 3 <br/> **Miércoles 28/08 - 16:15 hrs**: DIA LIBRE |   [Weight initialization](./Slides/5_Initialization_optimization.pdf)   | 27/08 T_1 Enunciado       |
|    5     | 02/09 - 08/09 | **Lunes 02/09 - 16:15 hrs**: Regularizacion y Laboratorio 4 <br/> **Miércoles 04/09 - 16:15 hrs**: DIA LIBRE |   [Regularization](./Slides/6_Regularization.pdf)     |                           |
|    6     | 09/09 - 15/09 | **Lunes 09/09 - 16:15 hrs**: Convolución, ideas, Capas convolucionales, Ingredientes CNN <br/> **Miércoles 11/09 - 16:15 hrs**: DIA LIBRE |   [Convolución, ideas](./Slides/7_CNN1.pdf) <br/> [CNN 2](./Slides/8_CNN2.pdf)    | 10/09 T_1 Entrega <br> 10/09 T_2 Enunciado |
|         | 16/09 - 22/09 | **RECESO ACADÉMICO**                                         |        |                           |
|   7     | 23/09 - 29/09 | **Lunes 23/09 - 16:15 hrs**: DIA LIBRE <br/> **Miércoles 25/09 - 16:15 hrs**: DIA LIBRE |        |                           |
|    8     | 30/09 - 06/10 | **Lunes 30/09 - 16:15 hrs**: Arquitecturas CNN <br/> **Miércoles 02/10 - 16:15 hrs**: DIA LIBRE |    [Arquitecturas CNN](./Slides/9_CNN_Architectures.pdf)    | 03/10 T_2 Entrega         |
|    9     | 07/10 - 13/10 | **Lunes 07/10 - 16:15 hrs**: Laboratorios 5/6  <br/> Transfer Learning y Laboratorios 7/8 <br/> **Miércoles 09/10 - 16:15 hrs**: DIA LIBRE |    [Transfer Learning](./Slides/10_TransferLearning.pdf)    | 08/10 T_3 Enunciado       |
|    10    | 14/10 - 20/10 | **Lunes 14/10 - 16:15 hrs**: DIA LIBRE <br/> **Miércoles 16/10 - 16:15 hrs**: DIA LIBRE|        |                           |
|    11    | 21/10 - 27/10 | **Lunes 21/10 - 16:15 hrs**: Detección de objetos y Arquitecturas de Detección <br/> Laboratorios 9/10  <br/> **Miércoles 23/10 - 16:15 hrs**: Modelos secuenciales RNN |    [Detección de objetos y Arquitecturas de Detección](./Slides/11_ComputerVision.pdf)    | 22/10 T_3 Entrega         |
|          | 28/10 - 03/11 | **RECESO ACADÉMICO**                                         |        |                           |
|    12    | 04/11 - 10/11 | **Lunes 04/11 - 16:15 hrs**: LSTM, Laboratorio 11/12 <br/> **Miércoles 06/11 - 16:15 hrs**: Modelos generativos |        | 05/11 T_4 Enunciado       |
|    13    | 11/11 - 17/11 | **Lunes 11/11 - 16:15 hrs**: Modelos generativos, Laboratorio 9 <br/> **Miércoles 13/11 - 16:15 hrs** : Atención Neuronal |        |                           |
|    14    | 18/11 - 24/11 | **Lunes 18/11 - 16:15 hrs**: Transformers, Laboratorio 10 <br /> **Miércoles 20/11 - 16:15 hrs**: Técnicas avanzadas: Modelos de Lenguaje |        | 19/11 T_4 Entrega <br> 19/11 T_5 Enunciado       |
|    15    | 25/11 - 01/12 | **Lunes 25/11 - 16:15 hrs**: Técnicas avanzadas: Modelos de Lenguaje Largos generativos <br/> **Miércoles 27/11 - 16:15 hrs**: Técnicas avanzadas: Modelos Multimodales |        |                           |
| 16 | 02/12 - 08/12 | **Lunes 02/12 - 16:15 hrs**: Técnicas avanzadas: Efficiency         |        | 03/12 T_5 Entrega         |


## Discord 

We have a dedicated discord channel for this class. Please look at the [u-campus post](https://www.u-cursos.cl/ingenieria/2024/2/CC6204/1/foro/o/31217745).  