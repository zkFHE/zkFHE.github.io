---
title: Home
layout: home
nav_order: 1
---

This is a collections of ressources on combining fully homomorphic encryption and zero-knowledge proofs to achieve flexible and robust computation on encrypted data fit for real-world deployments. 

Browse our ressources (code, blog, and presentations) to learn more about what we're trying to solve, what we've done, and the challenges that remain. 

## What are we trying to solve?

Fully Homomorphic Encryption (FHE) has been dubbed the "Holy Grail of Cryptography"[^1], as it enables (arbitrary!) computations to be performed on encrypted data. 
However, all known standard FHE schemes break catastrophically when used in realistic threat models like the ones we expect from the real world. If you want to learn more, read our blog post "[FHE's dirty little secret -- A decade of reaction attacks](blog/fhe_dirty_little_secret.md)". 

We believe that FHE holds tremendous potential to enable more secure and private applications, and we really want to see FHE deployed in the wild. 
That's why we're trying to tackle this challenge, both with theoretical work and practically-oriented solutions. 

## Who we are

We are a loose collective that originally started in the [privacy-preserving systems lab](https://pps-lab.com) at [ETH Zurich](https://ethz.ch/en.html). Core contributors include: 
- [Christian Knabenhans](https://cknabs.github.io) (EPFL), maintainer
- [Alexander Viand](https://pps-lab.com/people/alexanderviand/) (Intel Labs)
- [Anwar Hithnawi](https://pps-lab.com/people/anwarhithnawi/) (ETH Zurich)
- [Antonio Merino Gallardo](https://amerigal.github.io/) (ETH Zurich)

---
[^1]: It is surprisingly hard to figure out where the "holy grail" characterization first appeared; the first written mention seems to be by Micciancio in [_Communications of the ACM (2010)_](https://dl.acm.org/doi/10.1145/1666420.1666445). 