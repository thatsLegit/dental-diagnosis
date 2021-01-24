# dental-diagnosis

The purpose of this project was to apply different techniques of machine learning on a realworld dataset.<br><br>
            The studied dataset contained different features of patients from the Centre Hopitalier Universitaire (CHU) of Toulouse, and had the purpose of defining if the patients were at risk of having a disease on their tooth supporting tissues. Unfortunately we had this dataset only temporarily and had to delete it after the project was over because of privacy concerns.<br><br>
            The machine learning techniques applied were: SVM, KNN and Random Forest.<br>
            After preprocessing the data and tuning the models to obtain the best results for the available data, the most accurate algorithm was a linear SVM model, with a 100% accuracy.<br><br>
            These results were very encouraging and we could easily imagine such a model sort of back-checking doctors in their diagnosis or alert them when a diagnosis seems very unusual.<br>
            The most challenging part of the project was, as very often in ML projects, the preparation of the data. We had to test different solutions on how to deal with missing data (deleting the whole row, interpolate a value, consider null values as ‘real’ data by transforming them into a category ‘undefined’…).
