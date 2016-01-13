# Scalable-tf-idf
Tf-Idf Scoring for Large Corpus of Textual Data using Apache Spark (v1.5.2 and later) MapReduce

Usage:<br>
<ol>
  <li> Import the class into your code using: <code>from tfidf import TF-IDF</code>.</li>
  <li> Initialization: <code>job = TF-IDF(<i>input_path</i>,<i>output_path</i>)</code> where <code><i>input_path</i></code> is the path to the directory containing the corpus and <code><i>output_path</i></code> is the path to the OUTPUT directory.</li>
  <li> Run the MapReduce Job: <code>job.run()</code> and a CSV file will be created in the OUTPUT directory.</li>
</ol>
<br>
<i>Note: The default SparkContext is initialized on a</i> <code>'local'</code> <i>cluster and with default executor memory at 1GB.</i>
