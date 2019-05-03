### DS 5559 Exploratory Text Analytics Final Project
### UVA MSDS 2018 Spring 2019

### Fang You (fy6vj)，Wenxi Zhao (wz8nx), Ruoyan Chen (rc3my)

### Overview: 
This project primarily aims to study Victor Hugo, one of the most influential figures in 19th French literature. We would first look at Hugo’s major works at different stages of his life and study how his writing style evolved through time and influenced by social movements. Since Hugo was at the forefront of the Romantic literary movement, we would compare his works with those of Alexandre Dumas, another French writer of the same period. We would compare these two authors’ writing styles, narrations structures and expression of romanticism. We would also compare Hugo’s works with those of Charles Dickens, one of the the greatest British novelist of the Victorian era. The comparison between Hugo and Dickens targets their different social and culture backgrounds, and study whether discrepancies in such backgrounds influences their writings. 

For each of the 3 writers we wish to study i.e.: Victor Hugo, Alexandre Dumas and Charles Dickens, we would look at 3 of their most prominent works. These 9 books are all hosted on Project Gutenberg and are publicly available. For Hugo, we are using Les Miserables, The Hunchback of Notre Dame and Ninety-Three. For Dumas, we are using The Count of Monte Cristo, The Man in the Iron Mask and The Black Tulip. For Dickens, we are using Great Expectations, Oliver Twist and Bleak House. The 9 books have approximately 60,000 observations (paragraphs) in total. 


### Individual Research Questions: 
Fang You: Use sentiment analysis to identify characteristics that define and contribute to Hugo’s Romanticism. 

Wenxi Zhao: According to the KDEs and PCAs of the three works of Victor Hugo, what’s the difference and similarity between them and how does his style change over time and over period?

Ruoyan Chen: Use sentiment analysis to identify the different romanticisms between 3 authors.


### Content: 
./csv_output: F4 compliant digital editions of the corpora as exported CSV files. 

./data: Original texts obtained from Project Gutenberg. 

./db: F4 compliant digital editions of the corpora as single SQLite files.

./eda(part): Some exploratory data analysis. 

./lexicon: Lexicon database generated based on Opinion Lexicon (Bing et al.), NRC Emotion Lexicon and General Inquirer lexicon. 

Other jupyter notebook files in base directory: F5-level extensions to the F4 editions, such as topic model tables, sentiment analyses, KDE, PCA, etc.
