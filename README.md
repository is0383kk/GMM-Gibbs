# GMM-Gibbs
Implementation of a Gaussian mixture model with Gibbs sampling.  
ギブスサンプリングを適用したガウス混合モデルの実装例  


# How to run

1. The first step is to create the observation data using **make_data.py**. Then, create **data1.txt**. **true_label.txt** is the label data for calculating ARI.
2. After that, you can use **gmm_gibbs.py** to run the clustering.  

The image below shows the actual generated observables using **make_data.py**.
<div>
	<img src='/image/data1.png' height="250px">
</div>

# An example of the results  
The image below shows the actual ARI measured by **gmm_gibbs.py**, where a value close to 1 means high cluster performance and a value close to 0 means low cluster performance.  

<div>
	<img src='/image/ari.png' height="250px">
</div>

# Appendix
Other examples of implementations using GMM are as follows  
1. [GMM with Gibbssampling](https://github.com/is0383kk/GMM-Gibbs)
2. [GMM with Metropolis-Hastings Algorithm](https://github.com/is0383kk/GMM-MetropolisHastings)
3. [Multimodal-GMM](https://github.com/is0383kk/Multimodal-GMM)
4. [Multimodal-GMM with Metropolis-Hastings Algorithm](https://github.com/is0383kk/Inter-GMM)
5. [VAE and GMM mutual learning model](https://github.com/is0383kk/Pytorch_VAE-GMM)
