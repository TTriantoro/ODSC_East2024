# Prompts for Data Synthesis, Augmentation, and NLP Insights with LLMs
# Instructor: Tamilla Triantoro

This tutorial is created for my session on "Data Synthesis, Augmentation, and NLP Insights with LLMs" that takes place at ODSC East conference in Boston in April 2024. To use, simply copy and paste the prompts using LLM of your choice. This tutorial works well with a free version of ChatGPT.

<h2>Lesson 1: Data Synthesis</h2>

<h3>Generate data:</h3>

-	Generate a customer review

-	Generate a consumer review for an electronic watch. Ensure the review is realistic, covering aspects such as product quality, customer service experience, delivery, and overall satisfaction. Avoid including any real names, locations, or sensitive personal information. The length of review is up to 50 words.

-	Generate a set of ten reviews for an electronic watch with various customer perspectives. Please ensure the reviews are realistic. Avoid including any real names, locations, or sensitive personal information. The length of each review is less than 50 words. Display reviews as a table that can be easily copied to Excel.

<h2>Lesson 2: Data Augmentation</h2>

<h3>Data Augmentation Techniques:</h3>

-	Perform rule-based perturbations on the following customer review to create five varied versions of it. The original review is: 'The watch looks and feels premium. I highly recommend it.' Apply the following rule-based perturbations:
o	Synonym Replacement: Change words to their synonyms without altering the overall sentiment.
o	Character Swap: Introduce a typo by swapping two adjacent characters in a word.
o	Random Insertion: Add a relevant adjective or adverb to enhance a description.
o	Deletion: Remove a non-critical word without changing the essential meaning.
o	Pronoun Substitution: Change pronouns to make the review gender-neutral.
Your task is to create variations that maintain the original review's meaning and sentiment while demonstrating each type of perturbation. The goal is to generate data that can help train a model to understand and process text with slight variations.

<h3>Positive and Negative Augmentation:</h3>

-	Transform the customer review sentence “'The watch looks and feels premium. I highly recommend it” into six different augmented versions, one for each class:
o	Alternation: Change the sentence from active to passive voice without altering its meaning.
o	Redundancy: Add words to the sentence that can be removed without changing its meaning.
o	Nominalization: Transform verbs in the sentence into nouns.
o	Lexical Contradiction: Modify words in the sentence so that it contradicts the initial sentiment.
o	Negation: Rewrite the sentence to deny the truth of the original content.
o	Random Sentence: Create a new review about the product that is unrelated to the initial review about the product.
Ensure each transformed review reflects the specific augmentation class it represents and maintain grammatical correctness in all variations.


<h3>Augment the dataset with simulated content:</h3>

-	Generate a prompt to augment the existing dataset of consumer reviews by adding (add all requirements here)

-	Augment our existing dataset of consumer reviews for an electronic watch by adding a 'Response' column. Your task is to craft responses that align with the sentiment of each review. For positive reviews, express gratitude toward the customer, emphasizing appreciation for their feedback, especially regarding keywords related to 'quality,' 'design,' and 'service.' For example, if a positive review mentions the watch's design, you might respond with, 'Thank you for recognizing our watch's design. We're thrilled you love it!' For negative reviews, offer support and a willingness to address their concerns, particularly those related to 'quality,' 'design,' and 'service.' If a negative review highlights issues with service, a suitable response could be, 'We're sorry to hear about your experience. How can we make it right?' Your responses should feel personal, considerate, and directly address the specifics mentioned in each review, focusing on turning feedback, whether positive or negative, into an opportunity to enhance customer satisfaction.

<h2>Lesson 3: NLP Insights</h2>

<h3>Text Preprocessing:</h3>

-	Make all words lowercase, remove punctuation, stop words and perform lemmatization of this review “'The watch looks and feels premium. I highly recommend it”

<h3>Topic Modeling</h3>

-	Read the reviews in the table, perform topic modeling. What are the five popular topics?

-	Read the reviews. Extract 5 important keywords. Rank them by popularity, evaluate sentiment for each keyword, provide an explanation.

<h3>Sentiment Analysis</h3>

-	Perform sentiment analysis for generated reviews. 

<h3>Content Analysis</h3>

-	Perform a deductive content analysis on customer reviews. Start with predefined themes such as 'design', 'customer service', 'battery life', and 'quality'. Categorize the content, tagging excerpts of the reviews under these themes. Quantify the occurrences and provide context for how these terms are used, focusing on insights that could steer product development or marketing.

-	Perform an inductive content analysis of the same reviews. Without preconceived categories, immerse yourself in the data to let new themes emerge organically. Look for repeated patterns, sentiment expressions, and novel phrases, creating categories as they appear. Document these emergent themes, providing examples and exploring their potential impact on business strategy and customer experience.

-	Select only negative reviews.

-	Select only reviews about the perception of design.

<h3>Data Visualization</h3>

-	What type of charts can you create to visualize generated reviews?

-	Create a bar chart

-	Create a word cloud graph
