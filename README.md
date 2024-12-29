<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Research Paper - Inductive Biases in GNNs</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #007ACC;
            --text-color: #333;
            --background-color: #f8f9fa;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem;
            background-color: var(--background-color);
        }

        .container {
            background-color: white;
            padding: 3rem;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        h1 {
            color: var(--primary-color);
            font-size: 2.2rem;
            margin-bottom: 1.5rem;
            line-height: 1.3;
            border-bottom: 3px solid var(--secondary-color);
            padding-bottom: 0.5rem;
        }

        .abstract {
            background-color: #f8f9fa;
            padding: 2rem;
            border-radius: 8px;
            margin: 2rem 0;
            border-left: 4px solid var(--secondary-color);
        }

        .abstract h2 {
            color: var(--primary-color);
            margin-top: 0;
            font-size: 1.5rem;
        }

        .abstract p {
            margin-bottom: 0;
            text-align: justify;
        }

        .resources {
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
            margin-top: 2rem;
        }

        .resource-link {
            display: inline-flex;
            align-items: center;
            padding: 0.75rem 1.5rem;
            background-color: var(--secondary-color);
            color: white;
            text-decoration: none;
            border-radius: 6px;
            font-weight: 500;
            transition: transform 0.2s, background-color 0.2s;
        }

        .resource-link:hover {
            background-color: #005fa3;
            transform: translateY(-2px);
        }

        @media (max-width: 768px) {
            body {
                padding: 1rem;
            }
            
            .container {
                padding: 1.5rem;
            }

            h1 {
                font-size: 1.8rem;
            }

            .abstract {
                padding: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Different Inductive Biases Can Lead to Similar Performance via Distinct Algorithms</h1>
        
        <div class="abstract">
            <h2>Abstract</h2>
            <p>
                Graph Neural Networks (GNNs) have emerged as a useful class of neural networks with specific inductive biases that make them well-suited for processing graph-structured datasets. Despite the remarkable success of GNNs in several domains, the algorithms they learn from data are not well understood. Leveraging the mathematical equivalence between message passing in GNNs and variations of transformer attention, we investigate the information flow patterns inside networks with different inductive biases.
            </p>
            <p>
                We develop a simple framework to combine the attention in multi-head and multi-layer models in a way that reflects the information flow within the network. In our experiments with 4 architectures across 7 node classification tasks, we (i) analyze the relationship between learned information flow patterns and the underlying graph structure and (ii) compare the information flow patterns learned by different GNN architectures.
            </p>
            <p>
                Firstly, we find that, in general, when the architecture does not impose the graph structure, the information flow patterns within the network do not reflect the graph structure. Secondly, we observe that on small heterophilous graphs, such as Texas, different GNN architectures achieve similar performance, yet a closer look at their information flow patterns suggests that they do so by implementing different algorithms. This observation raises a critical question: How can we determine which of these algorithms is correct? Consequently, it underscores the necessity for more comprehensive and holistic evaluations that go beyond performance comparisons.
            </p>
        </div>

        <div class="resources">
            <a href="#" class="resource-link">📄 Paper</a>
            <a href="https://drive.google.com/drive/folders/1rCwxa3mjwZ9m24sl7gttgiJ-dzUZoNt1?usp=sharing" class="resource-link">📁 Drive Folder</a>
            <a href="https://github.com/batu-el/understanding-inductive-biases-of-gnns/blob/main/presentation.pdf" class="resource-link">🎯 Presentation</a>
            <a href="https://www.cl.cam.ac.uk/teaching/2324/L65/" class="resource-link">🎓 Course Page</a>
        </div>
    </div>
</body>
</html>
