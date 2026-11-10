---
title: "Grasp Affordance Transfer via Simulation Pretraining"
authors: "D. Volkov, R. Oyelaran, T. Ilić"
venue: "Conference on Robot Learning (CoRL)"
year: 2024
status: "accepted"
codeurl: "https://github.com/komal74784391-netizen/sim2real-grasp-k7m2x"
abstract: >-
  We pretrain an affordance predictor in a physically simulated warehouse and
  transfer it to a real two-finger gripper. Domain random-isation over object
  mass, friction and lighting closes most of the sim-to-real gap.
---

The paper reports 84% grasp success on unseen objects after 30 minutes  of real-world fine-tuning. The released code covers pretraining, policy distillation and the real-robot rollout script.
