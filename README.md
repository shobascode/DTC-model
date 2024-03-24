## Project Title: Operation Smart or Ultra?

### Mission Briefing
<font size="5">Mobile carrier Megaline has discovered that many of their subscribers are still on legacy plans and wants to encourage them to switch to newer plans: Smart or Ultra. Your mission is to develop a model that analyzes subscribers' behavior and recommends the most suitable plan. You have access to pre-processed behavior data from subscribers who have already switched to the new plans. Your task is to develop a classification model that accurately predicts whether a subscriber should be recommended the Smart or Ultra plan.</font>

### Goal
Develop a model that recommends one of Megaline's plans (Smart or Ultra) with the highest possible accuracy. The threshold for accuracy is set at 0.75.

### Understanding the Data
Each observation in the dataset contains monthly behavior information about one user. The features provided include:
- Calls: Number of calls
- Minutes: Total call duration in minutes
- Messages: Number of text messages
- MB Used: Internet traffic used in MB
- is_ultra: Plan for the current month (Ultra - 1, Smart - 0)

### Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

### Project Structure
1. **Data Preprocessing**
   - Importing necessary libraries
   - Loading pre-processed data
   - Splitting data into training, validation, and test sets
   
2. **Model Development**
   - Implementing a Decision Tree Classifier
   - Experimenting with different values of max_depth
   - Selecting the model with the highest and best balance of training and validation accuracy
   
3. **Model Evaluation**
   - Assessing the model's performance using sklearn accuracy_score function
   - Plotting a confusion matrix to visualize predictions vs. actual values
   - Performing a sanity check to compare training and testing accuracy

### How to Run
1. Clone the repository to your local machine.
2. Navigate to the file "DTC Mobile Carrier Recommender".
3. Ensure that the required libraries are installed (Pandas, Scikit-learn, Matplotlib, Seaborn).
4. Run the provided Jupyer Notebook to execute the code.
5. View the results, including accuracy scores and confusion matrix visualization.

### Contact Information
- [GitHub](https://github.com/shobascode)
- [LinkedIn]([https://linkedin.com/in/yourname](https://www.linkedin.com/in/shoba-santosh])

### Acknowledgements
Special thanks to TripleTen for providing the Megaline dataset and project instructions.
