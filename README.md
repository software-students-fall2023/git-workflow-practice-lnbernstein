# Git Practice
An article that I find interesting is this article on
[Apache Arrow](https://thenewstack.io/how-apache-arrow-is-changing-the-big-data-ecosystem/).

Apache Arrow is an open-source project intended to provide a standardized memory format for tabular data. It is currently being adopted as the back-end data storage style for pandas, the most commonly used data analytics library for Python. Some of the benefits of Apache Arrow are increased performance without the need for serialization, bulk data ingress and egress, and perhaps most importantly, universal access potential across platforms and ecosystems. It has been adopted by the most prevalent SASS data brokers and generative AI platforms such as IBM Watson X. By the adoption of common data formats such as Apache Arrow, faster software development workflows are possible. 


## Comment from jamesluo:

I think article is really cool and I had no idea about Apache before reading this. Apache Arrow is open source and improves performance by removing the need to serialize and deserialize data when moving between different tools and languages. By converting data to the arrow format, processing and manipulating data is much faster as it is designed for modern CPUs and GPUs. Data can be processed in parallel. 