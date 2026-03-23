<div align="center">

<p style="background: linear-gradient(135deg, #1e6501, #2d9e08); color: gold; font-size: 160%; font-weight: bold; text-align: center; border-radius: 20px 60px; border: 3px solid gold; padding: 25px 40px; letter-spacing: 2px; box-shadow: 0 4px 15px rgba(0,0,0,0.3);">
🌿 GreenNet: Lightweight Custom CNN for Sustainable AI
</p>

<h3>Benchmarking Against Established Models on MNIST & CIFAR-10</h3>

<table>
<tr>
<td align="center">
<img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/PyTorch-2.0+-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
</td>
<td align="left">
<img src="https://img.shields.io/badge/CUDA-Enabled-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA"/>
<img src="https://img.shields.io/badge/License-MIT-gold?style=for-the-badge" alt="License"/>
</td>
</tr>
</table>

</div>

---

## 👤 Author & Affiliation

<div align="center">

<table>
<tr><td align="center">👨‍💻 <strong>Author</strong></td><td>Abrar Hossain Zahin</td></tr>
<tr><td align="center">📧 <strong>Email</strong></td><td>abrarhossain1200@gmail.com</td></tr>
<tr><td align="center">🏛️ <strong>Institution</strong></td><td>Dept. of CSE, East West University, Dhaka, Bangladesh</td></tr>
<tr><td align="center">📄 <strong>Target Venue</strong></td><td>IEEE Conference on Green &amp; Sustainable Computing</td></tr>
<tr><td align="center">🗃️ <strong>Datasets</strong></td><td>
<a href="https://www.kaggle.com/datasets/hojjatk/mnist-dataset"><img src="https://img.shields.io/badge/Dataset-MNIST-blue?style=flat-square" alt="MNIST"/></a>
<a href="https://www.kaggle.com/datasets/pankrzysiu/cifar10-python"><img src="https://img.shields.io/badge/Dataset-CIFAR--10-orange?style=flat-square" alt="CIFAR-10"/></a>
</td></tr>
<tr><td align="center">🎓 <strong>Connect</strong></td><td>
<a href="https://www.linkedin.com/in/md-abrar-hossain-zahin-3160272a4/?originalSubdomain=bd"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://www.kaggle.com/mdabrarhossainzahin"><img src="https://img.shields.io/badge/Kaggle-Follow-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle"/></a>
<a href="https://www.researchgate.net/profile/Abrar-Zahin-7"><img src="https://img.shields.io/badge/ResearchGate-Follow-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white" alt="ResearchGate"/></a>
<a href="https://scholar.google.com/citations?user=PggflFIAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"/></a>
</td></tr>
</table>

</div>

---

## 🌍 Why This Matters

<div align="center">

<blockquote>
<em>Training a large AI model can emit CO₂ equivalent to <strong>five car lifetimes</strong> - Strubell et al., 2019</em>
</blockquote>

</div>

<table align="center">
<tr>
<td align="center" width="220">
<h2>121×</h2>
<b>Smaller than MobileNetV2</b><br>
<sub>0.076 MB vs 9.19 MB</sub>
</td>
<td align="center" width="220">
<h2>2.86×</h2>
<b>Less CO₂ on MNIST</b><br>
<sub>Real CodeCarbon measurement</sub>
</td>
<td align="center" width="220">
<h2>99.22%</h2>
<b>MNIST Accuracy</b><br>
<sub>Only 12,698 parameters</sub>
</td>
<td align="center" width="220">
<h2>85.27%</h2>
<b>CIFAR-10 with KD</b><br>
<sub>Sub-2MB model size</sub>
</td>
</tr>
</table>

---

## 🔑 Key Contributions

```
╔══════════════════════════════════════════════════════════════════════════════════════════════╗
║                                                                                              ║
║  1. 🏗️  GreenNet Architecture     : From-scratch DSC CNN with residual blocks =~ 12K params  ║
║                                                                                              ║
║  2. 🎓  Knowledge Distillation    : MobileNetV2 teacher → GreenNet student                   ║
║                                                                                              ║
║  3. 🌱  Green Score (Novel Metric): Acc / (CO₂ × Size × Latency)^(1/3) — formally defined    ║
║                                                                                              ║
║  4. ✂️  Progressive Pruning       : 10% → 60% sparsity sweep on all 4 architectures          ║
║                                                                                              ║
║  5. 📊  Comprehensive Benchmark   : 8 models × 10 metrics × 2 datasets = 160 data points     ║
║                                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════════════════════╝
```

---

<div align="center">

<!-- FIX 4: Markdown table inside <div> → converted to HTML table -->
<table>
<tr>
<td align="center">
<img src="https://img.shields.io/badge/CO₂%20Tracking-CodeCarbon-green?style=flat-square" alt="CO2"/>
</td>
<td>
<img src="https://img.shields.io/badge/Quantization-INT8%20Dynamic-red?style=flat-square" alt="Quantization"/>
</td>
</tr>
</table>

</div>

<!-- FIX 5: Removed the extra stray </div> that had no matching opening tag -->

<div align="center">

<p style="background: linear-gradient(135deg, #1e6501, #2d9e08); color: white; font-style: italic; font-size: 105%; text-align: center; border-radius: 12px; padding: 18px 30px; border-left: 5px solid gold;">
💡 "Green AI is best achieved by designing efficient architectures from the ground up, not by compressing large pretrained models."
</p>

<br>

<sub>© 2025 Abrar Hossain Zahin · East West University · IEEE Submission</sub>

</div>
