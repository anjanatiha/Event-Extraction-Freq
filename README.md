# Event Extraction based on Natural Frequency

## Procedure

Extracting events based on frequency of words found in news corpus. The event extraction system operates on simple logic that verbs and non proper nouns that are less frequently found in general purpose corpus are distinct word that indicates probabale events.

The steps are as follows
1. Remove stopwords
2. Ignore proper nouns
3. Verify frequency of both original word in text and its root word to decide if this word is unique in general corpus and viable candidate to indicate its a event word.

This advantage of this approach is we do not need to use expensive hardware with gpus or complex computation heavy deep learning algorithms. The frequency dictionary is calculated just once and takes less than 10 minutes. Also, the inference process is extremely fast as this is normalized frequency is stored in dictionary. So both traditional sense training and inference is extremly fast.

## Pros and Cons:
Pros of this approach:
1. Fast training
2. Low resource requirements.
3. Fast inference
4. Performance is comparable to deep learning based one but is still waiting for through testing.

Cons:
1. The dataset used in this project may have limitation. 

## Examples coming soon
