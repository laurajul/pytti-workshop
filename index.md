---

title: Home
---




# SYNTHESIZING MEANING
## a participatory one-day workshop

[GOALS](#GOALS)


{% include figure.html img="Impressions_04.png" alt="intro image here" caption="posthuman hybrid" width="100%" %}

we are organising this workshop as part of the [Participatory Design Conference 2022](https://pdc2022.org/)

## ABSTRACT


*The hands-on participatory workshop emphasizes the appropriation of AI techniques to convey a high-level understanding of applied Machine Learning, while retaining scrutiny on concurrent ethical and environmental issues. Novel ways of co-creation with machines will be explored, with a special focus on image generation techniques with natural language prompts. Learnings made during the workshop through practical experiments will serve as a starting point to reflect and discuss possible future scenarios and modalities of human machine interaction and collaboration. The workshop will put in perspective the mediating role speculative design can have in the face of disruptive technological advancements, as it allows for the exploration and simulation of future developments.*


### GOALS
Markdown Cheatsheet<a name="GOALS"></a>

The workshop is oriented towards collaboratively finding an approach towards dealing with applied Machine 
Learning techniques, while developing speculative future visions on machine-human hybridization. A high-
level understanding of applied Machine Learning will be conveyed, by means of practical AI appropriation. 
Meanwhile societal and environmental impacts, closely intertwined with the advances of AI technology will 
be scrutinized. The basic usage of Jupyter Notebooks will be demonstrated, and collaboration facilitated 
using the Google Colab and Drive infrastructure. The workshop will introduce and reflect on the views of 
posthuman thinkers such as Rosi Braidotti, Donna Haraway, and Katherine Hayles. Participants are invited 
to construct and share future visions of human-machine collaboration while appropriating AI tools that can 
be integrated in their individual workflows. The experimental short film “Borrowed Limbs” will serve as an 
example for both speculative storytelling and appropriation of AI tools. In this film, the AI protagonist utilizes 
the human body as a sensing device to gain an embodied understanding of its environment. As a result of 
consequent machine-human hybridization, the narration describes an interspecies alliance with AI as new 
species. The work was produced with several Machine Learning techniques, generating imagery that was 
brought into a coherent narrative. After exploring the tools used in the film, learnings made through the 
process of appropriation will be reflected upon through group discussion. Speculative concepts will be used 
for exploration and simulation of ethical issues connected to the emergence of new technologies. Developing 
such concepts, the workshop aims to spark a discussion about future visions of hybridization and machine-
human collaboration. Outcomes of the workshop will be a collection of generated images or short videos, 
reflecting on posthuman future visions, the story of their inception, and the conclusions drawn from them.
These will be combined into a collective work in the form of a Graphic Novel. The resulting stories will be 

made accessible to the participants in the browser with either a self-hosted Jupyter book (jupyterbook.org) 
or with other productivity and knowledge organization software based on markdown.*See also:* [workshop-template-b](https://evanwill.github.io/workshop-template-b/), Bootstrap version.


## STRUCTURE
At first, insights will be given into the myriad of techniques that were used in producing the short film 
“Borrowed Limbs”. The production pipeline developed while making the film and the technologies involved 
will be briefly explained. In the following, workshop participants are introduced to a modified version of the 
aforementioned Google Colab Notebook VQGAN+CLIP. At this stage there will be a small excurse delving 
into what makes the Machine Learning models involved in the image-diffusion-process behave the way they 
do: we will look at the training data being used to train CLIP and certain GANs. explain - on a very high 
level - how image diffusion works. The central task will be to select an organism, human or non-human, and 
describe a future collaboration with the AI as a new species. These speculative concepts will be visualized 
with the techniques learned before. The results will be discussed as they will reflect on certain aspects of 
future developments, projected by the participants (synthesized meaning). Some results will also reveal 
learnings about how the model ‘ticks’ some hypotheses on the training data and how natural language is 
processed can be drawn and discussed. Outcomes will be made accessible in the browser with either a self-
hosted Jupyter book (jupyterbook.org) or with a productivity software such as Notion, resulting in a gallery 
representing future visions of Machine collaboratio



## SCHEDULE

| Time | Programme |
---------------|-----------------------------------------------------------
| 9:00 – 9:30 | Introduction instructors and participants |
| 9:30 – 10:30 | Techniques used in “Borrowed Limbs” | 
| 10:30 – 11:00 | Coffee-Break (Zoom stays open for ppl that want to talk) |
 11:00 – 12:00 | Intro to CLIP guided diffusion 
 12:00 – 15:00 | Self-experimentation based on a speculative concept 
 15:00 – 17:00 | Comparison of results, conclusions discussion 
 17:00 – 17:15 | Goodbye (Zoom open until 18:00 for questions/feedback) 
<div class="toc" markdown="1">


## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

Hosted by [University of Idaho Library](http://www.lib.uidaho.edu/), {{ site.pub_year }}.
 
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
