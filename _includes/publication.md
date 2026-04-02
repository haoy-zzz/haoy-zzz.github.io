
<!-- CSS 样式：默认未选中显示灰色，选中时为黑色 -->
<style>
  .publication-header span {
    cursor: pointer;
    color: gray;
  }
  .publication-header span.active {
    color: #494e52;
  }
</style>

<div id="publications">

<h2 class="publication-header">
  <span id="selectedHeader" class="active" onclick="filterPubs('selected')">📖 Selected Works</span> |
  <span id="fullHeader" onclick="filterPubs('full')">Full</span>
</h2>

<div class="paper-box-text" data-selected="true" markdown="1">
<strong><font color="#374798">ToRL: Scaling Tool-Integrated RL</font></strong>\\
Xuefeng Li\*, **Haoyang Zou\***, Pengfei Liu \\
<span style="font-size: 0.95em; color: #888888;">2025, Tech Report.</span> <br>
<a href="https://arxiv.org/abs/2503.23383" style="pdf"><span>Paper</span></a> / 
<a href="https://github.com/GAIR-NLP/ToRL" style="code"><span>Code</span></a> / 
<img src="images/huggingface_logo.svg" width=21em style="vertical-align: middle;"> 
<a href="https://huggingface.co/GAIR/ToRL-7B" style="pdf"><span>Models</span></a> /
<a href="https://github.com/GAIR-NLP/ToRL">
<img src="https://img.shields.io/github/stars/GAIR-NLP/ToRL?style=social" style="vertical-align: middle;"> \\
</a>
<span>An RL framework enabling LLMs to autonomously learn tool usage from base models.</span>
<br>
</div>

<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">Generative AI Act II: Test Time Scaling Drives Cognition Engineering</font></strong>\\
Shijie Xia, Yiwei Qin, Xuefeng Li, Yan Ma, Run-Ze Fan, Steffi Chern, **Haoyang Zou**, Fan Zhou, Xiangkun Hu, Jiahe Jin, Yanheng He, Yixin Ye, Yixiu Liu, Pengfei Liu \\
<span style="font-size: 0.95em; color: #888888;">2025, Preprint</span> <br>
<a href="https://arxiv.org/abs/2504.13828" style="pdf"><span>PDF</span></a> / 
<a href="https://github.com/GAIR-NLP/cognition-engineering" style="code"><span>Code</span></a> / 
<a href="https://github.com/GAIR-NLP/cognition-engineering">
<img src="https://img.shields.io/github/stars/GAIR-NLP/cognition-engineering?style=social" style="vertical-align: middle;"> \\
</a>
<span>A survey on Test Time Scaling.</span>
<br>
</div>

<div class="paper-box-text" data-selected="true" markdown="1">
<strong><font color="#374798">LIMR: Less is More for RL Scaling</font></strong>\\
Xuefeng Li\*, **Haoyang Zou\***, Pengfei Liu \\
<span style="font-size: 0.95em; color: #888888;">2025, Tech Report.</span> <br>
<a href="https://arxiv.org/abs/2502.11886" style="pdf"><span>Paper</span></a> / 
<a href="https://github.com/GAIR-NLP/LIMR" style="code"><span>Code</span></a> / 
<img src="images/huggingface_logo.svg" width=21em style="vertical-align: middle;"> 
<a href="https://huggingface.co/GAIR/LIMR" style="pdf"><span>Models</span></a> & 
<a href="https://huggingface.co/datasets/GAIR/LIMR" style="pdf"><span>Dataset</span></a> /
<a href="https://github.com/GAIR-NLP/LIMR">
<img src="https://img.shields.io/github/stars/GAIR-NLP/LIMR?style=social" style="vertical-align: middle;"> \\
</a>
<span>A data selection method achieving comparable RL performance with fewer strategically chosen samples.</span>
<br>
</div>

<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">O1 Replication Journey--Part 3: Inference-time Scaling for Medical Reasoning</font></strong>\\
Zhongzhen Huang\*, Gui Geng\*, Shengyi Hua\*, Zhen Huang\*, **Haoyang Zou\***, Shaoting Zhang, Pengfei Liu, Xiaofan Zhang \\
<span style="font-size: 0.95em; color: #888888;">2025, Tech Report.</span> <br>
<a href="https://arxiv.org/abs/2501.06458" style="pdf"><span>Paper</span></a> / 
<a href="https://github.com/SPIRAL-MED/Ophiuchus" style="code"><span>Code</span></a> / 
<img src="images/huggingface_logo.svg" width=21em style="vertical-align: middle;"> 
<a href="https://huggingface.co/datasets/SPIRAL-MED/o1-journey-Ophiuchus" style="pdf"><span>Dataset</span></a> /
<a href="https://github.com/SPIRAL-MED/Ophiuchus">
<img src="https://img.shields.io/github/stars/SPIRAL-MED/Ophiuchus?style=social" style="vertical-align: middle;"> \\
</a>
<span>An inference-time scaling approach for medical reasoning tasks.</span>
<br>
</div>

<div class="paper-box-text" data-selected="true" markdown="1">
<strong><font color="#374798">O1 Replication Journey -- Part 2: Surpassing O1-preview through Simple Distillation, Big Progress or Bitter Lesson?</font></strong>\\
Zhen Huang\*, **Haoyang Zou\***, Xuefeng Li\*, Yixiu Liu\*, Yuxiang Zheng\*, Ethan Chern\*, Shijie Xia\*, Yiwei Qin, Weizhe Yuan, Pengfei Liu \\
<span style="font-size: 0.95em; color: #888888;">2024, Tech Report.</span> <br>
<a href="https://arxiv.org/abs/2411.16489" style="pdf"><span>Paper</span></a> / 
<a href="https://github.com/GAIR-NLP/O1-Journey" style="code"><span>Code</span></a> / 
<a href="https://github.com/GAIR-NLP/O1-Journey">
<img src="https://img.shields.io/github/stars/GAIR-NLP/O1-Journey?style=social" style="vertical-align: middle;"> \\
</a>
<span>A distillation approach surpassing o1-preview performance.</span>
<br>
</div>


<div class="paper-box-text" data-selected="true" markdown="1">
<strong><font color="#374798">O1 Replication Journey: A Strategic Progress Report--Part 1</font></strong>\\
Yiwei Qin\*, Xuefeng Li\*, **Haoyang Zou\***, Yixiu Liu\*, Shijie Xia\*, Zhen Huang, Yixin Ye, Weizhe Yuan, Hector Liu, Yuanzhi Li, Pengfei Liu \\
<span style="font-size: 0.95em; color: #888888;">2024, Tech Report.</span> <br>
<a href="https://arxiv.org/abs/2410.18982" style="pdf"><span>Paper</span></a> / 
<a href="https://github.com/GAIR-NLP/O1-Journey" style="code"><span>Code</span></a> / 
<a href="https://github.com/GAIR-NLP/O1-Journey">
<img src="https://img.shields.io/github/stars/GAIR-NLP/O1-Journey?style=social" style="vertical-align: middle;"> \\
</a>
<span>An early O1 replication exploration documenting trial-and-error attempts.</span>
<br>
</div>

<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">PC Agent: While You Sleep, AI Works -- A Cognitive Journey into Digital World</font></strong>\\
Yanheng He\*, Jiahe Jin\*, Shijie Xia, Jiadi Su, Runze Fan, **Haoyang Zou**, Xiangkun Hu, Pengfei Liu \\
<span style="font-size: 0.95em; color: #888888;">2024, Tech Report.</span> <br>
<a href="https://arxiv.org/abs/2412.17589" style="pdf"><span>Paper</span></a> / 
<a href="https://github.com/GAIR-NLP/PC-Agent" style="code"><span>Code</span></a> / 
<img src="images/huggingface_logo.svg" width=21em style="vertical-align: middle;"> 
<a href="https://huggingface.co/henryhe0123/PC-Agent-E" style="pdf"><span>Models</span></a> & 
<a href="https://huggingface.co/datasets/henryhe0123/PC-Agent-E" style="pdf"><span>Dataset</span></a> /
<a href="https://github.com/GAIR-NLP/PC-Agent">
<img src="https://img.shields.io/github/stars/GAIR-NLP/PC-Agent?style=social" style="vertical-align: middle;"> \\
</a>
<span>A GUI agent learning from human cognitive processes to perform computer work.</span>
<br>
</div>

<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">OlympicArena: Benchmarking Multi-discipline Cognitive Reasoning for Superintelligent AI</font></strong>\\
Zhen Huang, Zengzhi Wang, Shijie Xia, Xuefeng Li, **Haoyang Zou**, Ruijie Xu, Run-Ze Fan, Lyumanshan Ye, Ethan Chern, Yixin Ye, Yikai Zhang, Yuqing Yang, Ting Wu, Binjie Wang, Shichao Sun, Yang Xiao, Yiyuan Li, Fan Zhou, Steffi Chern, Yiwei Qin, Yan Ma, Jiadi Su, Yixiu Liu, Yuxiang Zheng, Shaoting Zhang, Dahua Lin, Yu Qiao, Pengfei Liu \\
<span style="font-size: 0.95em; color: #888888;">2024, Neurips 2024 (DB track).</span> <br>
<a href="https://arxiv.org/abs/2406.12753" style="pdf"><span>PDF</span></a> /
<a href="https://github.com/GAIR-NLP/OlympicArena" style="code"><span>Code</span></a> /
<img src="images/huggingface_logo.svg" width=23em style="vertical-align: middle;"> 
<a href="https://huggingface.co/datasets/GAIR/OlympicArena" style="pdf"><span>Dataset</span></a> /
<a href="https://gair-nlp.github.io/OlympicArena/" style="pdf"><span>Project Page</span></a> /
<a href="https://github.com/GAIR-NLP/OlympicArena">
<img src="https://img.shields.io/github/stars/GAIR-NLP/OlympicArena?style=social" style="vertical-align: middle;"> \\
</a>
<span>A challenging multi-modal olympic competition benchmark for LLMs and LVMs.</span> 
<br>
</div>

<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">Reformatted Alignment</font></strong>\\
Run-Ze Fan, Xuefeng Li, **Haoyang Zou**, Junlong Li, Shwai He, Ethan Chern, Jiewen Hu, Pengfei Liu \\
<span style="font-size: 0.95em; color: #888888;">2024, Tech Report.</span> <br>
<a href="https://arxiv.org/abs/2402.12219" style="pdf"><span>Paper</span></a> / 
<a href="https://github.com/GAIR-NLP/ReAlign" style="code"><span>Code</span></a> / 
<img src="images/huggingface_logo.svg" width=21em style="vertical-align: middle;"> 
<a href="https://huggingface.co/datasets/GAIR/ReAlign-GSM8K" style="pdf"><span>Dataset</span></a> /
<a href="https://gair-nlp.github.io/ReAlign/" style="pdf"><span>Project Page</span></a> /
<a href="https://github.com/GAIR-NLP/ReAlign">
<img src="https://img.shields.io/github/stars/GAIR-NLP/ReAlign?style=social" style="vertical-align: middle;"> \\
</a>
<span>A data quality improvement method reformatting responses to improve LLM alignment.</span>
<br>
</div>

<div class="paper-box-text" data-selected="true" markdown="1">
<strong><font color="#374798">Generative ai for math: Abel</font></strong>\\
Ethan Chern\*, **Haoyang Zou\***, Xuefeng Li\*, Jiewen Hu\*, Kehua Feng, Junlong Li, Pengfei Liu \\
<span style="font-size: 0.95em; color: #888888;">2024, Project.</span> <br>
<a href="https://gair-nlp.github.io/abel/" style="pdf"><span>Project Page</span></a> / 
<a href="https://github.com/GAIR-NLP/abel" style="code"><span>Code</span></a> / 
<img src="images/huggingface_logo.svg" width=21em style="vertical-align: middle;"> 
<a href="https://huggingface.co/GAIR/Abel-7B-002" style="pdf"><span>Models</span></a> /
<a href="https://github.com/GAIR-NLP/abel">
<img src="https://img.shields.io/github/stars/GAIR-NLP/abel?style=social" style="vertical-align: middle;"> \\
</a>
<span>A mathematical reasoning model achieving then SOTA performance on GSM8K and MATH benchmarks.</span>
<br>
</div>


</div>

<script>
function filterPubs(filterType) {
  var pubs = document.getElementById('publications').children;
  for (var i = 0; i < pubs.length; i++) {
    var selectedAttr = pubs[i].getAttribute('data-selected');
    if (selectedAttr !== null) { 
      if (filterType === 'selected') {
        pubs[i].style.display = (selectedAttr === 'true') ? '' : 'none';
      } else {
        pubs[i].style.display = '';
      }
    }
  }
  if (filterType === 'selected') {
    document.getElementById('selectedHeader').classList.add('active');
    document.getElementById('fullHeader').classList.remove('active');
  } else {
    document.getElementById('fullHeader').classList.add('active');
    document.getElementById('selectedHeader').classList.remove('active');
  }
}
document.addEventListener('DOMContentLoaded', function() {
  filterPubs('selected');
});
</script>