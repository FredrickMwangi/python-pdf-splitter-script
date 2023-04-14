<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	
</head>
<body>
	<h1>PDF Splitter</h1>
	<p>This Python code splits a PDF document into several PDF files based on the specified page range for each output file. The code uses the <code>pikepdf</code> library to work with PDF files.</p>
<h2>Requirements</h2>
<p>To run this code, you will need to have the <code>pikepdf</code> library installed. You can install it using pip:</p>
<pre><code>pip install pikepdf</code></pre>

<h2>Usage</h2>
<p>To use this code, simply specify the input PDF file name and the page ranges for each output file in the <code>file2pages</code> dictionary. The page ranges are 0-indexed and include the lower bound but not the upper bound, so if you want to split the PDF file into files with pages 0-9, 10-19, and 20-29, you would specify the following:</p>
<pre><code>file2pages = {
0: [0, 10],
1: [10, 20],
2: [20, 30],
}</code></pre>
<p>Once you have specified the input file and the page ranges, simply run the code and it will generate the output PDF files with names based on the input file name and an index number.</p>

<h2>License</h2>
<p>This code is released under the MIT License. See LICENSE file for details.</p>

<h2>Acknowledgements</h2>
<p>This code uses the <code>pikepdf</code> library, which is released under the Apache License 2.0. See <a href="https://github.com/pikepdf/pikepdf">https://github.com/pikepdf/pikepdf</a> for details.</p>
</body>
</html>
