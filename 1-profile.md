---
title: profile
nav: true
---

# DETAILED WORKSHOP PROFILE


Following the practice of research by design, this workshop will emphasize the designerly appropriation of 
AI techniques while envisioning future human-machine collaboration. When technological progress is 
accelerating, and the possibilities of appropriation are given, it is even more important to draw attention to 
the possible dangers of future developments1
. Potential risks are derived from posthumanist thinkers who 
criticize a techno-optimism that does not deal with the consequences of its methods. Visions of a detachment 
of the mortal body completely disregard that thinking is dependent on an organic body.2
 Interactions of a 
social and material kind, necessary to form a mental model of the environment and oneself, are ignored. In 
posthumanist opinions, a human body diversified by technology and hybridized with objects, animals, or 
nature can lead to a new form of subjectivity.3
 Participants are invited to assume a speculative future in 
which organisms live in a symbiotic, hybrid existence with machines. Instead of focusing on perfecting and 
increasing the efficiency of the human species, alternative approaches focus on future concepts of 
hybridization and collaboration. What could a speculative posthuman look like? Will future bodily 
representation be altered using such new tools? Can historically disadvantaged individuals emancipate 
themselves by merging with the new species or are we heading towards a dystopia? The practical exercises 
will give insights on how the short film “Borrowed Limbs” was produced and how the techniques involved 
might get applied to other use cases. The footage for the short film was created with the help of a myriad of 
novel techniques for generating artificial imagery. Machine Learning backed processes such as StyleGAN34
, CLIP guided diffusion, upscaling (RealESRGAN)5
 and frame interpolation with RIFE6
 were applied in 
conjunction with traditional methods for image creation and composition: drawing, sketching, 3D modeling 
and photography. In the new future developing and evaluating Machine Learning models that understand 
people might involve many designers’ works, as designers are traditionally trained to understand people’s 
challenges, goals, and emotions. The design field has always developed rapidly, and designers are used to 
working with different media and software. They constantly must adapt to new tools, functionality, and 
industry changes and therefore might have the perfect mindset and skills to appropriate AI tools and systems. 
AI technologies change whole industries from serial production with the prerogative of standardization and 
one size fits all to a radical individualization. Tapping into the resilience of creative professionals facing 
disruptive technical developments, we will consider how these techniques can be applied in conjunction with 
more traditional art and design practices. Such combinatory techniques are also described in our paper 
alongside a proposed production pipeline for integrating AI tools in film production workflows. Meanwhile, 
we will also look at the big picture: Practical exercises will be the starting point of investigating how imagery 
is inferred, and a deep dive into the data and methods that are involved in training Machine Learning models 
(in particular the ones involved in generating artificial imagery). One Model will dedicate particular attention 
to is CLIP7 . CLIP is a part of DALL·E8
, which was introduced by OpenAI, publishing the paper “Zero-Shot Text-to-Image Generation” as a framework capable of generating an image from written text descriptions. 
OpenAI released CLIP in early 2021, the part of the code that processes language and evaluates how well an 
image fits a specific text description. While standard image models jointly train an image feature extractor 
and a linear classifier to predict some label, CLIP consists of an image encoder and a text encoder and was 
trained on web scraped images and their respective captions. With its capability of predicting how well an 
image fits a textual description, CLIP can be utilized for guiding a search through the latent space of a given 
Generative Adversarial Network to find latents that map to the textual concept of images. Since OpenAI 
published its research on DALL·E in the beginning of 2021 alongside releasing a smaller version of CLIP to 
the public, researchers and artists have tried to reverse engineer DALL·E and utilize CLIP in conjunction 
with various Generative Adversarial Networks. The artist and mathematician Katherine Crowson 
@RiversHaveWings9
 published a Google Colab Notebook that combines CLIP with VQGAN. The latter is 
short for “Vector Quantized Generative Adversarial Network“ and was proposed in the paper “Taming 
Transformers“ at Heidelberg University (2020). 10 VQGAN combines convolutional Neural Networks 
(traditionally used for images) with Transformers (traditionally used for language). The combination of the 
two Machine Learning models allows artists to create various exciting visuals merely by inputting text. A 
slightly modified version of Crowson’s Google Colab Notebook CLIP+VQGAN, will be used and 
participants will be instructed on how to find and use Jupyter notebooks/Google Colab Notebooks in general. 
The act of experimenting and performing inference with Machine Learning models, such as CLIP in 
combination with GANs can tell us a lot about how representations of our vast corpus of internet knowledge 
were embedded in those models. This condensed knowledge does not represent us human planet dwellers 
equally, as access to the internet is not at all equal among different countries and demographics. Problems 
like biased and outdated, sometimes outright discriminatory patterns in data gain even more significance, 
when AI is used to introduce new content. Once established representations of past data might forever haunt 
us, as they forever get entangled with the original material of the present: a vicious cycle. Humans also tend 
to presume neutrality in the way computational machines work - the problem with Machine Learning is that 
correlation, the coinciding data, is effectively treated as causation inside the resulting models, resulting in 
spurious relationships. It is not possible for these algorithms, which are based on statistical operations to 
differentiate causation and correlation when the factors causing the correlation are outside of the scope of the 
data available to the algorithm. A way to investigate is by interacting experimentally with these models and 
learning new aspects about the behavior with every such experiment. Through practical explorations such as 
interacting with a Machine Learning model’s latent space, and investigating the dataset it has been trained 
on, the workshop participants will come across some of these flaws and characteristics. Through practical 
exploration, participants will create future narratives of machine-human interaction and embodiment.
STRUCTURE
At first, insights will be given into the myriad of techniques that were used in producing the short film
