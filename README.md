# thesisNLP


In this paper I aim to compare the methods traditionally used
such as Harvard IV-4 and Loughran and McDonald dictionary with
more advanced techniques such as FinBERT and a Recursive Neural
Tensor Network (RNTN) to see if incorporating syntactic information
leads to better results. After which I will use the best performing
models to see if you can use sentiment analysis to predict stock market returns from the Management Discussion and Analysis (MDA)
section of annual reports (10-ks). I find that on the labeled datasets
the FinBERT model outperforms all other methods. The superior
performance is attributable to using syntactic information in combination with that the model is specially designed for financial language.
The Harvard IV-4 and RNTN are both not built for financial language
and perform the worst on the labeled datasets.

![harvard_all_final](https://user-images.githubusercontent.com/104837565/182042893-0f351ef9-fa05-4a79-ad19-b06db90f3430.png)         ![lm_all_final](https://user-images.githubusercontent.com/104837565/182042911-74d2f42d-dd9e-4c4e-a5bb-3999846eb442.png)  ![finbert_all_final](https://user-images.githubusercontent.com/104837565/182042938-b00e2b89-8f11-4a4b-aa31-56b26aa2ad9d.png)    ![RNTN_all_final](https://user-images.githubusercontent.com/104837565/182042943-1f41e575-fada-4515-9ae9-961204cc1587.png)



-------------------------------------------------------------------------------------------------------------------------------------------------------------------------


