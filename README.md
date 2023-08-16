# Are-two-questions-similar
Are Two Questions Similar? Using K Means Clustering to predict whether two questions are semantically similar. 

This was my final year project for University, which was submitted on Monday 25th April 2022.

This repo will contain parts of my report where I talk about:
- the problem domain
- Requirement specification
- Implementation/code
- Testing
- Appendix

The code will be slightly altered to reflect how I would write/design my projects now, the results and outcomes of my report will reflect this. Whilst, this won't be a full re-write of the code and report, it will be a much more up to date and in-line with what I would want to present. 

This is a machine learning project focussing on the unsupervised machine learning algorithm, K-Means Clustering. This project mainly uses machine learning libraries, as well as a library for stop words, to achieve the outcome, as the goal was to not reinvent the wheel but rather understand it and apply it to a problem.

However, I would like to rewrite this program without the use of machine learning libraries in a language like Rust. It's more to test my understanding of the algorithm as well as writing software, I personally don't find the mathematics behind K-Means to be too hard, and writing it in faster than Language than Python would be a bonus. 

At some point my GitHub may have that project done.

-----------------------------------------------

# Abstract
Internet forums are places where like-minded people can discuss just
about anything they have an interest in. The world has become a much smaller
place since we have had the internet and people from every corner of the earth
are able to discuss and share ideas as well as ask for help.

These forums are sometime visited by a passer-by who just needs help with
something, or they have a question. Frequent users may get tired of answering the
same questions over and over, whilst the users coming to the forum might find it
difficult to find the right answer to their question when so many similar pages
have been made already. These pages are not kept in an ethereal plane either,
hosting big sites require lots of memory and physical space.

This report aims to find to apply an unsupervised machine learning algorithm,
called K means to being able to accurately detect if two questions are
semantically similar or not.

This report will also discuss if the implementation is feasible, based on accuracy
as well as time and space complexity.

# Preface
Sentence semantics refer to the meaning of a sentence as whole. The
constituent words can have different meanings depending on the other words in
the sentence, and thus, a sentences semantics are a product of the words it
contains, though to us, understanding this is natural. We could tell, for example, if
two questions were the similar in meaning but a computer cannot. There are ways
in which computers are able to interpret natural language, not just low/high level
programming languages. This paper will dive into to field behind this.