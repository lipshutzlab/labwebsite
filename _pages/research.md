---
layout: page
title: Research
permalink: research
order: 1
---

<p>
We are broadly interested in understanding how large populations of neurons coordinate to efficiently and robustly process information and how this processing is shaped by learning and adaptation. To gain insights, we develop algorithmic frameworks that link computational objectives to neural processes.
<!-- For an overview of the normative approach, see this excellent <a href="https://www.youtube.com/watch?v=rP3znbxmyRg">tutorial</a> by Anne Hermundstad. <br><br> -->
Some of our recent efforts are described below.
</p>

<h3>Learning and synaptic plasticity</h3>

<p>
A primary mechanism for learning in the brain is synaptic plasticity. However, the relationship between changes at the synaptic level and associated changes in the neural responses at the population level remains poorly understood. We develop algorithmic frameworks that link population level learning objectives and synaptic plasticity rules, with an emphasis on non-Hebbian forms of synaptic plasticity. For an overview this work, see our <a href="https://doi.org/10.1103/PRXLife.1.013008">review article</a> and <a href="/slides/njit.pdf">slides</a> from a recent talk.
</p>

{% include refs.html tag = "learning" %}

<h3>Adaptive coding efficiency and the role of interneurons</h3>

<p>
Early sensory systems are thought to <a href="https://en.wikipedia.org/wiki/Efficient_coding_hypothesis">efficiently encode</a> natural signals using the available resources. Since environments are constantly in flux, this necessitates sensory systems that can rapidly adapt to changing signal statistics. There is extensive experimental and theoretical work devoted to understanding adaptation at the single neuron level; however, much less is known about the mechanisms that support adaptation at the neural population level. We develop circuit models that demonstrate how adaptation mechanisms such as gain modulation and synaptic plasticity can support efficient coding in neural populations. We are particularly interested in the role of local inhibitory interneurons in reshaping excitatory neural responses into efficient representations. For an overview of this work, see <a href="/slides/utaustin.pdf">slides</a> from a recent talk.
</p>

{% include refs.html tag = "adaptation" %}

<h3>Representational similarity metrics</h3>

<p>
A challenge at the intersection of neuroscience and machine learning is to understand if neural systems compute similarly. Comparing neural systems is challenging in part because neural responses to stimuli are high-dimensional, noisy and dynamic. We develop methods for quantifying the similarity between neural responses.
</p>

{% include refs.html tag = "metric" %}