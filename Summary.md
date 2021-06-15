# Summary
In this document, we present the tables summaried form the papers cited in the paper list.

## Multimodal Dialogue
| Paper | Dataset | Visual Encoder | Language Model | Encoder | Decoder |
| --- | --- | --- | --- | --- | --- |
| Towards Building Large Scale Multimodal Domain-Aware Conversation Systems | MMD | VGGNet-16 | Bidirectional RNN network with GRU | GRU (HRED) | GRU + Attention |



## Schema-Guided Dialogue (SGD)

| Paper | Issue | Dataset | Language Model | Encoder | Decoder |
| --- | --- | --- | --- | --- | --- |
| The JDDC Corpus: A Large-Scale Multi-Turn Chinese Dialogue Dataset for E-commerce Customer Service |  | JDDC | Multimodal Dialogue Dense Retriever; Multimodal Hierarchical Encoder Decoder |
| Towards Scalable Multi-domain Conversational Agents: The Schema-Guided Dialogue Dataset | Benchmark; Zero-shot DST | SGD | BERT-DST (Schema Embedding Module + State Update Module) | BERT | Softmax |
| CrossWOZ: A Large-Scale Chinese Cross-Domain Task-Oriented Dialogue Dataset |  | CrossWOZ |  | BERTNLU-context | 
| STAR: A Schema-Guided Dialog Dataset for Transfer Learning | Zero-shot generalization across tasks and domains; Schema = task specification ≠ **S**GD | STAR | BERT (language + schema; classification); BERT (for generation)  | BERT+classifier (for generation) | Fine-tune GPT-2 (for generation) |
| RiSAWOZ: A Large-Scale Multi-Domain Wizard-of-Oz Dataset with Rich Semantic Annotations for Task-Oriented Dialogue Modeling |  | RiSAWOZ | BERT + context (for NLU); TRADE + MLCSG (for DST); DAMD (for Context2Text Generation); e2e-coref (for Coref Resolution); GECOR (for Unified generative ellipsis + Coref Resolution) |
| Action-Based Conversations Dataset: A Corpus for Building More In-Depth Task-Oriented Dialogue Systems |  | ABCD |
| Adding Chit-Chats to Enhance Task-Oriented Dialogues | Integrate both types of systems (task-oriented systems + open-domain chatbots) | ACCENTOR |  |  |  |

## Dataset
| Paper | Dataset | Domain | Size |
| --- | --- | --- | --- |
|
