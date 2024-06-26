# Group Allocation

We implemented an algorithm to partition study participants on comparable groups. The algorithm is a heuristic that aims at minimizing skill differences between study groups. Although not needed to replicate our results, we release the implementation, for further transparency and easier extension of our work.

## Source Code

The documented source code of the {--[MiniMax implementation and documentation](https://github.com/m5c/RestifyGroupPartitioner) is available on GitHub--} {==[Minimax implementation and documentation is available as local filesystem snapshot](../../RestifyGroupPartitioner/README.md)==}.

## Explanations

We implemented a custom MiniMax Heuristic, to assess the participant's skill profiles and create balanced experiment groups.  

 * To maintain transparency we provide source code and documentation of the heuristic used to create the participant allocations.
 * The program parses all provided self assessment forms (see [corresponding entry of replication bundle](recruitment.md)) which they provided during recruitment, and then performs a [MiniMax search](https://en.wikipedia.org/wiki/Minimax) for the fairest group allocation.
 * A side product of this software is the generation of personalized emails for following communication with the individual participants. 

 > Since the purpose of this program is to select of all applicants and provide a mapping from their legal names to group-specific pseudonyms, it can be only executed with access to the sensitive participant sheets. The latter we do not release, to protect participant privacy.


