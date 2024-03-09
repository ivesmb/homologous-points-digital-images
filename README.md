# homologous-points-digital-images

**Determination of homologous points in digital images**

🎯 It consists of comparing a reference sub-image, extracted from an image, with a research sub-image, extracted from another image. For all possible combinations, a similarity measure involving the gray tones of the two sub-images is carried out.

🖥️ Once all the similarity measures have been obtained, a correlation function is used to search for the sub-image in the search region that is most similar to the reference sub-image;

📈 The criterion used to find the most similar (or homologous) sub-image depends on the correlation function used.To do this, 5 static correlation functions are available in the code:

- Error function;
- Cross Covariance Function;
- Cross-Correlation function and;
- Quotient function.
