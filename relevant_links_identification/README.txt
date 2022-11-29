We are focused on identifying relevant linked elements
*We are assuming that we'll have access to a page index that we can leverage to find all page number based linked elements.

This leaves, the non-page number based linked elements as the problem space we'll pursue
Brayton
We need document text blobs....
tools to do this? by hand?
We need to research linked element composition
What's the possible fingerprint space of the elements we care about?
We need to explore NLP transformations
tokenizing, n-grams

Josh
We need to identify token matches:
We need to explore efficacy of 1-to-1 token matching
We need to explore potential model based matching
*Matches should be part of the feature space (and pre-inference filter)

Chris
Identify relevant tokens (classification):
We need to label data
We need to explore classification approaches