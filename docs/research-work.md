---
layout: default
title: Research work
nav_order: 3
permalink: /research-work/
---

**Communication cost for secret recovery in Quantum Secret Sharing**

Quantum secret sharing, or QSS, is a quantum cryptographic primitive where a secret is encoded into quantum information and distributed among multiple parties.
In QSS schemes, only authorized sets of parties are allowed to recover the information about the secret while unauthorized sets cannot recover any information on the secret.
My work with Prof. Pradeep Sarvepalli at IIT Madras proposed QSS schemes, based on quantum error correcting codes, which aim at reducing the communication cost during secret recovery.
We introduced the class of _Communication Efficient Quantum Secret Sharing_ schemes which reduce communication cost while accessing more than necessary number of parties [[1]](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.100.052313).
We derived the bound on communication cost for such schemes and provided two optimal constructions [[2]](https://ieeexplore.ieee.org/abstract/document/9674910/).

**Storage cost - repair bandwith tradeoff in Regenerating codes**

Regenerating codes are classical codes used for distributed storage which focus on two parameters.
<br>{: .mb-1} 1) How much memory space is needed to store the data reliably across multiple nodes?
<br> 2) How much bandwidth is needed while repairing one of the failed nodes?
<br>{: .mb-1} There exists a tradeoff between these two parameters whose extreme points had been characterized earlier.
However the interior points of the tradeoff are yet to be fully characterized.
My work in Codes and Signal Design lab at IISc jointly with Birenjith Sasidharan and Prof. Vijay Kumar helped towards a better characterization of this tradeoff.
Our work involved two approaches.
First, we built upon an exisiting information-theoretic approach to tighten the outer bound of the tradeoff [[3]](https://ieeexplore.ieee.org/abstract/document/6875270/).
We also proposed a class of regenerating codes called improved layered codes which gave performance very close to the tradeoff and even optimal under certain conditions [[4]](https://ieeexplore.ieee.org/abstract/document/7133121/).
