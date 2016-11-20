# graymatter_programmingexercise
program exercise
Steps to execute the below scripts.
1. sed '1d;$d' Sample_Data_2016.csv > No_HRD_TRL_Sample_Data_2016.csv.
2. hadoop fs -put No_HRD_TRL_Sample_Data_2016.csv <hadoop_Location>
3. hadoop fs -chmod 777 <hadoop_Location>/No_HRD_TRL_Sample_Data_2016.csv
4. RUN THE PIG SCRIPT.
