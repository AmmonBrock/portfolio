# Data Scientist

### Education

**Brigham Young University**
- Computer Science, MS (4.00)
- Applied and Computational Mathematics, BS (3.99 - Covaledictorian)

### Work Experience

**Quant @ Union Capital Partners**
- Trained and deployed a random forest stock selector used for managing $100,000 of the fund
- Scraped, downloaded, and stored millions of rows of market data in a MySQL database for efficient retrieval
- Developed a market state classification system used for reducing volatility of trading strategies

**Data Science Intern @ Zions Bancorporation**
- Created and deployed a human-in-in-the-loop for labeling text data with AI assistance
- Fine-tuned a transformer to classify bank transaction data into 13 categories with over 80% accuracy
- Utilized Named Entity Recognition tools to reduced unlabeled pool of transaction data by 90%

**Research Assistant @ BYU: Counseling and Psychological Services**
- Optimized patient-therapist matching by developing predictive models of improvement scores
- Used automated machine learning to find a model that improved prediction accuracy by 10%
- Performed data cleaning, model selection, and model validation on data for over 20,000 entries

## Featured Projects

### Custom CLIP Training and Application: Semantic Image Sorting

I trained a custom CLIP (Contrastive Language-Image Pre-training) model on 1.2 million image-caption pairs, achieving performance that exceeds the original CLIP model on multiple benchmarks. The model learns joint embeddings of images and text, enabling powerful semantic understanding and comparison. I also created novel evaluation metrics and applications of the model as detailed in the [technical report](custom_clip_report.pdf).

**Key Achievements**
- Successful training of a large scale (1.2 million training examples) multi-modal model
- Developed a novel application of the trained model (using a difference vector from 2 captions to sort a dataset of images)
- Unique evaluation metric that measures the accuracy of the projections onto the semantically defined lines

#### Example Applications
Zero-shot sorting of facial images from "a very young baby" to "an extremely old man"
![Age Sorting](images/AgeRanking.png)
See the [technical report](custom_clip_report.pdf) for detailed information about how we used ground truth ages on a large dataset of faces to measure its accuracy on this task.

Zero-shot sorting of pictures of myself from "a very ugly man" to "an extremely attractive man"
![Attractiveness Sorting](images/ugly_to_attractive.png)

Zero-shot sorting of pictures of myself from "a man that is bored" to "a man having fun"
![Bored to Fun](images/bored_to_fun.png)

Check out the code yourself! [Custom Clip Code](https://github.com/AmmonBrock/custom-clip.git)


### Parapal: An LLM-Based Grading Assistant for Teachers

I worked with 2 classmates to create a website that automatically grades student essays according to specified rubrics and common core standards. We built it to autoscale on AWS so it could handle real-world usage demands. Out of respect for co-founders who intend to pursue this project as a business endeavor, I do not include the code. However, I do include a short demo video of the website. Check it out!



<div align="center">

  <iframe width="560" height="315" src="https://www.youtube.com/embed/1aKSF8OVZsM" frameborder="0" allowfullscreen></iframe>

</div>



**Key Achievements**

- Deployment of an LLM-based website using the following tools on AWS: S3, CloudFront, Cognito, API Gateway, Lambda, and Bedrock

- Rigorous parsing and validation of LLM responses to ensure correct format

- Cost estimations of deployment architecture and design of a feasible business plan
