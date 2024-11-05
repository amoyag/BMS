## Attention is all you need. From Deep Learning to Protein Language Models

### Reinforcement learning

- **Goal-Oriented Learning**: An agent learns by trial and error in an environment to maximize rewards.

- **Rewards for Actions**: The agent receives feedback in the form of rewards, which guide its actions.

- **Balance of Exploration and Exploitation**: The agent must explore new actions to learn while also exploiting known actions that yield rewards.

- **Learning Methods**: Techniques like Q-learning help the agent optimize decisions over time.

#### Biochemistry example
Optimize enzyme activity in a simulated biochemical pathway. The agent tries different concentrations of substrates or inhibitors, receiving rewards based on the enzyme’s activity. Over time, it learns which conditions maximize activity, like an experimental setup that adapts based on feedback from each trial. This approach could help simulate optimal conditions for biochemical reactions.

### Transformer model
A model architecture designed to process sequences, like language or genetic sequences, by focusing on relationships between elements within the sequence, without needing to process them in a fixed order. This model was introduced in the groundbreaking paper "Attention Is All You Need" by Vaswani *et al.* in 2017, which fundamentally changed the approach to handling sequential data.

Uses self-attention to let each part of a sequence (like words in a sentence or amino acids in a protein) focus on other parts, capturing long-range relationships efficiently. It processes data all at once, not in a strict order, making it faster than earlier models.

#### Biochemistry example: Protein folding. 
Given a sequence of amino acids, the Transformer model can analyze the relationships between distant amino acids to predict how they interact and fold into a 3D structure. 

### The Shift from Supervised to Unsupervised Learning
- **Supervised Learning**:
	- Requires labeled data, which can be costly and scarce, especially in biochemistry.
  
- **Unsupervised Learning**:
	- Learns from unlabeled data by identifying patterns.
	- Similar to exploratory research, observing without predefined labels to uncover insights.

- **Transformers and Pretraining**:
	- Can be pretrained on large, unlabeled datasets to understand data structures.
	- Fine-tuning is then applied for specific tasks, enabling novel content generation without extensive labeled data.

## Language of Life: AI and the Next Generation of Protein Design
### From Physics to Proteins: The Nobel Prizes and AI's Impact on Protein Study

AI enables computational approaches, speeding up discoveries in protein structure and design.

- **2024 Nobel Prize in Physics**:
	- Awarded to **John Hopfield and Geoffrey Hinton** for foundational work on artificial neural networks.
	- Hopfield’s 1982 model for associative memory linked neural networks to spin models in physics, essential groundwork for modern AI.
	- Their research led to algorithms that mimic human brain learning, forming the basis of today’s AI tools.

- **2024 Nobel Prize in Chemistry**:
	- Awarded to **David Baker, Demis Hassabis, and John Jumper** for advances in computational protein design and structure prediction.
	- **David Baker’s Contributions**:
		- Developed **Rosetta software** for protein design, originally for stable structures, now also for purpose-specific proteins.
		- Showed potential for AI in creating new enzymes, combining **computational design and directed evolution** (boosted by Frances Arnold’s 2018 Nobel work).
	
	- **Demis Hassabis and John Jumper’s Contributions (AlphaFold)**:
		- Created **AlphaFold**, an AI tool predicting protein structures with high accuracy, outperforming other methods.
		- AlphaFold’s predictions now form databases with millions of protein structures, aiding research in protein function, drug discovery, and biotechnology.

### Demystifying Protein Language Models
PLMs treat protein sequences as a “language,” where each amino acid is a "letter" and the sequence determines the protein’s structure and function, similar to sentence structure in language.

- **How PLMs Work**:
	- PLMs use transformer neural networks and attention mechanisms to identify relationships between amino acids.
	- They learn from vast datasets of protein sequences, creating “embeddings” that represent each amino acid in a way that groups similar properties together.

- **Applications of PLMs**:
	- **Predicting Protein Structure**: PLMs can predict 3D structures from sequences, aiding discoveries in protein functions and drug design (e.g., AlphaFold).
	- **Predicting Protein Function**: By analyzing sequence patterns, PLMs can infer the roles of proteins, even those not yet fully studied.
	- **Protein Evolution and Variants**: PLMs assess the impact of mutations on protein function and stability, helping trace evolutionary adaptations.
	- **Post-Translational Modifications**: They predict PTMs (e.g., phosphorylation), aiding in understanding regulatory mechanisms.

- **Innovations in Protein Design**:
	- **De Novo Design**: PLMs generate entirely new protein sequences, enabling designs with specific structures and functions not found in nature.
	- **Functional Motif Scaffolding**: They create proteins around specific functional motifs, like binding sites, for targeted activities.
	- **Integration with Traditional Tools**: Combining PLMs with tools like Rosetta enhances the accuracy of protein engineering.

## A New Era for Biochemistry

- AI and biochemistry are merging, reshaping the field and accelerating discoveries in protein science, engineering, and therapeutics.
- This fusion offers biochemists new tools to tackle complex biological systems and create innovative solutions for health and medicine.

- **The Role of AI in Protein Science**:
	- AI, especially **Protein Language Models (PLMs)** and deep learning, enables rapid, accurate predictions of protein structures and designs new enzymes.
	- Models like **AlphaFold** have revolutionized protein folding studies, advancing drug discovery and therapeutic development.

- **Creative Protein Design with AI**
	- AI enables **de novo protein design**, allowing the creation of entirely new proteins tailored for specific functions, like neutralizing toxins or catalyzing unique reactions.
	- Techniques like **functional motif scaffolding** and **direct sequence design** help build proteins with targeted features, benefiting medicine, environmental science, and industry.

- **Opportunities for Aspiring Biochemists**:
	- This is a prime time for contributions in biochemistry, where AI skills like coding and machine learning enhance research abilities.
	- Exploring AI and computational tools prepares you to address big questions in biology, sustainability, and health.



