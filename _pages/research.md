---
layout: page
title: Research
permalink: research
order: 1
---

<br>

<p>
We are broadly interested in understanding how large populations of neurons coordinate to efficiently and robustly compute and how this computation is shaped by learning and adaptation. 
To gain insights, we develop algorithmic frameworks that link circuit computations to mechanisms such as neural dynamics, gain modulation and synaptic plasticity.
Some of our recent efforts are described below.
</p>

<h3>Learning and synaptic plasticity</h3>

<p>
A primary mechanism for learning in the brain is synaptic plasticity. However, the relationship between changes at the synaptic level and associated changes in the neural responses at the population level remains poorly understood. We develop algorithmic frameworks that link population level learning objectives and synaptic plasticity rules, with an emphasis on non-Hebbian forms of synaptic plasticity. For an overview this work, see our <a href="/papers/lipshutz2023normative.pdf">review article</a> and <a href="/slides/njit.pdf">slides</a> from a recent talk.
</p>

{% include refs.html tag = "learning" %}

<h3>Adaptive coding efficiency in neural populations</h3>

<p>
Early sensory systems are thought to <a href="https://en.wikipedia.org/wiki/Efficient_coding_hypothesis">efficiently encode</a> natural signals using the available resources. Since environments are constantly in flux, this necessitates sensory systems that can rapidly adapt to changing signal statistics. There is extensive experimental and theoretical work devoted to understanding adaptation at the single neuron level; however, much less is known about the mechanisms that support adaptation at the neural population level. We develop circuit models that demonstrate how adaptation mechanisms such as gain modulation and synaptic plasticity can support efficient coding in neural populations. We are particularly interested in the role local inhibitory interneurons may serve in reshaping excitatory neural responses into efficient representations. For an overview of this work, see <a href="/slides/utaustin.pdf">slides</a> from a recent talk.
</p>

{% include refs.html tag = "adaptation" %}

<h3>Metrics for comparing neural systems</h3>

<p>
A challenge at the intersection of neuroscience and machine learning is to understand if two neural systems (biological or artificial) compute similarly. For example, does an artificial deep neural network compute similarly to the human visual system? Comparing neural systems is challenging in part because neural responses (or representations) are high-dimensional, noisy and dynamic. We develop methods for quantifying the similarity between neural representations that are stochastic and/or dynamic.
</p>

{% include refs.html tag = "metric" %}