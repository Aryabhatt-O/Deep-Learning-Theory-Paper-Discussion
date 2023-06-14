# Deep Learning Theory Discussion :)

The repository contains lists of papers on theoretical deep learning and how relevant techniques are being used to further enhance deep learning. 

The repository is organized by [Amartya Roy](https://sites.google.com/view/amartyaroy/home?authuser=0), and [Anirbit Mukherjee](https://sites.google.com/view/anirbit/home)







   - [Comparative Generalization Bounds for Deep Neural Networks](https://openreview.net/pdf?id=162TqkUNPO)
      - <details><summary>Amartya's Notes</summary>
        Recent research suggests that deep neural networks are able to generalize well to new data. This paper looks at how corrupted labels affect the extent of intermediate layer NCC separability. Authors have proposed a novel generalization bound that estimates the likelihood that the effective depth of a trained neural network is strictly smaller than the minimal depth required to achieve NCC separability with partially corrupted labels. They have introduced the concept of “effective depth’ in neural networks, which refers to the lowest layer at which the features are nearest class-center separable.
        </details>  
        
       
   - [Why Can GPT Learn In-Context? Language Models Implicitly Perform Gradient Descent as Meta-Optimizers](https://arxiv.org/pdf/2212.10559.pdf)
      - <details><summary>Amartya's Notes</summary>
      The article proposes a theoretical understanding of in-context learning (ICL) in large pretrained language models such as GPT. The authors explain language models as  meta-optimizers and understand ICL as implicit fine-tuning. They theoretically figure out that Transformer attention has a dual form of gradient descent and provide         empirical evidence supporting their understanding. The article also suggests introducing momentum into attention as a potential method to further improve the                performance of  language models. 
        </details> 
