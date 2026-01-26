---
layout: page
title: Science
permalink: /science/
---

<div style="display: flex; align-items: center; gap: 40px; margin-bottom: 60px;">
  <div style="flex: 40%;">
    <a href="/data/Replay.png" target="_blank">
        <img src="/data/Replay.png" alt="Rplay" style="width: 100%; border-radius: 8px; cursor: pointer;">
    </a>
  </div>
  <div style="flex: 60%; text-align: justify;">
    <h3>Online compositional replay</h3>
    <p>
      Online neural replay facilitates compositional inference by using learnt statistical structure to guide uncertainty resolution. When faced with a novel problem, neural replay reflects a hypothesis-testing mechanism that gradually resolves uncertainty from more to less predictable building blocks.
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
      Applying ideas to make MCTS search adaptive via trainable neural networks, we find that a learnable policy network can pick up on this statistical structure to improve performance of compositional inference (work led by Turan Orujlu)
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
      During compositional inference, we can use individual neural representations of certain building blocks in specific relations to predict neural representations of novel composites. This suggests a factorial neural code that underlies generalisable and compositional reasoning when faced with novel tasks, similar to a scene algebra.
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
      When casting decision making as surprise minimisation in Markov Decision Processes, we can derive different biases for maximising reward, minimising uncertainty about hidden states and minimising uncertainty about model parameters, which all guide planning behaviour.
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
      When performing inference in Markov Decision Processes, there is an important distinction between surprising but meaningless events ("information-theoretic surprise") and unexpected events that allows agents to shift their beliefs about hidden states ("Bayesian surprise"). We find that there is a clear neural distinction between those two surprise signals, where (unsigned) Bayesian but not information-theoretic surprise is reflected in dopaminergic activity (commonly associated with signalling signed reward prediction errors).
    </p>
  </div>
</div>