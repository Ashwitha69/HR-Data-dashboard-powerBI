For developing dashboard for HR data analysis,firstly read and analyze the given excel data carefully to procedd for further process,then load the data into powerBI desktop.
To perform the data preprocessing steps like missing data,null value data,duplicate data etc.we go for trasform data in the powerBI desktop,which will redirect it into power query editor.
After applying neccessary steps in preprocessing click close&apply.Then the processed data will load into powerBI desktop.
To know the empolyee count,i have choosen card visualization and dragged empolyee count field into values input box,similarly do the same for attrition,attrition count,Active empolyees etc.
We can also give specific title to each cards in formal visual>title and we can specify background color and text color and border radius etc.
To get Attrition rate i have used DAx calculations by giving measure =sum('hr data'[empolyee count])/sum('hr data'[attrition]).
To find department wise attrition i have selected Pie chart visulization,and dragged department in x axis and attrition count as y axis.
To find gender wise attrition I have choosen matrix visualization and dragged required values.
By performing all the operations HR data analysis dashboard has been prepared.
