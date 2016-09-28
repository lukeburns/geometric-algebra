# Geometric Algebra

This is a work in progress explanation of geometric algebra. Please [open an issue](https://github.com/lukeburns/geometric-algebra/issues) or [fork and submit a pull request](https://github.com/lukeburns/geometric-algebra/pulls) if you find a mistake or room for improvement.

## Introduction

*Geometric algebra* is a language that generalizes vectors to higher dimensional objects. Vectors are useful for encoding the notion of a directed line segment, and we find that the extension of this to *bivectors* (as oriented planes), *trivectors* (as oriented volumes), and *k-vectors* (as oriented k-dimensional volumes), leads one to rich and robust algebraic structures grounded in geometric meanings. **k** is called the **grade** of a vector. Naturally, 0-vectors, are simply magnitudes (real numbers) with no dimensionality at all.

I will use italics to indicate a word that the reader is not yet expected to know, using context in order to facilitate the learning of its meaning. Bolded font is used to indicate that I believe the meaning of the word has been sufficiently communicated. If you come across a bolded word, and do not know what I mean, re-read! I will consider that I've accomplished my job if I help you learn how to use the concepts here productively and consistently.

My mission here is to formalize the notion of grade using a product called the *geometric product* and introduce you to new objects of mixed grade called *multivectors*, in particular certain multivectors called *spinors*.