---
title: "Wikipedia Turkish Dataset Release"
date: 2023-03-19T16:45:48+03:00
draft: false
---

Hello, language enthusiasts! I am excited to announce the release of my personal side-project: the Wikipedia Turkish February 2023 dataset! This dataset is a comprehensive collection of articles from the Turkish Wikipedia, specifically designed for masked language modeling and text generation tasks. As a passionate advocate for the development and exploration of the Turkish language, I am thrilled to share this resource with the community.

In this blog post, I'll be giving you a brief overview of the dataset, its features, and how you can utilize it for your projects.

##  📘 Dataset Overview

The Wikipedia Turkish February 2023 dataset is based on the Wikipedia dump of "20230220" and has been processed and cleaned using Huggingface wikipedia cleaner. It is organized into one split: "train", which contains 512,377 examples and has a size of 935,821,219 bytes.

Each example in the dataset includes the following features: id, url, title, and text. The "id" feature is a string, while the "url", "title", and "text" features are all of dtype string. The dataset is written in Turkish and was created using crowdsourcing methods by a team of volunteers.

##  🏷️ Annotations and Usage

The articles in this dataset were not specifically annotated for any particular task, meaning that the dataset is unlabeled. This makes it ideal for tasks such as masked language modeling and text generation, where the focus is on understanding and generating text based on the given context.

##  🌐 Language and Multilinguality

The Wikipedia Turkish February 2023 dataset is exclusively in the Turkish language, making it a valuable resource for researchers and developers working on natural language processing (NLP) tasks for the Turkish language.

##  📜 Licensing

The dataset is released under two licenses: CC-BY-SA 3.0 and GFDL. These licenses allow for the free use and distribution of the dataset, provided appropriate attribution is given.

##  💻 How to Use the Dataset

The Wikipedia Turkish February 2023 dataset is designed to be used for two main tasks: fill-mask and text-generation. You can use this dataset with Hugging Face's transformers library to train a masked language model or generate text using pre-trained models.

##  📥 Download Size

The download size of the Wikipedia Turkish February 2023 dataset is 518,914,544 bytes.

In conclusion, the Wikipedia Turkish February 2023 dataset is a fantastic resource for anyone looking to work on masked language modeling and text generation tasks in the Turkish language. I am delighted to share this dataset with the community and hope that it proves valuable for your projects. Please feel free to use, share, and build upon this dataset, and I look forward to seeing the innovative ways in which you utilize it!

Happy language modeling!

[Link](https://huggingface.co/datasets/musabg/wikipedia-tr)