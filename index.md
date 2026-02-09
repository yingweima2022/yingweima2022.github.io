---
layout: default
---

# About Me

Yingwei Ma (马迎伟) is a Member of Technical Staff on the RL team @ Moonshot AI. His research lies at the intersection of foundation model and software engineering. He had planned to pursue his PhD at HKUST under the supervision of Prof. [S.C. CHEUNG](https://www.cse.ust.hk/~scc/), but decided to postpone this plan as he got AGI-pilled. Currently, he focuses on using agent techniques (or Agentic LLM) to solve end-to-end SE/Research problems. 

# News
<ul id="news-list">
  <li><b>[<font color="#FF0000">2026.01</font>]</b> Introducing <b>Kimi-K2.5</b>: It seamlessly integrates vision and language understanding with advanced agentic capabilities, instant and thinking modes, as well as conversational and agentic paradigms. <a href="https://www.kimi.com/blog/kimi-k2-5.html">[Github]</a> <a href="https://huggingface.co/moonshotai/Kimi-K2.5">[Huggingface]</a></li>

  <li><b>[<font color="#FF0000">2025.11</font>]</b> Two papers have been accepted by AAAI'26.</li>

  <li><b>[<font color="#FF0000">2025.11</font>]</b> Introducing <b>Kimi-K2-Thinking</b>: Kimi K2 Thinking is the latest, most capable version of open-source thinking model. Starting with Kimi K2, we built it as a thinking agent that reasons step-by-step while dynamically invoking tools. <a href="https://moonshotai.github.io/Kimi-K2/thinking.html">[Github]</a> <a href="https://huggingface.co/moonshotai/Kimi-K2-Thinking">[Huggingface]</a></li>

  <li><b>[<font color="#FF0000">2025.09</font>]</b> One paper has been accepted by ASE'25.</li>

  <li><b>[<font color="#FF0000">2025.09</font>]</b> Introducing <b>Kimi-K2-0905</b>: Kimi K2-Instruct-0905 demonstrates significant improvements in performance on public benchmarks and real-world coding agent tasks. <a href="https://github.com/MoonshotAI/Kimi-K2">[Github]</a> <a href="https://huggingface.co/moonshotai/Kimi-K2-Instruct-0905">[Huggingface]</a></li>

  <li><b>[<font color="#FF0000">2025.08</font>]</b> Two papers have been accepted by EMNLP'25 Findings.</li>

  <li><b>[<font color="#FF0000">2025.07</font>]</b> Introducing <b>Kimi-K2</b>: A Open-source LLM for Agentic Intelligence. <a href="https://github.com/MoonshotAI/Kimi-K2">[Github]</a> <a href="https://huggingface.co/moonshotai">[Huggingface]</a> <a href="https://arxiv.org/pdf/2507.20534">[Paper]</a></li>

  <li><b>[<font color="#FF0000">2025.06</font>]</b> Introducing <b>Kimi-Dev</b>: A Strong and Open-source Coding LLM for Issue Resolution. <a href="https://github.com/MoonshotAI/Kimi-Dev?tab=readme-ov-file">[Github]</a> <a href="https://huggingface.co/moonshotai/Kimi-Dev-72B">[Huggingface]</a></li>

  <li><b>[<font color="#FF0000">2025.06</font>]</b> I won the <b><font color="#FF0000">ACM SIGSOFT Distinguished Paper Award</font></b>.</li>

  <li><b>[<font color="#FF0000">2025.03</font>]</b> One patent on code processing method has been published.</li>

  <li><b>[<font color="#FF0000">2025.03</font>]</b> <b>Alibaba LingmaAgent</b> has been accepted by FSE'25.</li>

  <li><b>[<font color="#FF0000">2025.01</font>]</b> One paper has been accepted by ICLR'25.</li>

  <li><b>[<font color="#FF0000">2025.01</font>]</b> Two patents on code processing and intelligent software development methods have been published.</li>

  <li><b>[<font color="#FF0000">2024.12</font>]</b> One paper has been accepted by ISSTA'25.</li>

  <li><b>[<font color="#FF0000">2024.09</font>]</b> One paper has been accepted by NeurIPS'24.</li>

  <li><b>[<font color="#FF0000">2024.06</font>]</b> Alibaba Lingma Agent obtained SOTA on SWE-Bench Lite.</li>

  <li><b>[<font color="#FF0000">2024.01</font>]</b> One paper has been accepted by ICLR'24 <b><font color="#FF0000">(Spotlight, top 5%)</font></b>.</li>

  <li><b>[<font color="#FF0000">2023.05</font>]</b> One paper has been accepted by Internetware'23.</li>

  <li><b>[<font color="#FF0000">2023.03</font>]</b> I won the <b><font color="#FF0000">IEEE TCSE Distinguished Paper Award</font></b>.</li>

  <li><b>[<font color="#FF0000">2023.03</font>]</b> Two papers have been accepted by SANER'23.</li>

  <li><b>[<font color="#FF0000">2022.09</font>]</b> I won the Outstanding Students of the School of Computer Science, National University of Defense Technology.</li>
</ul>

<script>
(() => {
  const MAX = 10;
  const list = document.querySelector('#news-list');
  if (!list) return;

  const items = Array.from(list.children).filter(el => el.tagName === 'LI');
  if (items.length <= MAX) return;

  const details = document.createElement('details');
  details.style.marginTop = '0.5rem';

  const summary = document.createElement('summary');
  summary.textContent = `Show ${items.length - MAX} older news`;
  summary.style.cursor = 'pointer';
  details.appendChild(summary);

  const folded = document.createElement('ul');
  items.slice(MAX).forEach(li => folded.appendChild(li));
  details.appendChild(folded);

  list.insertAdjacentElement('afterend', details);
})();
</script>



# Publication

### Preprints:

- **[<font color="#0000FF">arxiv'26</font>]** Jiaran Zhang, Luck Ma, Yanhao Li, Fanqi Wan, Di Qi, Xu Zhao, Jieyi Hou, Zhe Xie, Mengqiang Ren, Xin Wu, Zhewei Huang, Liangyu Chen, **Yingwei Ma**, Qi Han, Xiangyu Zhang, DOCKSMITH: Scaling Reliable Coding Environments
via an Agentic Docker Builder. arXiv preprint arXiv:2602.00592. [[paper](https://arxiv.org/pdf/2602.00592)] [[dataset](https://huggingface.co/collections/8sj7df9k8m5x8/docksmith)]

- **[<font color="#0000FF">arxiv'25</font>]** Kelin Fu, Tianyu Liu, Zeyu Shang, **Yingwei Ma**, Jian Yang, Jiaheng Liu, Kaigui Bian, Multi-Docker-Eval: A 'Shovel of the Gold Rush' Benchmark on
Automatic Environment Building for Software Engineering. arXiv preprint arXiv:2512.06915v2. [[paper](https://arxiv.org/abs/2512.06915v2)] [[benchmark](https://huggingface.co/datasets/litble/Multi-Docker-Eval)]

- **[<font color="#0000FF">arxiv'25</font>]** Yihong Dong, Xue Jiang, Yongding Tao, Huanyu Liu, Kechi Zhang, Lili Mou, Rongyu Cao, **Yingwei Ma**, Jue Chen, Binhua Li, Zhi Jin, Fei Huang, Yongbin Li, Ge Li, RL-PLUS: Countering Capability Boundary Collapse of LLMs in Reinforcement Learning. arXiv preprint arXiv:2508.00222. [[paper](https://arxiv.org/abs/2508.00222)]

- **[<font color="#0000FF">arxiv'24</font>]** Yalan Lin, **Yingwei Ma**, Rongyu Cao, Binhua Li, Fei Huang, Xiaodong Gu, Yongbin Li, LLMs as Continuous Learners: Improving the Reproduction of Defective Code in Software Issues. arXiv preprint arXiv:2411.13941. [[paper](https://arxiv.org/pdf/2411.13941)]

- **[<font color="#0000FF">arxiv'24</font>]** Zhenyu Pan, Rongyu Cao, Yongchang Cao, **Yingwei Ma**, Binhua Li, Fei Huang, Han Liu, Yongbin Li, Codev-Bench: How Do LLMs Understand Developer-Centric Code Completion?. arXiv preprint arXiv:2410.01353. [[paper](https://arxiv.org/pdf/2410.01353)]


### Peer-Reviewed And Technical Report: 

- **[<font color="#0000FF">Technical Report</font>]** **Yingwei Ma (Co-author)**, I did my best to enhance K2.5’s agentic capabilities across SWE, terminal usage, research scenarios, and security, **Kimi K2.5: Visual Agentic Intelligence**. arXiv preprint arXiv:2602.02276. [[paper](https://arxiv.org/pdf/2602.02276)]

- **[<font color="#0000FF">Technical Report</font>]** **Yingwei Ma (Co-author)**, contributed to Coding Agentic Capabilities for Kimi K2, **Kimi K2: Open Agentic Intelligence**. arXiv preprint arXiv:2507.20534. [[paper](https://arxiv.org/pdf/2507.20534)]

- **[<font color="#0000FF">Technical Report</font>]** **Yingwei Ma (Co-author)**, introducing Kimi-Dev:
A Strong and Open-source Coding LLM for Issue Resolution, **Kimi-Dev: Agentless Training as Skill Prior for SWE-Agents**. arXiv preprint arXiv:2509.23045. [[paper](https://arxiv.org/abs/2509.23045)]


- **[<font color="#0000FF">ASE'25</font>]** **Yingwei Ma**, Binhua Li, Yihong Dong, Xue Jiang, Rongyu Cao, Fei Huang, Yongbin Li, Thinking Longer, Not Larger: Enhancing Software Engineering Agents via Scaling Test-Time Compute. arXiv preprint arXiv:2503.23803. ASE'25, CCF-A. Accepted as an Industry Full Paper. [[paper](https://arxiv.org/abs/2503.23803)]

- **[<font color="#0000FF">ISSTA'25</font> 🏆]** **Yingwei Ma**, Rongyu Cao, Yongchang Cao, Yue Zhang, Jue Chen, Yibo Liu, Yuchen Liu, Binhua Li, Fei Huang, Yongbin Li, Lingma SWE-GPT: An Open Development-Process-Centric Language Model for Automated Software Improvement. The ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA'25), CCF-A. (**<font color="#FF0000">ACM SIGSOFT Distinguished Paper Award</font>, The Best Paper Award at The Conference**) [[paper](https://arxiv.org/pdf/2411.00622)] [[link](https://mp.weixin.qq.com/s/Qq2pb2PaHGwoDT50Rs4_bw)]

- **[<font color="#0000FF">FSE'25</font>]** **Yingwei Ma**, Qingping Yang, Rongyu Cao, Binhua Li, Fei Huang, Yongbin Li, **Alibaba LingmaAgent**: Improving Automated Issue Resolution via Comprehensive Repository Exploration. arXiv preprint arXiv:2406.01422. FSE'25, CCF-A. Accepted as an Industry Full Paper. [[paper](https://arxiv.org/pdf/2406.01422)]

- **[<font color="#0000FF">ICLR'24</font>]** **Yingwei Ma**, Yue Liu, Yue Yu, Yuanliang Zhang, Yu Jiang, Changjian Wang, Shanshan Li, At Which Training Stage Does Code Data Help LLMs Reasoning?. The 12th International Conference on Learning Representations (ICLR-24)
, Vienna Austria, May 7th-11th, 2024. (**<font color="#FF0000">Spotlight, Top 5%</font>**) [[paper](https://arxiv.org/pdf/2309.16298)]

- **[<font color="#0000FF">SANER'23</font> 🏆]** **Yingwei Ma**, Yue Yu, Shanshan Li, Zhouyang Jia, Jun Ma, Rulin Xu, Wei Dong and Xiangke Liao, *MulCS: Towards a Unified Code Representation for Multilingual Code Search*. 30th IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER), Macao SAR, China, March 21st-24th, 2023.(**<font color="#FF0000">IEEE TCSE Distinguished Paper Award</font>, The Best Paper Award at The Conference**) [[paper](https://yuyue.github.io/res/paper/MulCS-saner2023.pdf)]

- **[<font color="#0000FF">AAAI'26</font>]** Zhenhao Zhu, Yue Liu, **Yingwei Ma**, Hongcheng Gao, Nuo Chen, Yanpei Guo, Wenjie Qu, Huiying Xu, Xinzhong Zhu, Jiaheng Zhang, ExtendAttack: Attacking Servers of LRMs via Extending Reasoning. The 40th Annual AAAI Conference on Artificial Intelligence (AAAI-26) [[paper](https://arxiv.org/abs/2506.13737)]

- **[<font color="#0000FF">AAAI'26</font>]** Xue Jiang, Yihong Dong, Zheng Fang, **Yingwei Ma**, Tangxinyu Wang, Rongyu Cao, Binhua Li, Zhi Jin, Wenpin Jiao, Yongbin Li, Ge Li, Large Language Model Unlearning for Source Code. The 40th Annual AAAI Conference on Artificial Intelligence (AAAI-26) [[paper](https://www.arxiv.org/abs/2506.17125)]

- **[<font color="#0000FF">ICLR'25</font>]** Jie Cheng, Ruixi Qiao, **Yingwei Ma**, Gang Xiong, Qinghai Miao, Binhua Li, Yongbin Li, Yisheng Lv, Scaling Offline Model-Based RL via Jointly-Optimized World-Action Model Pretraining. The Thirteenth International Conference on Learning Representations (ICLR-25) [[paper](https://arxiv.org/pdf/2410.00564?)]

- **[<font color="#0000FF">ICML'25</font>]** Yue Liu, Xiaoxin He,  Miao Xiong, **Yingwei Ma**, Jiaheng Zhang, Bryan Hooi, FLIPATTACK: JAILBREAK LLMS VIA FLIPPING. (ICML-25) [[paper](https://openreview.net/pdf?id=H7xIfLDIoA)]

- **[<font color="#0000FF">EMNLP'25 Findings</font>]** Bo Yang, Qingping Yang, **Yingwei Ma**, Runtao Liu, UTMath: Math Evaluation with Unit Test via Reasoning-to-Coding Thoughts. arXiv preprint arXiv:2411.07240. [[paper](https://arxiv.org/pdf/2411.07240)]

- **[<font color="#0000FF">NeurIPS'24</font>]** Yue Liu, Shihao Zhu, Jun Xia, **Yingwei Ma**, Jian Ma, Wenliang Zhong, Xinwang Liu, Guannan Zhang, Kejun Zhang, End-to-end learnable clustering for intent learning in recommendation. The 38th Annual Conference on Neural Information Processing Systems (NeurIPS-24) [[paper](https://arxiv.org/pdf/2401.05975)]


# Patents
- [2025] Yingwei Ma. 异常数据复现方法以及异常代码复现方法 (Abnormal data reproduction method and abnormal code reproduction method). Patent Application No. CN119166410B, Alibaba (China) Co., Ltd. (Application Date: 2025.02.14, Publication Date: 2025.02.14)
- [2024] Yingwei Ma. 代码处理方法以及代码修复测试方法 (Code Processing Method and Code Repair Testing Method). Patent Application No. CN118760612A, Alibaba (China) Co., Ltd. (Application Date: 2024.09.04, Publication Date: 2024.10.11)
- [2024] Yingwei Ma. 代码处理模型训练、代码任务处理以及代码开发方法 (Code Processing Model Training, Code Task Processing and Code Development Method). Patent Application No. CN118860900A, Alibaba (China) Co., Ltd. (Application Date: 2024.09.19, Publication Date: 2024.10.29)

# Experience

- **[2025.05-]**

  Technical Staff in <a href="https://www.moonshot.ai/">RL team</a> ![GitHub](/assets/img/moonshot.jpeg){:width="20"}, Moonshot AI. 


- **[2024.02-2025.05]** 

  Researcher in <a href="https://www.tongyi.com/">TONGYI Lab</a> ![GitHub](/assets/img/tongyi.jpg){:width="20"}, Alibaba Cloud. 

# Education

- **[2021.9-2023.12]** 

  M.E. in <a href="https://english.nudt.edu.cn/">National University of Defense Technology (NUDT)</a>. 

  Supervisor: Prof. Liao, Xiangke and Shanshan Li

  National Scholarship (国家奖学金).


- **[2017.9-2021.6]** 

  B.E. in <a href="http://english.ysu.edu.cn/">Yanshan University(YSU) at Qinhuangdao, Hebei Province</a>.

  Supervisor: Prof. Fengda Zhao

  National Scholarship (国家奖学金).

- **[2014.9-2017.6]** 

  High school in <a href="https://baike.baidu.com/item/%E6%B2%B3%E5%8C%97%E6%B6%BF%E5%B7%9E%E4%B8%AD%E5%AD%A6/5507970">Zhuozhou Middle School, Hebei Province</a>.

  Provincial First Prize in the Mathematics Olympiad (数学奥林匹克竞赛省一等奖).

# Academic Service
- Program committee for AAAI'25
- Program committee for EXPRESS@ISSTA'25
- Reviewer for ICML'25, ICLR'25, NeurIPS'25
- Reviewer for NeurIPS'24, ICLR'24
- Reviewer for EMNLP'23
