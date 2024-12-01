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
embed_cv: true # embed CV in this page
cv_pdf: joseph-cv.pdf
cv_link: /cv/   # link to standlone CV page
social: true # includes social icons at the bottom of the page
---

<style>
.hstmt {
  font-size: 1.7rem;
  padding-top: 0rem;
  padding-bottom: 0.5rem;
}
</style>

<p class="hstmt">Statement of Purpose</p>

Work to live, or live to work? I say neither. From taking out trash to large
group meetings, everyone has menial but necessary tasks that swallow precious
time. In recent years, I have worked extensively in machine learning and seen
firsthand how it can empower humanity. It enables us to focus on what is
meaningful by assisting with the mundane. I would love to continue this work
through postgraduate studies. My previous work with language models (LMs),
multimodality, and reinforcement learning has guided me toward my research
interests: more capable multimodal models, evaluation of their limitations,
and their application to society at large.

> LMs for Programming

In my junior year, I started a project researching the applications of
language models in programming under Professor Swayamdipta. I led my team in
an investigation of the debugging capabilities of LMs through different
prompting strategies. One key challenge was the lack of a reliable metric for
evaluating the effectiveness of model outputs; traditional evaluations are
similarity-based, which is inaccurate on heavily reformatted code. To address
the problem, we developed multiple error generation mechanisms that created
code pairs and test cases. Then, we proposed an executable metric that
evaluates debugging performance by running these test cases, directly
measuring functional improvement. We found that chain-of-thought prompting
generally increased performance, while few-shot prompts decreased performance
due to the number of bugs found in the context. My results from exploring
prompt engineering's impact on functional correctness have led to my interest
in holistic evaluations grounded in real-world performance.

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
also demonstrated decreased performance as task complexity increases due to
the linking of multiple models. To address these limitations, I am eager to
explore more unified representations across modalities.

> LMs as Evaluators

Since January 2024, I have been researching text simplification evaluation
under Professor Swayamdipta. Traditional methods have design drawbacks such as
reliance on high-quality reference texts or extensive annotated data, which
constrains their domains and adaptability. Instead, I designed and implemented
a novel approach using a panel of LLMs that removed the need for external
information sources entirely. Harnessing the model’s inherent understanding of
simplicity, I used a specialized prompt to obtain scores from multiple models
and transformed the outputs into a simplicity score. Our method significantly
outperformed traditional metrics; its correlation with human judgment
surpassed human annotators on certain dimensions and was highly competitive in
the rest. As first author, I am preparing a paper for submission by early next
year. My work also revealed a key challenge in evaluation: Human annotators
often disagreed due to equally valid but subjective interpretations.
Recognizing these variations has refined my interest in developing evaluation
methods that can quantify real-world complexity and diversity of opinion.

> Multi-agent Path Finding (MAPF)

While working with language and multimodal models, I also recognized their
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

> Towards Effective Academic Skills

Recently, I collaborated with Stanford and CMU researchers on a review of
generative protein design. Analyzing nearly 300 papers, we proposed a
framework categorizing methods into two paradigms and three generative tasks.
I contributed to the section on LMs and autoregressive models, identifying
underexplored areas such as end-to-end drug discovery pipelines and clinically
relevant benchmarks. Our work was selected for the FM4Science Workshop at
NeurIPS 2024 and will be submitted to npj Artificial Intelligence. As co-first
author, I performed an extensive literature review and contributed to many
aspects of paper writing, from initial drafting to creating figures to
editing. This experience sharpened my ability to collaborate across
institutions and synthesize many perspectives, preparing me for complex
research environments.

> Why MIT?

I admire MIT because of its rich concentration of motivated students.
Professors are often told to meet students where they are, but I want to be at
a place that pushes students to where they want to be. I am particularly drawn
to Professor Paul Liang’s work in multimodal models; single-modality models
stifle the potential of AI and I am interested in researching less modularized
foundation models. Simultaneously, textual modalities are very well-suited for
reasoning even if currently flawed, and I would like to work with Professor
Yoon Kim to evaluate the extent of their capabilities. Lastly, I am interested
in the work of Professor Cathy Wu, as it focuses on how best to apply previous
advances in societal systems despite their limitations. My long-term goal is
to continue research in an academic setting because it is where the realm of
possibility is pushed forward; and as this happens, people are freed to work
on what they find most creative and joyful.


<br>

---

<p class="hstmt">Personal Statement</p>

I am vividly colored by Eureka moments. Eureka moments are characterized by a
lingering question, an answer, and a familiar feeling of satiation. It’s no
surprise that I came to favor computer science because of the constructive
nature of logic; I love that knowledge begets knowledge. My research area,
machine learning, is especially unique because it is a system that is adaptive
to new knowledge. Through it, I could contribute to the sum of human knowledge
not just by learning myself, but also by creating systems that will continue
to learn, even after my work is finished.

I was 8 months into my text simplification project when I realized that my
approach had significant limitations. After a difficult conversation with my
professor, I had to make the challenging decision to start over in a different
direction. In the moment, I worried that I would lose the resolve I had; it is
disheartening to discard work, especially something that I had labored over so
extensively. And yet, I found myself recovering much faster than I expected.
Upon reflection, I realized that my motivation has always been, and still is,
the Eureka moment: when all the pieces fall into place and everything - the
theory, the experimental results, the failed attempts - coalesces into a
singular understanding. The setbacks I face don’t take away from it; they
delay but also contribute, and the moment feels that much more satisfying when
I finally understand it all.

As I learned about myself, I was fortunate enough to be placed in positions
where I could help others thrive. Through helping my sister with homework,
volunteering, and later teaching assistant positions, I have learned that I
find satisfaction not only in gaining knowledge but also in witnessing other
people discover their Eureka moment. The joy that lights up their face in the
moment of sudden realization is contagious because I have experienced it. As
such, I desire the opportunity to teach others; I want to put time and effort
into helping others because I want to be a companion in their journey.

Throughout my life, the pursuit of knowledge has been a key motivator. While
other paths offer the opportunity to learn, graduate school and academia are
the purest: learning for the sake of learning. To impart knowledge to others
is the entire purpose of higher education. From what I have learned thus far,
graduate school is the obvious next step because it uniquely can satiate my
desire to be curious, to explore, to learn, and to create.

