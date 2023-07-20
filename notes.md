Text summarization is the process of automatically generating a shorter version (summary) of a given text while retaining its main ideas and key points. There are several methods for text summarization, broadly categorized into two types: extractive summarization and abstractive summarization.

Extractive Summarization:
Extractive summarization involves selecting and extracting important sentences or phrases directly from the original text to create a summary. These methods do not generate new sentences but use existing ones. Common techniques for extractive summarization include:
1. Frequency-based methods: Identify and extract sentences that contain the most frequently occurring words or phrases in the text. The assumption is that important content is often mentioned repeatedly.
2. TF-IDF (Term Frequency-Inverse Document Frequency): Assign weights to words based on their frequency in the text and their rarity across the entire document collection. Sentences with higher TF-IDF scores are considered more important and are selected for the summary.
3. Graph-based methods: Represent sentences as nodes in a graph, where the edges between nodes represent the similarity between sentences. Then, use algorithms like PageRank to identify the most central and significant sentences for the summary.
4. Machine Learning (ML) methods: Train a supervised learning model using features extracted from sentences (e.g., word frequency, sentence length, etc.) and their corresponding summary labels.

Abstractive Summarization:
Abstractive summarization aims to create a summary by paraphrasing and rephrasing the content in a more concise and coherent manner. This requires the model to generate new sentences, often resulting in more human-like summaries. Common techniques for abstractive summarization include:
1. Sequence-to-Sequence models (Seq2Seq): Use deep learning models, such as Recurrent Neural Networks (RNNs) or Transformer-based architectures, to map the input text to a fixed-length vector and then decode it to generate the summary.
2. Pointer-Generator Networks: A variation of Seq2Seq models that includes a pointer mechanism to allow the model to copy words directly from the input text when needed, enabling a more faithful summary.
3. Pre-trained Language Models: Utilize large pre-trained language models like BERT or GPT to perform text summarization by fine-tuning them on a summarization dataset.
4. Reinforcement Learning: Combine supervised learning with reinforcement learning to optimize the generated summaries based on reward functions that measure the quality of the summaries.
5. Transformer-based models: Models like BART (Bidirectional and Auto-Regressive Transformers) are designed for various NLP tasks, including text summarization, and have shown promising results.

Text cleaning is an essential preprocessing step in natural language processing (NLP) tasks. It involves removing irrelevant or noisy information from the text to make it suitable for analysis. Here are some common methods for text cleaning:
1. Lowercasing:    Convert all text to lowercase. This helps in standardizing the text and ensures that words in different cases are treated as the same.
2. Tokenization:    Split the text into individual words or tokens. Tokenization makes it easier to process and analyze the text on a word-level basis.
3. Removing Punctuation:    Remove all punctuation marks (e.g., commas, periods, exclamation marks) from the text. Punctuation is generally not relevant for most NLP tasks.
4. Removing Numbers:    Remove numerical digits from the text unless they are essential for the analysis.
5.  Stopword Removal:    Eliminate common words (stopwords) that do not carry much meaning in the context of the analysis (e.g., "the," "is," "and," "in").
6. Stemming and Lemmatization:    Reducing words to their root form can help reduce variations of the same word. Stemming and lemmatization techniques aim to convert words to their base or dictionary form (e.g., "running" -> "run," "better" -> "good").
7. Handling Contractions:    Expand contractions (e.g., "can't" to "cannot," "won't" to "will not") to ensure consistency in word forms.
8. Removing HTML Tags and URLs:    For text obtained from web sources, remove HTML tags and URLs that may not be relevant for analysis.
9. Handling Special Characters:    Deal with special characters or symbols that might not have any significance for the analysis. Depending on the use case, you may choose to remove or replace them.
10. Handling Emojis and Non-English Characters:    Decide how to handle emojis and non-English characters. You may remove them, replace them with text representations, or keep them based on the specific requirements of your analysis.
11. Handling Whitespaces and Newlines:    Remove extra whitespaces and newlines to ensure consistent formatting.
12. Spell Checking and Correction:    Use spell checking libraries or algorithms to correct common spelling mistakes.

Text cleaning is a crucial step in preparing data for NLP tasks like text classification, sentiment analysis, topic modeling, and more. The specific methods and level of cleaning required depend on the nature of the text data and the objectives of the NLP analysis.
