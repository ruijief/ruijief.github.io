---
layout: post
title:  "Motion Planning for Kinematic Snake under singular configuration"
time: "January - October 2020"
image: /images/kinematic.png
categories: research
background: https://epjst.epj.org/articles/epjst/abs/2015/16/epjst150085/epjst150085.html
paper: https://arxiv.org/abs/2102.01506
authors: "<strong>Ruijie Fu</strong>, Shuoqi Chen, Ross Hatton, Howie Choset"
keyword: <img src="https://img.shields.io/badge/-Matlab-blue"/>&nbsp;<img src="https://img.shields.io/badge/-geometric mechanics-green"/>&nbsp;<img src="https://img.shields.io/badge/-robot singularity-green"/>&nbsp;<img src="https://img.shields.io/badge/-snake robot-yellow"/>&nbsp
---
Kinematic snake runs into singular configurations when the nonholonomic constraints are violated (e.g. one or more of the constraint equations becomes a linear combination of the others), at which point the matrix inverse becomes analytically unsolvable and thus causing discontinuities. We propose an optimization algorithm for finding high-efficient gait of nonholonomic kinematic snake that purposely enclose the singularity region, which ultimately produces the best gaits given specified input energy cost functions. Refer to the back ground paper linked above for the application of geometric mechanics to studying robot locomotion.
