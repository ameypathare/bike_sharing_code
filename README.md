## bike_sharing_code

$${\color{lightgreen}Overview \space Of \space Code:}$$
<br>

<li>The Project in being executed in databricks Why? Bcause RDBMS cant handle 100 GB on compresed data. If we unzip this files the data will be in tons.
    <ul type = "circle">
         <li>Uploaded the files to databricks</li>
         <li>Copied the files to localpath</li>
         <li>Extracted the contents from local path to dbfs.</li>
         <li>Loaded the files from dbfs</li>
   </ul>
</li> 
<br>


<li>Data Cleaning</li> 
    <ul type = "circle">
    ${\color{red}Null \space Handling \space used:}$
     <li>isNull()</li>
     <li>isNotNull()</li>
      <li>fillna(value)</li>
      <li>dropna()</li>
    </ul>
  <br>
  
   <ul type = "circle">
 ${\color{red}Duplicate \space Handling \space used}$
   <li>dropDuplicates()</li>
   <li>distinct()</li>
   </ul>
<br>

 <ul type = "circle">
  ${\color{red}Date \space functions \space used}$
   <li>DATEPART</li>
   </ul>
  <br>

  <ul type = "circle">
  ${\color{red}Column \space Operations \space used}$
   <li>withColumn(columnName, expression)</li>
   <li>drop(columnName)</li>
   <li>alias(newName)</li>
   </ul>
  <br>

   <ul type = "circle">
  ${\color{red}Filtering \space and \space Validation \space used}$
   <li>filter(condition)</li>
   <li>where(condition)</li>
   </ul>
  <br>
  
  <ul type = "circle">
  ${\color{red}Date \space Functions}$
   <li>to_date(column, format)</li>
  </ul>

<br>
<li>Removed Outliers as the outliers were present more in the pickup_counts column</li> 
<br>

<li>Checked Multicollinearity and dropped columns where values were sperated from rest of the columns</li> 
<br> 
 
<li>Performed  EDA</li> 
<br>

<li>Charts used</li> 
    <ul type = "circle">
    ${\color{red}Null \space Handling \space used:}$
     <li>BarChart</li>
     <li>BoxPlot</li>
      <li>Pairplot</li>
      <li>HeatMap</li>
    </ul>
  <br>

  <li>Train test split the data into 80% and 20%  EDA</li> 
  <br>

  <li>Made use of Vector assembler and StandardScaler</li> 
  <br>

  <li>Models  used</li> 
  <br>
  
<li>Charts used</li> 
    <ul type = "circle">
     <li>Linear  Regression</li>
     <li>Lasso  Regression</li>
     <li>Elastic  Net</li>
      <li>Ridge  Regression</li>
    </ul>
  
