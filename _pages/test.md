---
layout: post
permalink: /test/
title: test
date: 2015-10-20 11:12:00-0400
description: an example of a blog post with some math
tags: formatting math
categories: sample-posts
related_posts: false
pseudocode: true
---

test $$
\sum_{k=1}^\infty |\langle x, e_k \rangle|^2 \leq \|x\|^2 $$ test


  <script type="module">
    import { LaTeXJSComponent } from "https://cdn.jsdelivr.net/npm/latex.js/dist/latex.mjs"
    customElements.define("latex-js", LaTeXJSComponent)
  </script>

  <style>
    latex-js {
      display: inline-block;
      width: 40%;
      border: 1px solid red;
      margin-right: 2em;
    }
  </style>

  <latex-js baseURL="https://cdn.jsdelivr.net/npm/latex.js/dist/">

\documentclass[letterpaper,11pt]{article}

\usepackage[paperwidth=212.5 mm, paperheight=321.25 mm]{geometry}
\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[pdftex]{hyperref}
\usepackage{fancyhdr}
\usepackage{underscore}
\usepackage{titlesec}
\usepackage{hyperref}
\hypersetup{
    colorlinks=true,
    linkcolor=blue,
    filecolor=magenta,      
    urlcolor=cyan,
    pdftitle={Joseph Resume},
    pdfpagemode=FullScreen,
    }

% Adjust margins
\addtolength{\oddsidemargin}{-13mm}
\addtolength{\evensidemargin}{-15mm}
\addtolength{\textwidth}{25mm}
\addtolength{\topmargin}{-10mm}
\addtolength{\textheight}{20mm}

\titleformat{\section}{\vspace{-4pt}\scshape\raggedright\large}{}{0em}{}[\titlerule]
\titlespacing{\section}{0pt}{3pt}{3pt}
\setlength{\titlewidth}{\textwidth}
\let\oldtitleline\titleline
\renewcommand{\titleline}{\oldtitleline*}

\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

\newcommand{\resumeItem}[2]{
  \item\small{
    \textbf{#1}{#2 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubheadingalter}[3]{
  \vspace{2pt}\item
   \textbf{#1} \\
    \begin{tabular*}{0.97\textwidth}{p{0.8\textwidth}@{\extracolsep{\fill}}r}
      \textit{\small#2} & \textit{\small #3} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

\renewcommand{\labelitemii}{$\circ$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-10pt}}

\begin{document}

%----------HEADING-----------------
\begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
  \textbf{{\Huge Joseph Liu}} & Email: \href{mailto:joseph@liu.us}{joseph@liu.us
}\\
 & Contact: +1 (650) 276-8035 \\
\end{tabular*}
\newline
%-----------EDUCATION-----------------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {University of Southern California (USC)}{Los Angeles, CA}
      {Bachelor of Science in Computer Science}{08/2022 - 05/2025}
      \resumeItemListStart
        \resumeItem{GPA: }{4.0/4.0}
        \resumeItem{Program: }{W.V.T. Rusch Engineering Honors Program}
      \resumeItemListEnd
    
    \resumeSubheading
      {Santa Clara University (SCU)}{Santa Clara, CA}
      {Bachelor of Science in Computer Science}{09/2021 - 05/2022}
      \resumeItemListStart
        \resumeItem{GPA: }{3.94/4.0}
      \resumeItemListEnd
  \resumeSubHeadingListEnd

%-----------PUBLICATIONS-----------------
\section{Publications}
\begin{enumerate}[{label=[\arabic{*}]},itemsep=0pt]
\small{
    \item Chen, X*., Yiwen, Y*., \textbf{\underline{Liu, J.}}*, Leong, C., Zhu, X., \& Chen, J. (2024). Generative Models in Protein Engineering: A Comprehensive Survey. \textit{NeurIPS 2024 Workshop Foundation Models for Science.} \textbf{(oral)} [\href{https://drive.google.com/file/d/1G2bGN6ZEHUTgDgZMDAscJKplqGNcUt0l/view}{Paper}]
    \item Keyu, He., Max, Li., \textbf{\underline{Liu, J.}} (2023). Enhancing Debugging Skills of LLMs with Prompt Engineering. Techical report. [\href{https://j.liu.us/assets/pdf/2023-1211-Enhancing-Debugging.pdf}{Paper}]
    \item Smith, R., Patel, A., Soraisam, M.D., Guhathakurta, P., Tadepalli, P., Zhu, S., \textbf{\underline{Liu, J.}}, Girardi, L., Johnson, L.C., Mukherjee, S., Olsen, K.A. (2024). Variable Stars in M31 Stellar Clusters from the Panchromatic Hubble Andromeda Treasury. \textit{The Astrophysical Journal}, 974(2), p.292. [\href{https://iopscience.iop.org/article/10.3847/1538-4357/ad6eff/meta}{Paper}]
    \item Patel, A., Mukherjee, S., Soraisam, M., Guhathakurta, P., \textbf{\underline{Liu, J.}}, \& Tadepalli, P. (2022). Variable Stars in M31 Stellar Clusters using the Panchromatic Hubble Andromeda Treasury. \textit{Bulletin of the AAS}, 54(6). [\href{https://baas.aas.org/pub/2022n6i201p02/release/1}{Paper}]
    \item \textbf{\underline{Liu, J.}} \textit{et al}. (2024). Perplexity as a Measure of Text Simplicity. Techical report. [\href{}{Paper}]
    \item \textbf{\underline{Liu, J.}} \textit{et al}. (2024). Predicting Game Popularity from Steam Descriptions. Techical report. [\href{https://j.liu.us/assets/pdf/2023-0501-Predicting-Game-Popularity.pdf}{Paper}]

}
\end{enumerate}
%-----------RESEARCH EXPERIENCE-----------------
\section{Research Experience}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Generative Models in Protein Engineering}{Los Angeles, CA}{Mentored by {Jiaqi Chen}, advised by \href{https://zcli-charlie.github.io/}{\textit{Prof.} Zuchao Li}}{08/2024 - Present}
      \resumeItemListStart
        \resumeItem{Protein Model Classification: }{Systematically categorized protein generative models through a multi-dimensional framework, encompassing inference methodologies (diffusion-based/autoregressive) and modeling targets (sequence/structure), establishing a structured overview of this emerging field's technical landscape.}
        \resumeItem{Protein Diffusion Model Comparison: }{Established a comparison framework for protein diffusion models across two fundamental dimensions: the mathematical representation level and the structural invariance level,  revealing how modeling choices affect protein structure design.}
        \resumeItem{Future Directions in Protein Modeling: }{Identified critical challenges and future opportunities in protein generative models, emphasizing the transition from data limitations to large-scale datasets and hybrid modeling approaches.}
    \resumeItemListEnd
        \resumeSubheading
      {Learning Heuristics for Multi-Agent Pathfinding}{Los Angeles, CA}
      {Mentored by {Yimin Tang}, advised by \href{https://sc.panda985.com/}{\textit{Prof.} Sven Koenig}}{05/2024 - Present}
      \resumeItemListStart
        \resumeItem{Trainable Heuristic Framework: }{Developed a trainable heuristic framework for multi-robot path planning, leveraging 4D tensor representation to capture spatial-temporal relationships between robot paths and environmental constraints.}
        \resumeItem{Two-Phase Training Strategy: }{Crafted a two-phase training strategy, initially replicating traditional heuristics and subsequently enhancing search efficiency with a node expansion reward system.}
        \resumeItem{Search Efficiency Assessment Tool: }{Implemented a quantitative evaluation system based on node expansion metrics, enabling direct measurement of search efficiency improvements for the learned heuristic function.}
        %\resumeItem{}{Developed predictive models to optimize node exploration in ECBS multi-agent pathfinding algorithm.}
      \resumeItemListEnd
     \resumeSubheading
      {Novel Perplexity-based Text Simplification Evaluation System}{Los Angeles, CA}{Mentored by {Xinyue Cui} and {Yoonsoo Nam}, advised by \href{https://viterbi.usc.edu/directory/faculty/Swayamdipta/Swabha}{\textit{Prof.} Swabha Swayamdipta}}{01/2024 - Present}
      \resumeItemListStart
        \resumeItem{Text Simplification Metrics: }{Designed a novel reference-free perplexity metric for text simplification by introducing template-based context, eliminating the need for specialized training data.}
        \resumeItem{Model Architecture Design: }{Developed an efficient evaluation framework utilizing pre-trained GPT-2 models without fine-tuning, enabling broad domain coverage and robust simplification assessment.}
        \resumeItem{Split Text Evaluation: }{Demonstrated superior performance in evaluating split-focused simplifications, achieving 51.2\% correlation with human judgment and outperforming existing metrics like SARI and BERTScore.}
    \resumeItemListEnd
    \resumeSubheading
      {Enhancing Debugging Skills of LLMs with Prompt Engineering}{Los Angeles, CA}
      {Researcher}{09/2023 - 01/2024}
      \resumeItemListStart
        \resumeItem{Debugging Prompt Engineering: }{Integrated prompt engineering into LLMs to boost performance in debugging tasks through few-shot learning and chain-of-thought prompting.}
        \resumeItem{Multidimensional Evaluation Metrics: }{Developed and implemented a comprehensive set of evaluation metrics, including CodeBLEU, CodeROUGE, and CodeF1, to quantitatively assess LLM debugging performance.}
        \resumeItem{Real-World Error Dataset Construction: }{Constructed a dataset by integrating Java and Leetcode to replicate real-world programming bugs for dynamic analysis.}
      \resumeItemListEnd

    \resumeSubheading
      {Variable Star Identification and Characterization in M31 Clusters}{Santa Cruz, CA}
      {Researcher (Variable Stars in Andromeda Galaxy)}{06/2020 - 08/2021}
      \resumeItemListStart
        \resumeItem{Hybrid Variable Star Detection Strategy: }{Combined statistical analysis of PHAT survey light curves with difference imaging to identify variable stars in M31 stellar clusters using HST observations.}
        %{Built a webpage and a graphical Python application to help efficiently visualize, categorize, and compare 1000+ stars.}
        \resumeItem{Crowded-field Assessment Framework: }{Established a probability-based method to evaluate photometry blending in cluster environments, providing confidence levels for derived stellar properties.}
        %{Discovered and identified missing portions of the PHAT dataset around brick edges with computational geometry.}
        \resumeItem{Variable Star Census and Classification: }{Established a catalogue of 86 luminous variables (F814W $<$ 19) in M31 clusters, with comprehensive characterization of their evolutionary phases and initial masses (0.8-67$M$$_{\odot}$) based on theoretical isochrones.}
        %{Optimized database queries by a factor of over 100, by reducing request count using batching, slicing data, and joins.}
        %\resumeItem{}{Parallelized cubic-time array operations in difference imaging data pipelines using NumPy matrix operations.}
      \resumeItemListEnd

    % \resumeSubheading
    %   {Data, Interpretability, Language, and Learning (DILL) lab, USC}{Los Angeles, CA}
    %   {Mentored by {Xinyue Cui} and {Yoonsoo Nam}, advised by \href{https://viterbi.usc.edu/directory/faculty/Swayamdipta/Swabha}{\textit{Prof.} Swabha Swayamdipta}}{01/2024 - Present}
    %   \resumeItemListStart
    %     \resumeItem{Text Simplification Metrics: }{Developed novel evaluation methods to assess text simplification quality through systematic analysis.}
    %     %{Developing novel evaluation methods for text simplification tasks.}
    %     \resumeItem{LLM-based Metrics Development: }{Implemented Large Language Model (LLM)-driven metrics for model assessment.}
    %     \resumeItem{Perplexity-based Performance Analysis: }{Designed and implemented perplexity-based methods, and evaluated performance on human ratings.}
    %   \resumeItemListEnd

    % \resumeSubheading
    %   {Computation and Data Driven Discovery Group, USC}{Los Angeles, CA}
    %   {Mentored by Bryan Shaddy, advised by \href{https://viterbi.usc.edu/directory/faculty/Oberai/Assad}{\textit{Prof.} Assad Oberai}}{08/2023 - 12/2023}
    %   \resumeItemListStart
    %     \resumeItem{Wildfire Modeling: }{Worked on physics-informed machine learning techniques to model wildfire spread using diffusion and GAN models.}
    %   \resumeItemListEnd

  %   \resumeSubheading
  %     {Interaction Lab, USC}{Los Angeles, CA}
  %     {Advised by \href{https://viterbi.usc.edu/directory/faculty/Mataric/Maja}{\textit{Prof.} Maja Mataric}}{04/2023 - 08/2023}
  %     \resumeItemListStart
  %       \resumeItem{Astro Robot Navigation: }{Created an autonomous lab tour using Amazon Astro Robot.}
  %     \resumeItemListEnd
  % \resumeSubHeadingListEnd

%-----------INDUSTRY EXPERIENCE-----------------
\section{Industry Experience}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Stellantis N.V.}{Auburn Hills, MI (Remote)}
      {Data Science Intern}{05/2023 - 08/2023}
      \resumeItemListStart
        \resumeItem{Pipeline Optimization: }{Led end-to-end optimization of ML sales prediction pipeline, achieving 86\% reduction in interruptions, 30\% faster runtime, and 25\% cost savings while improving data quality by fixing critical bugs affecting 60\% of the dataset.}
        %{Refactored and automated machine learning sales prediction pipeline, decreasing interruptions by 86\%, runtime by 30\%, and cost by 25\%.}
        %\resumeItem{}{Increased data quality by identifying and fixing multiple functional bugs that affected 60\% of sales dataset.}
        \resumeItem{Research Leadership: }{Spearheaded feature engineering initiatives and performance optimization research, presenting findings to 80+ stakeholders including directors and VPs.}
        %{Investigated potential features for better model performance and candidates for further feature engineering.}
        %\resumeItem{}{Presented findings and work to an audience of 80, including multiple directors and VPs.}
        \resumeItem{Performance Recognition: }{Demonstrated exceptional performance resulting in return offer for Summer 2024.}
        %{Received return offer for Summer 2024.}
      \resumeItemListEnd

    \resumeSubheading
      {iKala Interactive Media Inc.}{Taipei, Taiwan}
      {Machine Learning Intern}{06/2022 - 08/2022}
      \resumeItemListStart
        \resumeItem{Video Analysis Research: }{Researched state-of-the-art methodologies in Computer Vision (CV) and Natural Language Processing (NLP) for video analysis.}
        \resumeItem{Audio-Video Embedding: }{Designed and implemented a Transformer-based model for multimodal (video and audio) embedding generation with PyTorch, achieving 60\% precision on AudioSet dataset.}
      \resumeItemListEnd
  \resumeSubHeadingListEnd
%-----------PROJECTS-----------------
% \section{Projects}
%   \resumeSubHeadingListStart
%     \resumeSubheadingalter
%       {Medical Case Report Search with AI}
%       {Developing website to search case report database using intelligent symptom and complication matching.}
%       {09/2024 - Present}
    
    % \resumeSubheadingalter
    %   {Generative Models in Protein Engineering}
    %   {Investigated protein representations and generation approaches, and current challenges and opportunities in generative protein models.}
    %   {08/2024 - Present}
    
    % \resumeSubheadingalter
    %   {Enhancing Debugging Skills of LLMs with Prompt Engineering}
    %   {Investigated the effects of prompt engineering techniques like chain-of-thought on debugging skills of general LLMs and analyzed failure cases.}
    %   {09/2023 - 01/2024}
    
    % \resumeSubheadingalter
    %   {Earnings Call Analysis with Machine Learning}
    %   {Automated scraping of earnings call transcripts, analyzed sentiment using AWS SageMaker, built pipeline to extract audio features.}
    %   {11/2021 - 06/2022}
    
  %   \resumeSubheadingalter
  %     {Using CNNs to Identify Exoplanet Candidates}
  %     {Conducted independent research into feasibility of using CNNs on photometric data; trained 3DCNN model achieving 61\% accuracy.}
  %     {09/2021 - 03/2022}
   % \resumeSubHeadingListEnd




%-----------TEACHING EXPERIENCE-----------------
\section{Teaching Experience}
  \resumeSubHeadingListStart
    \resumeItem
      {Teaching Assistant, USC: }{Led lab sessions and mentored students in CSCI 201 Software Development.}
    \resumeItem
      {Course Grader, SCU: }{Assessed upper-level CSCI 163 Theory of Algorithms coursework as freshman student.}
  \resumeSubHeadingListEnd

%-----------AWARDS-----------------
\section{Awards}
\vspace{0pt}
     1)~USC Provost's Undergrad Research Fellowship: Fall 2024 (\$1,000) \\
     2)~USC Center for Undergraduate Research in Viterbi Engineering Fellowship: Fall 2023; Spring, Summer 2024 (\$5,500) \\
     3)~USC Viterbi Dean's List: Spring, Fall 2023; Spring 2024 \\
     4)~SCU Dean's Scholarship: 2021-2022 (\$8,100) \\

%-----------SKILLS-----------------
\section{Skills}
 \resumeItemListStart
 \itemsep=-2pt
    \item 
    \textbf{Languages:}{ Python, Java, C++, C\#, SQL, JavaScript, x86-64 Assembly}
    \item
    \textbf{Frameworks/Tools:}{ PyTorch, Pandas, NumPy, Git, AWS}
    \item
    \textbf{Environments:}{ Unix/Linux, Windows}
    \item
    \textbf{Areas of Expertise:}{ Machine Learning, Natural Language Processing (NLP), Large Language Models (LLMs), Data Structures \& Algorithms}
 \resumeItemListEnd

\end{document}

  </latex-js>