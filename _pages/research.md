---
permalink: /research/
title: ""
author_profile: false
---

<h2 style="font-size:18pt;line-height:1.5;margin-left: -50px;"> <span style="color: #cc0000;">Neuromorphic Computing with Light</span> </h2>

<div style="font-size:14pt;line-height:1.5;margin-left: -50px;">
    <div class="row">
        <div class="columntext">
            Recent advances in artificial intelligence (AI) has resulted in a resurgence of interest in developing photonic neural networks for efficient machine-learning computation. AI and photonic computing form a nice synergy since neural-network models, especially large ones, bring the best out of optical processors by stressing their strength in data transmission and reuse. Based on these physical properties, photonic neural networks represent a class of analog computing systems that have been experimentally shown to approach the physical limit of computation, using even single photons for each operation. Our interest in photonic neural networks is twofold:
            <ol> 
                <li> <u>Hardware</u>: We are interested in exploring a hardware solution that enables photonic neural networks to be both scalable and compact. </li>
                <li> <u>Software</u>: We are interested in using photonic neural networks as a testbed to study novel computing phenomena in the analog noisy regime. </li>
            </ol>
        </div>
        <div class="columnfig">
            <img src="../images/publications/2023_Laydevant.png" width="100%"/>
        </div>
    </div>
    Further reading:
    <ul>
        <li>P.L. McMahon. <a href="https://doi.org/10.1038/s42254-023-00645-5">The physics of optical computing.</a> <i>Nature Review Physics</i> (2023).</li>
        <li>T. Wang, <i>et al.</i> <a href="https://doi.org/10.1038/s41467-021-27774-8">An optical neural network using less than 1 photon per multiplication.</a> <i>Nature Communications</i> <b>13</b>, 123 (2022).</li>
        <li>S. Lloyd. <a href="https://doi.org/10.1038/35023282">Ultimate physical limits to computation.</a> <i>Nature</i> <b>406</b>, 1047–1054 (2000) | Wikipedia <a href="https://en.wikipedia.org/wiki/Limits_of_computation#:~:text=Seth%20Lloyd%20calculated%20the%20computational,it%20could%20compute%20at%20a">Limits of Computation</a></li>
    </ul>
</div><br clear="all" />

<h2 style="font-size:18pt;line-height:1.5;margin-left: -50px;"> <span style="color: #cc0000;">Computational Sensors based on Neuromorphism</span> </h2>

<div style="font-size:14pt;line-height:1.5;margin-left: -50px;">
    <div class="row">
        <div class="columntext">
            Another opportunity offered by photonic neuromorphic computing is its potential for making smarter and more effcient sensors. Unlike computational imaging, whose goal is to produce full-resolution images through computational reconstruction, the primary goal of image sensing is to capture salient features with a high precision and speed beyond traditional hardware. This performance is achieved by breaking the wall between traditional imaging, sensing, and computing modules and strategically offloading some computation to optics and sensors. This holistic approach allows us to train the entire machine-vision system in an end-to-end fashion for specific machine-vision tasks, allowing a synergy otherwise unattainable by optimizing individual parts for different objectives. Getting results without bookkeeping all the intermediate data is a neuromorphic design principle, which is ubiquitously adopted by biological organisms and autonomous systems to perform tasks in real time. We are interested in demonstrating the impact of this computational sensing scheme by using it to solve real-world problems in high-speed robotics and high-throughput biomedical assays.
        </div>
        <div class="columnfig">
            <img src="../images/research/onn_sensor.png" width="100%"/>
        </div>
    </div>
    Further reading:
    <ul>
        <li>G. Wetzstein, A. Ozcan, S. Gigan, <i>et al.</i> <a href="https://doi.org/10.1038/s41586-020-2973-6"> Inference in artificial intelligence with deep optics and photonics.</a> <i>Nature</i> <b>588</b>, 39–47 (2020).</li>
        <li>P. Sterling and S. Laughlin. <i>Principles of Neural Design</i> (MIT Press, 2015).</li>
        <li>T. Wang*, M.M. Sohoni*, L.G. Wright, <i>et al.</i> <a href="https://doi.org/10.1038/s41586-020-2973-6"> Image sensing with multilayer, nonlinear optical neural networks.</a> <i>Nature Photonics</i> <b>17</b>, 408 - 415 (2023).</li>
    </ul>
</div><br clear="all" />

<h2 style="font-size:18pt;line-height:1.5;margin-left: -50px;"> <span style="color: #cc0000;">Imaging and Sensing with Quantum Light</span> </h2>

<div style="font-size:14pt;line-height:1.5;margin-left: -50px;">
    <div class="row">
        <div class="columntext">
            Quantum and other non-classical states of light are enticing for imaging and sensing applications. This is because quantum resources, such as entanglement, allow us to engineer the collective behavior of multiple photons, enabling each photon to carry more information than its classical counterpart. This extra information translates to various forms of quantum sensing/imaging advantages, such as enhanced phase measurement precision or image resolution. However, many questions still remain: Can we engineer a state of light that can lead to scalable quantum sensing advantages, in presence of loss and background noise? How can we utilize quantum resources for an advantage in machine-learning tasks? In the context of optical imaging and sensing, we are interested in developing systems and computational methods to demonstrate practical quantum sensing advantages in real-world applications.
        </div>
        <div class="columnfig">
            <img src="../images/research/quantum_sensing.png" width="110%"/>
        </div>
    </div>
</div><br clear="all" />

<h2 style="font-size:18pt;line-height:1.5;margin-left: -50px;"> <span style="color: #cc0000;">Understanding Biological Neural Computation with Light</span> </h2>

<div style="font-size:14pt;line-height:1.5;margin-left: -50px;">
    <div class="row">
        <div class="columntext">
            Despite the advances in AI, the working principle of its source of inspiration &mdash; biological neural networks &mdash; is still not elucidated. The difficulty comes in twofolds, it is both challenging to measure and to analyze neural activity data. We are interested in helping with this endeavor in two ways:
            <ol> 
                <li> <u>Seeing through light scattering</u>: While optical imaging provides a minimally invasive means to measure the activities of biological neurons across a large population, imaging through turbid biological tissue is challenging due to the highly complex and dynamical nature of tissue-induced light scattering. We are interested in exploring new ways for instant light de-scattering through a mixture of physics and AI methods. When combined with state-of-the-art optical microscopy or spectroscopy, these methods will enable us to substantially push the depth of brain imaging. </li>
                <li> <u>Understanding neuronal activity data</u>: To test if the information in current large-scale neuronal recording datasets contains the information for decoding brain functions on the circuit level, we will explore state-of-the-art AI models for neuronal data analysis, with a focus on the predictive power of the model.</li>
            </ol>
        </div>
        <div class="columnfig">
            <img src="../images/publications/2023_Laydevant.png" width="100%"/>
        </div>
    </div>
</div><br clear="all" />


<h2 style="font-size:18pt;line-height:1.5;margin-left: -50px;"> <span style="color: #cc0000;">Artificial Intelligence for Photonic Research</span> </h2>

<div style="font-size:14pt;line-height:1.5;margin-left: -50px;">
    <div class="row">
        <div class="columntext">
            Recent advances in AI, including reinforcement learning, multimodal, few-shot learning, and large language models, will generate long-lasting impacts on how we conduct scientific research, from how experiments are desinged and performed to how the results are analyzed and circulated. In this regard, we are keen on exploring ways state-of-the-art AI models and tools can be leveraged for making experimental designs through reinforcement learning, improving instrumentation through adaptive training, and creating novel devices through inverse design.  
        </div>
        <div class="columnfig">
            <img src="../images/research/AI_4_science.png" width="100%"/>
        </div>
    </div>
    Further reading:
    <ul>
        <li>H. Wang, T. Fu, Y. Du, <i>et al.</i> <a href="https://doi.org/10.1038/s41586-023-06221-2">Scientific discovery in the age of artificial intelligence.</a> <i>Nature</i> <b>620</b>, 47–60 (2023).</li>
        <li>L.G. Wright*, T. Onodera, M.M. Stein, <i>et al.</i> <a href="https://doi.org/10.1038/s41586-021-04223-6">Deep physical neural networks trained with backpropagation.</a> <i>Nature</i> <b>601</b>, 549-555 (2022).</li>
    </ul>
</div><br clear="all" />


