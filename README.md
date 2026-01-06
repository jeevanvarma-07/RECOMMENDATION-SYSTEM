# RECOMMENDATION-SYSTEM

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: JEEVAN VARMA

*INTERN ID*: CT04DR2749

*DOMAIN*: MACHINE LEARNING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

Task-4 sought to develop and apply a **Recommendation System using Collaborative Filtering methods. Modern digital platforms like Netflix, Amazon, YouTube, and Spotify depend on suggestion systems to customize material and increase audience participation. Rather than depending just on product characteristics, this project centers on creating a system that suggests items to consumers depending on the likes and actions of other comparable people. 
 
 The project shows how useful recommendations may be created by using concepts of machine learning, data analysis, and similarity calculation. 
 
 --- 
 
 The idea of collaborative filtering is 
 
 A recommendation approach called Collaborative Filtering works on the premise that **future user tastes are probably similar to those shown in the past**. Rather than examining item characteristics, this method finds trends and similarities using user-item interactions including ratings. 
 
 User-based collaborative filtering was used in this project, whereby recommendations are produced for a user by examining the rating behavior of other users most comparable to them. 
 
 --- 
 
 ### Description of the dataset 
 
 Real-world user interactions were simulated by means of a structured movie-rating dataset. The collection includes: 
 
 * **User IDs** that reflect several users 
 * Names of films denoting items 
 * Users assign numerical scale ratings 
 
 User preferences are recorded by this dataset, which also serves as the basis of cooperative filtering. Though the dataset is modest, it properly illustrates the rationale and operation of a recommendation engine and fits for internship-level use and explanation. 
 
 --- 
 
 Data preparation is 
 
 The dataset was transformed into a User–Item Matrix, in which: 
 
 * Users are rows 
 * Columns stand for films. 
 * Cell values denote rankings. 
 
 Missing values come naturally as not all consumers rank all products. Common and acceptable for simple collaborative filtering models, these missing grades were substituted with **zeros**. This stage guarantees that error-free calculation of similarities is possible. 
 
 --- 
 
 Computation of Similarity 
 
 Cosine Similarity was used to gauge the degree of likeness among users. Calculating the cosine of the angle between two rating vectors, cosine similarity helps to compare user behavior irrespective of rating scale variations. 
 
 Generated was a User–User Similarity Matrix with: 
 
 * Values near to 1 suggest great resemblance. 
 * Values approaching **0** point to minimal similarity. 
 
 The system suggested's intellectual heart consists in this matrix. 
 
 -
 ### **Recommendation Principles 
 
 To create movie suggestions for a target user, a customized recommendation function was used. The procedure consists of: 
 
 1. Finding users most akin to the target user 
 2. Gather movies classified by comparable users. 
 3. Movies already evaluated by the target user should be omitted. 
 4. Calculating weighted ratings based on similarity values 
 5. Classifying and suggesting the best goods 
 
 This guarantees that the user receives **customized recommendations** that are both fresh and appropriate from the system. 
 
 ---- 
 
 Evaluation and Validation 
 
 Because quantitative measures for suggestion systems typically need vast datasets, a **logic-based evaluation technique was employed. The assessment confirms that: 
 
 * The items recommended were not formerly rated by the user. 
 * Recommendations come from **same user tastes**. 
 
 To help to grasp similarity patterns and improve interpretability, a picture of the **user similarity matrix** was also created. For basic recommendation system solutions, this evaluation methodology is fitting and widely accepted. 
 
 --- 
 
 ### End 
 
 Utilizing Python, Pandas, and Scikit-learn, this effort shows how effectively a **Collaborative Filtering-based Recommendation System** can be implemented. By looking at user similarity and rating behavior, the system effectively creates customized suggestions. The project includes all crucial phases: dataset preparation, matrix construction, similarity calculation, recommendation generating, and evaluation. 
 
 The execution fulfills all the standards of **Task-4 of the CODTECH internship** and offers a solid conceptual basis for more sophisticated recommendation systems like hybrid recommendation systems, content-based filtering, or matrix factorization.

 ##OUTPUT:

 <img width="487" height="395" alt="Image" src="https://github.com/user-attachments/assets/95d9e234-0bef-4a14-b2cf-ff2ebde34051" />
<img width="625" height="221" alt="Image" src="https://github.com/user-attachments/assets/92ef1d42-070b-424f-991c-329623e355c3" />
<img width="402" height="223" alt="Image" src="https://github.com/user-attachments/assets/5fce0658-5358-4ed7-a1ea-4b768d630efd" />
<img width="412" height="231" alt="Image" src="https://github.com/user-attachments/assets/deca04a3-b8ff-4dc6-a9ca-52dc2b1d2994" />
<img width="306" height="364" alt="Image" src="https://github.com/user-attachments/assets/9edc4855-6ce7-4ab6-9759-a537f8d73826" />
