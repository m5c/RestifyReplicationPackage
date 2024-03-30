# Group Allocation

## Source Code

The source code of the [MiniMax implementation and documentation](https://github.com/m5c/RecruitmentFormInterpreter) is available on GitHub.

## Explanations

We implemented a custom MiniMax Heuristic, to assess the participant's skill profiles and create balanced experiment groups.  

 * To maintain transparency we provide source code and documentation of the heuristic used to create the participant allocations.
 * The program parses all provided self assessment forms (see [corresponding entry of replication bundle](recruitment.md) which they provided during recruitment, and then performs a [MiniMax search](https://en.wikipedia.org/wiki/Minimax) for the fairest group allocation.
 * A side product of this software is the generation of personalized emails for following communication with the individual participants. 

 > Since the purpose of this program is to select of all applicants and provide a mapping from their legal names to pseudonyms, it can be only executed with access to the participant details. The latter we cannot release for legal reasons.


