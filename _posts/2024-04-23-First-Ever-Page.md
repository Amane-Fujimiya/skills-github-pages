---
title: "First Ever Page"
date: 2024-04-23
---
# Preliminaries

Our examples frequently involve sequence, of which is a finite list of elements of a certain type, denoted $[a_{0},\dots,a_{n-1}]$. The set of sequences over $A$ is denoted $Seq(A)$. Further operations are: 

1. tips $=$ $a\mapsto [a]:A\to Seq(A)$. 
2. cons = $(a,[a_{0},a_{1},\dots,a_{n-1}])\mapsto[a,a_{0},\dots,a_{n-1}]$. Formally, $A\times Seq(A)\to Seq(A)$.     
3. joins $= ([a_{0},\dots,a_{m-1}],[a_{m},\dots,a_{n-1}])\mapsto[a_{0},\dots,a_{n-1}]$. Formally, $Seq(A)\times Seq(A)\to Seq(A)$. 
4. $Seq(f)$ (function mapping) $= [a_{0},\dots,a_{n-1}]\mapsto[f(a_{0}),\dots,f(a_{n-1})]$. Formally, $Seq(A)\to Seq(B)$ whenever $f:A\to B$ is a morphism. 
5. $\bigoplus /$ (direct sum) $=[a_{0},\dots,a_{n-1}]\mapsto a_{0}\oplus\dots \oplus a_{n-1}$. Formally, $Seq(A)\to A$ whenever $\bigoplus:A\times A\to A$. and $\bigoplus$ is associative and has a neutral element. 
