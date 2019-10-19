# Introduction

This repo contains code to accompany my blog post titled [Why Pandas itertuples() Is Faster Than iterrows() and How To Make It Even Faster](https://medium.com/@_init_/why-pandas-itertuples-is-faster-than-iterrows-and-how-to-make-it-even-faster-bc50c0edd30d)

# Usage

There are only two notebooks, namely:
* [pandas_row_iteration_analysis](./pandas_row_iteration_analysis.ipynb): This contains all the timings and profiles for the various methods described in the blog post.
* [itertuple_stats](itertuple_stats.ipynb): This contains a more detailed analysis of the profile for the `itertuples()` solution.
