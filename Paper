<!-- Simple islolation -->
   - [Causal Attention for Vision-Language Tasks](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Causal_Attention_for_Vision-Language_Tasks_CVPR_2021_paper.pdf)
      - <details><summary>Maheep's Notes</summary>
        The paper proposes to eradicate unobserved confounder using the front-door adjustment in Visual Image Captioning. The author implements the same using the two methods, i.e. 
        
        **In-Sample Attention** and **Cross-Sample Attention**. The selector separates the `Z`(suitable knowledge, known as **IS-Sampling**) from `X`(Input) and predictor predicts the `Y` from `Z`. The suitable knowledge `P(Z = z|X)` is also known as **In-Sampling** and a predictor which exploits Z to predict Y. <br>
        `P(Y|X) = sigma P(Z = z|X)P(Y|Z = z)`<br>
        But the predictor may learn the spurious correlation brought by the backdoor path from X to Z, and thus the backdoor method is used to block the path from X to Z by stratifying `X` into different cases `{x}`, making it: <br>
        `P(Y|do(Z)) = sigma P(X = x)P(Y|X = x,Z)`<br>
        where `P(X = x)` is known as **Cross-Sampling** sice it comes with other samples, making the whole equation: <br>
        `P(Y|do(X)) = sigma P(Z = z|X) sigma P(X = x)P(Y|Z = z, X = x)`
         This is also called front-door adjustment. 
   
   
        ![Model](images/23.png)
        </details>  
