Anti-CRISPRs (Acr) proteins suppress natural CRISPR-Cas immunity and are thus a novel class of proteins that have been exploited for various biotechnological applications. Most notably, Acrs are used to optimize genome editing to limit off-targeting effects and to direct genome editing based on certain biological cues. Despite Acrs’ viability, there exists no streamlined computational pipeline to create and validate these proteins efficiently. To this end, we expect that protein language models (pLMs) fine-tuned on Acr sequences will interpret and capture physicochemical information characteristic of Acrs, enabling their downstream generation. Here, we present APE, a pipeline of fine-tuned pLMs that generate de novo Acr protein sequences and uncover a set of mutations on the generated sequences that improve their stability. Our sequence-based models do not rely on structural information and thus present a novel approach to generating Acr sequences. We leverage a fine-tuned variant of the ProtGPT2 pLM to generate 10,000 Acr sequences, with the 10 generated sequences of highest confidence achieving average scores of 80.3 and 45.6 on AlphaFold2’s and ESMFold’s pLDDT benchmark, respectively. We further utilize a fine-tuned ESM-2 pLM to uncover mutations on select Acr sequences that improve their stability. These mutant variants achieved average scores of 78.2 and 40.5 on AlphaFold2’s and ESMFold’s pLDDT benchmarks, respectively. Although the average pLDDT scores are lower for mutant variants compared to their de novo counterparts, select mutants display greater pLDDT scores, demonstrating the potential of using fine-tuned pLMs for engineering stable Acr proteins. Our work creates utility for various programmable proteome applications, including the design of Acrs with lower off-targeting effects and, thus improved therapeutic applications.
