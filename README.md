# textsumeval22
Automatic summarization is one of the most difficult tasks in Natural Language Processing as it requires a comprehensive understanding of input documents, identification of relevant content, and generation of a synthetic perspective of the document, often subject to a length constraint. Yet, this task is very important in the context of the deluge of varying quality information our generation has to tackle. Building better summarization systems requires progress in summarization evaluation metrics, which are used to assess the quality of the summaries they produce. There is two current trends to summarization evaluation: manual and automatic evaluation. Manual evaluation consists in ranking summaries or parts of summaries according to a set of factors such as faithfulness to the original, linguistic fluency. The automatic evaluation focuses more on comparing the system production to a set of human-authored summaries deemed a gold standard. Manual evaluation is more accurate but much more costly than automatic evaluation, and it is often not actionable in a machine learning environment (systems require rapid and repeated evaluation of their output in order to learn how to summarize). Current methods for automatic evaluation fail because they involve a too candid representation of meaning (through word n-grams for ROUGE, for example), a problem which has been identified as a major hurdle for the advancement of the field. So, the aim of this shared task is to design an automatic evaluation system for system generated summaries where the evaluation system will compare the test summaries with gold summaries and estimate their relevance in terms of BLUE, and ROUGE scores.
