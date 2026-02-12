# HOPE_NL_CMS
 
## Continuum Multi-Timescale Memory System (CMS) for Continual Learning
PyTorch implementation of the Continuum Multi-Timescale Memory System (CMS) introduced in Nested Learning: The Illusion of Deep Learning Architectures (NeurIPS 2025), together with controlled continual-learning experiments analyzing its impact on catastrophic forgetting.

# First section of this repo implements 
This repository implements and evaluates the Continuum Multi-Timescale Memory System (CMS) proposed in:
Ali Behrouz et al., Nested Learning: The Illusion of Deep Learning Architectures, NeurIPS 2025.

## Nested Learning perspective
Neural architectures and optimizers are viewed as nested optimization processes operating at different update frequencies.
Each process acts as an associative memory that compresses information from its own temporal context.


## Continuum Multi-Timescale Memory System (CMS)
CMS distributes memory across multiple parameter blocks, each updated at a distinct frequency:

-->Fast blocks adapt quickly to recent data
-->Slow blocks evolve gradually and retain long-term knowledge
