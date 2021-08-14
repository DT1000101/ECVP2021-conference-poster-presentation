# ECVP2021 conference poster presentation

Please see the poster pdf [here]()
<br/>
<br/>

# Preview

## Continual Learning for Object Classification: Consolidation and Reconsolidation


### Daniel Turner, Pedro J.S. Cardoso, João M.F. Rodrigues 
### LARSyS & Instituto Superior de Engenharia, Universidade do Algarve, Faro, Portugal

#### **Abstract**
To achieve "consolidation", short-term memory's conversion
to long-term memory requires the passage of time. This
consolidation can occur at many organizational levels in the
brain, e.g., simplifying, when two neurons repeatedly fire at
the same time, they become more likely to fire together in the
future. Eventually, these two neurons will become sensitized
to one another. The brain progressively creates more of these
connections when new information or experiences are
presented. However, just because a memory has been
consolidated it does not mean that it cannot be lost. Literature
shows that memories often need to be reconsolidated once
they have been recalled. In deep artificial neural networks,
there is the tendency to forget previously learned information
completely and abruptly upon learning new information,
usually called catastrophic forgetting. We propose a Deep
Modular Dynamic Neural Network (MDNN) based on
“consolidation” and “reconsolidation” principles, capable of
learning new information and mitigating the catastrophic
forgetting issue. MDNN is divided in two blocks: (a) the
feature extraction block, based on a ResNet50, and (b) the
modular dynamic classification block, made up of modular
sub-networks that progressively grow in a tree shape and rearranges themselves as they continuously learn. Once one of
these branches learn an object then it is “consolidated”. If a
new object is assigned to a branch that already has
consolidated objects, then all the existing objects in that
branch are “reconsolidated”, this process occurs on the fly.
The network presents state of the art results on CORe50
dataset. [LARSyS - FCT Project UIDB/50009/2020]
