---
layout: page
title: Science
permalink: /science/
---

I am interested in understanding the principles of intelligence both in artificial and biological agents or agentic systems. I have worked on Bayesian and reinforcement learning models of decision-making and planning in agents. More recently, I have investigated the underlying mechanisms of generalisable and compositional reasoning, both in the context of understanding the representations that allow agents to generalise to novel sitations, and in terms of online and offline mechanisms that underlie compositional inference.

<div style="display: flex; align-items: center; gap: 40px; margin-bottom: 60px;">
  <div style="flex: 40%;">
    <a href="/data/Replay.png" target="_blank">
        <img src="/data/Replay.png" alt="Rplay" style="width: 100%; border-radius: 8px; cursor: pointer;">
    </a>
  </div>
  <div style="flex: 60%; text-align: justify;">
    <h3>Online compositional replay</h3>
    <p>
      Online neural replay facilitates compositional inference by using learnt statistical structure to guide uncertainty resolution. When faced with a novel problem, neural replay reflects a hypothesis-testing mechanism that gradually resolves uncertainty from more to less predictable building blocks (<a href="https://www.cell.com/cell/fulltext/S0092-8674(23)01025-5" target="_blank">Schwartenbeck et. al., Cell 2023</a>). Similar mechanisms might be at play during language generation (<a href="https://linkinghub.elsevier.com/retrieve/pii/S0896-6273(22)01125-4" target="_blank">Kurth-Nelson, ..., Schwartenbeck, Neuron 2023</a>).
    </p>
  </div>
</div>

<div style="display: flex; flex-direction: row-reverse; align-items: center; gap: 40px; margin-bottom: 60px;">
  <div style="flex: 40%;">
    <a href="/data/MCTSnet.png" target="_blank">
        <img src="/data/MCTSnet.png" alt="MCTS" style="width: 100%; border-radius: 8px; cursor: pointer;">
    </a>
  </div>
  <div style="flex: 60%; text-align: justify;">
    <h3>Adaptive MCTS</h3>
    <p>
      Applying ideas to make MCTS search adaptive via trainable neural networks (<a href="https://arxiv.org/abs/1802.04697" target="_blank">Guez, ..., Silver, arXive 2018</a>), we find that a learnable policy network can pick up on this statistical structure to improve performance of compositional inference (work led by Turan Orujlu, <a href="https://pure.mpg.de/pubman/faces/ViewItemOverviewPage.jsp?itemId=item_3385488_1" target="_blank">Schwartenbeck et. al., RLDM 2022</a>)
    </p>
  </div>
</div>

<hr style="margin-bottom: 60px; border: 0; border-top: 1px solid #eee;">

<div style="display: flex; align-items: center; gap: 40px; margin-bottom: 60px;">
  <div style="flex: 40%;">
    <a href="/data/SilhouetteAlgebra.png" target="_blank">
        <img src="/data/SilhouetteAlgebra.png" alt="Research Image" style="width: 100%; border-radius: 8px; cursor: pointer;">
    </a>
  </div>
  <div style="flex: 60%; text-align: justify;">
    <h3>Silhouette Algebra</h3>
    <p>
      During compositional inference, we can use individual neural representations of certain building blocks in specific relations to predict neural representations of novel composites (<a href="https://www.cell.com/cell/fulltext/S0092-8674(23)01025-5" target="_blank">Schwartenbeck et. al., Cell 2023</a>). This suggests a factorial neural code that underlies generalisable and compositional reasoning when faced with novel tasks, similar to a scene algebra in generative models of vision (<a href="https://www.science.org/doi/10.1126/science.aar6170" target="_blank">Eslami et. al., Science 2018</a>).
    </p>
  </div>
</div>

<hr style="margin-bottom: 60px; border: 0; border-top: 1px solid #eee;">

<div style="display: flex; flex-direction: row-reverse; align-items: center; gap: 40px; margin-bottom: 60px;">
  <div style="flex: 40%;">
    <a href="/data/FreeEnergy.png" target="_blank">
        <img src="/data/FreeEnergy.png" alt="Free Energy" style="width: 100%; border-radius: 8px; cursor: pointer;">
    </a>
  </div>
  <div style="flex: 60%; text-align: justify;">
    <h3>Information-theoretic planning</h3>
    <p>
      When casting decision making as surprise minimisation in Markov Decision Processes, we can derive different biases for maximising reward, minimising uncertainty about hidden states and minimising uncertainty about model parameters, which all guide planning behaviour (<a href="https://elifesciences.org/articles/41703" target="_blank">Schwartenbeck et. al., eLife 2019</a>).
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; gap: 40px; margin-bottom: 60px;">
  <div style="flex: 40%;">
    <a href="/data/MidbrainBeliefs.png" target="_blank">
        <img src="/data/MidbrainBeliefs.png" alt="Midbrain" style="width: 100%; border-radius: 8px; cursor: pointer;">
    </a>
  </div>
  <div style="flex: 60%; text-align: justify;">
    <h3>Neural basis of Belief Updating</h3>
    <p>
      When performing inference in Markov Decision Processes, there is an important distinction between surprising but meaningless events ("information-theoretic surprise") and unexpected events that allow agents to shift their beliefs about hidden states ("Bayesian surprise"). We find that there is a clear neural distinction between those two surprise signals, where (unsigned) Bayesian but not information-theoretic surprise is reflected in dopaminergic activity (commonly associated with signalling (signed) reward prediction errors) (<a href="https://www.sciencedirect.com/science/article/pii/S1053811915009842?via%3Dihub" target="_blank">Schwartenbeck et. al., NeuroImage 2016</a>, <a href="https://www.pnas.org/doi/full/10.1073/pnas.1809298115" target="_blank">Nour, ..., Schwartenbeck et. al., PNAS 2018</a>).
    </p>
  </div>
</div>