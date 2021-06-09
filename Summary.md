# Summary
In this document, we present the tables summaried form the papers cited in the paper list.

## Multimodal Dialogue
| Paper | Dataset | Visual Encoder | Language Model | Encoder | Decoder |
| --- | --- | --- | --- | --- | --- |
| Towards Building Large Scale Multimodal Domain-Aware Conversation Systems | MMD | VGGNet-16 | Multimodal HRED Model |  Bidirectional RNN network with GRU | GRU + Attention model |
| The JDDC Corpus: A Large-Scale Multi-Turn Chinese Dialogue Dataset for E-commerce Customer Service | JDDC |


## Schema-Guided Dialogue (SGD)

| Paper | Dataset | Language Model | Encoder | Decoder |
| --- | --- | --- | --- | --- |
| Towards Scalable Multi-domain Conversational Agents: The Schema-Guided Dialogue Dataset | SGD | BERT-DST (Schema Embedding Module + State Update Module) | BERT | Softmax | Benchmark; Zero-shot DST |
| CrossWOZ: A Large-Scale Chinese Cross-Domain Task-Oriented Dialogue Dataset | CrossWOZ |  | BERTNLU-context | 
| STAR: A Schema-Guided Dialog Dataset for Transfer Learning | STAR | Schema-free model; Schema-guided BERT classifier; Fine-tune GPT-2 (for generation) | BERT | Linear layer; Softmax | Zero-shot generalization across tasks and domains; Schema = task specification ≠ **S**GD |
| RiSAWOZ: A Large-Scale Multi-Domain Wizard-of-Oz Dataset with Rich Semantic Annotations for Task-Oriented Dialogue Modeling | RiSAWOZ |
| Action-Based Conversations Dataset: A Corpus for Building More In-Depth Task-Oriented Dialogue Systems | ABCD |
| Adding Chit-Chats to Enhance Task-Oriented Dialogues | ACCENTOR |  |  |  | Integrate both types of systems (task-oriented systems + open-domain chatbots) |

## Dataset
| Paper | Dataset | Domain | Size | Data Colletion Method |
| --- | --- | --- | --- | --- |
|
