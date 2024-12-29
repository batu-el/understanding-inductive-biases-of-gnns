## Different Inductive Biases Can Lead to Similar Performance via Distinct Algorithms
**Abstract:** Graph Neural Networks (GNNs) have emerged as a useful class of neural networks with specific inductive biases that make them well-suited for processing graph-structured datasets. Despite the remarkable success of GNNs in several domains, the algorithms they learn from data are not well understood. Leveraging the mathematical equivalence between message passing in GNNs and variations of transformer attention, we investigate the information flow patterns inside networks with different inductive biases. We develop a simple framework to combine the attention in multi-head and multi-layer models in a way that reflects the information flow within the network. In our experiments with 4 architectures across 7 node classification tasks, we (i) analyze the relationship between learned information flow patterns and the underlying graph structure and (ii) compare the information flow patterns learned by different GNN architectures. Firstly, we find that, in general, when the architecture does not impose the graph structure, the information flow patterns within the network do not reflect the graph structure. Secondly, we observe that on small heterophilous graphs, such as Texas, different GNN architectures achieve similar performance, yet a closer look at their information flow patterns suggests that they do so by implementing different algorithms. This observation raises a critical question: How can we determine which of these algorithms is correct? Consequently, it underscores the necessity for more comprehensive and holistic evaluations that go beyond performance comparisons. 

<a href="#" class="button">Paper</a> 
<a href="https://drive.google.com/drive/folders/1rCwxa3mjwZ9m24sl7gttgiJ-dzUZoNt1?usp=sharing" class="button">Drive Folder</a>




 Link to Paper: <br>
 Link to Drive Folder: https://drive.google.com/drive/folders/1rCwxa3mjwZ9m24sl7gttgiJ-dzUZoNt1?usp=sharing <br>
 Link to Presentation: https://github.com/batu-el/understanding-inductive-biases-of-gnns/blob/main/presentation.pdf <br>
 Course Page:  https://www.cl.cam.ac.uk/teaching/2324/L65/ <br>


