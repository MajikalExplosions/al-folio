---
layout: about
title: MIT
permalink: /mit
nav: false
subtitle:
header: false
sitemap: false

profile:
  align: right
  image: 2024-0105-joseph-square-1400.jpg
  image_circular: true # crops the image to make it circular
  more_info: >

news: true # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
embed_cv: false # embed CV in this page
cv_pdf: joseph-cv.pdf
cv_link: /cv/   # link to standlone CV page
social: true # includes social icons at the bottom of the page
---

<style>
h5 {
  font-size: 2rem;
  padding-top: 0rem;
  padding-bottom: 0.5rem;
}
h6 {
  font-size: 1.3rem !important;
  padding-top: 1rem;
  padding-bottom: 0.5rem;
}
</style>

##### Statement of Purpose

Work to live, or live to work? I say neither. From taking out trash to large
group meetings, everyone has menial but necessary tasks that swallow precious
time. Over the past years, I have worked extensively in machine learning and
seen firsthand how it can empower humanity by enabling us to focus on what is
meaningful by assisting us with the mundane. I would love to continue this
work through a PhD. My previous work with language models (LMs),
multimodality, and reinforcement learning has guided me toward my research
interests: more capable multimodal models, evaluation of their limitations,
and their application to society at large.

###### LMs for Programming
I began this work by researching how LMs could help in computer science. As
the team leader for a project under Professor Swayamdipta, I led an
investigation into the debugging capabilities of LMs through different
prompting strategies. One key challenge was the lack of a reliable metric for
evaluating the effectiveness of model outputs; traditional evaluations are
similarity-based, which is inaccurate on heavily reformatted code. To address
the problem, we developed multiple error generation mechanisms that created
code pairs and test cases. Then, we proposed an executable metric that
evaluates debugging performance by running these test cases, directly
measuring functional improvement. We found that chain-of-thought prompting
generally increased performance, while few-shot prompts decreased performance
due to the number of bugs found in the context. The inability of existing
metrics to measure this result revealed the importance of considering model
limitations in designing metrics. My learnings from this project have led to
my interest in holistic evaluations grounded in real-world performance. 

Subsequently, I had the opportunity to collaborate with teams from leading
universities to apply code generation to a more concrete scenario: code
synthesis for multimodal generative models. By generating ComfyUI code, large
language models (LLMs) assemble relevant components to perform a large variety
of any-to-any multimodal generation tasks. Drawing on my previous expertise, I
assisted the team in developing an automated process tailored to the ComfyUI
symbolic language. Our approach increased the execution success rate by 23%,
allowing us to complete 12 multimodal generation tasks without pretraining new
models. While our method performed very well against both SOTA and commercial
systems in tasks ranging from text-to-image to inpainting to text-to-video, it
also tends to fail more often as task complexity increases due to the linking
of multiple models. To address these limitations, I am eager to explore more
unified representations across modalities.

###### LMs as Evaluators
Since January 2024, I have been researching text simplification evaluation
under Professor Swayamdipta. Traditional methods have design drawbacks such as
reliance on high-quality reference texts or extensive annotated data, which
constrains their domains and adaptability. Instead, I designed and implemented
a novel approach using a panel of LLMs that removed the need for extra
information entirely. Utilizing the model’s inherent understanding of
simplicity, I used a specialized prompt to obtain a score from multiple models
and transformed the output into a simplicity score. Our method significantly
outperformed traditional metrics; its correlation with human judgment
surpassed human annotators on certain dimensions and was competitive in
others. As first author, I am preparing a paper for submission by early next
year. My work also revealed a key challenge in evaluation: Human annotators
often disagreed due to equally valid but subjective interpretations.
Recognizing these variations has refined my interest in developing evaluation
methods that can quantify real-world complexity and diversity of opinion.

###### Multi-agent Path Finding (MAPF)
While working with language and multimodal models, I recognized their
limitations. In many environments, specialized decision-making or planning
models can perform better. Under Professor Koenig’s guidance, I am exploring
an application of ML in MAPF, based on the Enhanced Conflict Based Search
algorithm. While previous deep learning solutions replaced planning with a
single end-to-end model, I replaced only the search heuristic. Our method uses
PPO to train an agent to score search nodes. This method considers specific
arrangements, like end-to-end models, while preserving optimality guarantees.
As with multimodal code synthesis, the fusion of reinforcement learning and
search algorithms showed me how different fields can complement each other,
reinforcing my interest in pursuing multiple directions to develop more robust
solutions.

###### Towards Effective Academic Skills
Recently, I collaborated with Stanford and CMU researchers on a review of
generative protein design. Analyzing nearly 300 papers, we proposed a
framework categorizing methods into two paradigms and three generative tasks.
I contributed to the section on LMs and autoregressive models, identifying
underexplored areas such as end-to-end drug discovery pipelines and clinically
relevant benchmarks. Our work was selected for the FM4Science Workshop at
NeurIPS and will be submitted to npj Artificial Intelligence. In this work, I
performed an extensive literature review and contributed to many aspects of
paper writing, from initial drafting to creating figures to editing. This
experience sharpened my ability to collaborate across institutions and
synthesize many perspectives, preparing me for complex research environments.

###### Why MIT?
I admire MIT because of its rich concentration of motivated students;
professors are often told to meet students where they are, but I want to be at
a place that pushes students to where they want to be. I am particularly drawn
to Professor Paul Liang’s work in multimodal models; LMs alone stifle the
potential of AI and I am interested in researching less modularized foundation
models. Simultaneously, textual modalities are very well-suited for reasoning
even if currently flawed, and I would like to work with Professor Yoon Kim to
evaluate the extent of their capabilities. Lastly, I am interested in the work
of Professor Cathy Wu, as it focuses on how previous advances can best be used
in societal systems despite their limitations. My long-term goal is to
continue research in an academic setting because it is where the realm of
possibility is pushed forward; and as this happens, people are freed to work
on what they find most creative and joyful.

---

##### Personal Statement
