# docker-calibre2opds

## Summary

This demo shows how to use [calibre2opds](http://calibre2opds.com/) with [Docker](http://www.docker.com).

related github repositories:

1. [calibre2opds sources](https://github.com/calibre2opds/calibre2opds)
2. [docker friendly ubuntu baseimage](https://github.com/phusion/baseimage-docker) 

## Motivation

same as: [Motivation for docker-cops](https://github.com/TomNussbaumer/docker-cops/blob/master/README.md)

... but this time around using a static website approach. Additionally I want to play around with [the phusion baseimage](https://github.com/phusion/baseimage-docker), which looks like it fixes the standard ubuntu problems when running within docker.

## Details

After playing around with calibre2opds for a few hours, I think it is an absolute horrible product. I don't mind it's written in Java (I used Java for over 10 years), but it's internal structure is a mess, it's hard to customize and it's buggy like hell. For example: why bother writing scripts for linux when they don't run without errors? Come on ... that's stupid.

Okay. Let's ask Doctor Google for another advice ;)
