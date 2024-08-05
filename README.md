# Academic-project
The Pan-Cancer project is a collaborative effort to understand the common and unique
features of different types of cancer. It uses data from the Cancer Genome Atlas (TCGA), which
is a large collection of human tumor samples that have been analyzed at multiple levels of
molecular detail. By comparing the genomic, transcriptomic, proteomic and epigenetic changes
across 12 cancer types, the project aims to identify new ways of classifying and treating tumors
based on their molecular profile.
The data obtained from the UCI Machine Learning Repository has been sampled so that
there is enough data for us to train models. The exploratory data analysis is conducted on the
sampled data. The data is then standardized, and dimensional reduction techniques are applied to
explore the patterns and relationship within the data which is known as Unsupervised learning.
Similarly, Supervised learning is used to classify the cancer type from the gene expressions using
Random Forest, Support Vector Machine (SVM) and Logistic regression algorithms. The
effectiveness of each method is discussed in this project.
Cancer subtypes in the dataset
• BRCA: Breast Invasive Carcinoma
• KIRC: Kidney Renal Clear Cell Carcinoma
• COAD: Colon Adenocarcinoma
• LUAD: Lung Adenocarcinoma
• PRAD: Prostate Adenocarcinoma 
First, it looks at the data without predefined categories, using methods like Principal Component Analysis (PCA) and K-means
clustering to find hidden patterns. Then using models like Random Forest, Support Vector Machines (SVM) and Logistic Regression to categorize
different types of cancer based on gene expression patterns. Among the classification algorithms, Random Forest emerged as the optimal
choice due to its high accuracy, robustness, and resilience against overfitting

Even though there has been progress, there are still challenges like uncomfortable biopsies,
treatments that don't work well, and the difficulty of tracking how cancer changes over time. But
ongoing research, using genetics and molecular technologies, gives us hope for better ways to
diagnose and treat cancer. 
