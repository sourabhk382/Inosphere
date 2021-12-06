# Inosphere
                      Classification of Radar returns from the Ionosphere

Introduction to Radar returns
- The Goose Bay system consists of a phased array of 16 high-frequency antennas with a total transmitted power on the order of 6.4 kilowatts. 
- The targets were free electrons in the ionosphere.
- "Good" radar returns are those showing evidence of some type of structure in the ionosphere.
- "Bad" returns are those that do not; their signals pass through the ionosphere.
- Received signals were processed using an autocorrelation function whose arguments are the time of a pulse and the pulse number. 
- There were 17 pulse numbers for the Goose Bay system. Instances in this database are described by 2 attributes per pulse number i.e total 17*2=34 features. 

Methodology
- Data pre-processing -  converting categorical values into numerical values.
- Feature selection
- ML model - fit Logistic Regression, Support Vector Machine(SVM)
- Later, comparative analysis of both the models.

Data
- This radar data was collected by a system in Goose Bay, Labrador. 
