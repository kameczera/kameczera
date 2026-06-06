# Leonardo Kamei

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leokamei/)

## About Me

- Computer Science student at PUC-MG and Electrical Engineering student at CEFET-MG.
- Research experience in image analysis at the IMScience Lab.
- Interested in compilers, artificial intelligence, high-performance computing, computer architecture, and programming languages.
- Currently working on compiler-related projects, including operator fusion benchmarks and a compiler written in Go.

## Technologies I Use Daily

<div style="display: inline_block">
  <img align="center" alt="c" src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
  <img align="center" alt="java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img align="center" alt="cpp" src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img align="center" alt="python" src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white" />
  <img align="center" alt="rust" src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img align="center" alt="haskell" src="https://img.shields.io/badge/Haskell-5e5086?style=for-the-badge&logo=haskell&logoColor=white" />
  <img align="center" alt="js" src="https://img.shields.io/badge/JavaScript-ffcd00?style=for-the-badge&logo=javascript&logoColor=white" />
  <img align="center" alt="cuda" src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
  <img align="center" alt="go" src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
</div>

<br/>

## Projects

### Ararinha

A project developed at Hackatruck Makerspace aimed at helping children with Autism Spectrum Disorder communicate.

### Interpreter in Rust

An interpreter written in Rust, based on the book *Crafting Interpreters*.  
The project implements a simple programming language and explores concepts such as lexical analysis, parsing, interpretation, and language design.

### NAFLD — Non-Alcoholic Fatty Liver Disease

A project developed in the Image Processing and Analysis discipline, focused on identifying liver fat through a graphical application using AI techniques, including XGBoost and Inception.

### PUC Simulator

A multithreading simulator developed in Java, supporting SMT, IMT, and BMT models with scalar and superscalar architectures.  
The project includes a graphical interface for visualization and analysis.

### compilers-benchmark

My undergraduate thesis project, focused on **operator fusion** in modern machine learning compilers.

In this project, I investigate the trade-off between **compilation time** and **execution time** in compiler backends such as **PyTorch 2 / TorchInductor** and **XLA**. The work studies how different operator fusion strategies affect performance, especially in common deep learning kernels such as **BatchNorm + ReLU** and **BatchNorm → Conv**.

As part of the project, I developed a benchmark/tool that helps identify which backend is more suitable depending on the execution scenario, considering both time-to-first-batch and repeated execution regimes.

This work is currently in the publication process for the **SBLP conference**.  
For more details, please refer to the paper.

### Dragon Book Compiler

A compiler written in **Go** while studying *Compilers: Principles, Techniques, and Tools*, also known as the *Dragon Book*.
