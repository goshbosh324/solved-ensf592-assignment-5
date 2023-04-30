Download Link: https://assignmentchef.com/product/solved-ensf592-assignment-5
<br>
5/5 - (1 vote)

<header></header>



 <main></main>



<span style="font-size: 2em;">&#x1f4da; Learning Outcomes</span>

<ul>

 <li>Manipulate and analyze data using Pandas DataFrame objects</li>

 <li>Read Excel data into a DataFrame</li>

 <li>Use hierarchical indexing to sort and slice data</li>

 <li>Process data according to specifications</li>

 <li>Find missing values in a dataset</li>

 <li>Operate on data in Pandas</li>

</ul>

<h2 id="programspecifications">&#x1f4bb; Program Specifications</h2>

The United Nations and other international organizations collect data on various demographics worldwide. You are being asked to design a terminal-based application for computing and printing statistics based on a provided UN sub-region name. Your application must meet the following design specifications:

<ul>

 <li>Your final output should match the given examples (see attached screenshots)</li>

 <li>Stage 1: DataFrame Creation</li>

</ul>

<ol>

 <li>Import the provided data into a Pandas DataFrame.</li>

 <li>You may not change or sort the Excel file.</li>

 <li>You may not hard-code/copy-paste any information into your program except for the Excel column names.</li>

 <li>Index the data in the following order: UN Region -&gt; UN Sub-Region -&gt; Country</li>

 <li>All of the below specifications must show the data in the correctly sorted order.</li>

 <li>You may not use global variables. You must import the data within your main function.</li>

</ol>

<ul>

 <li>Stage 2: User Entry</li>

</ul>

<ol>

 <li>Prompt the user to enter a sub-region name.</li>

 <li>If the name does not exist within the given data, raise a ValueError to print “You must enter a valid UN sub-region name.”</li>

 <li>Again, you must not hard-code the names (the UN could decide to change the sub-region names at any time!).</li>

</ol>

<ul>

 <li>Stage 3: Find Missing Data</li>

</ul>

<ol>

 <li>It is not always possible to collect complete data from all countries. Some countries do not have sq km area measurements. Write a function called <code>find_null()</code> to determine whether any area data is missing for the chosen sub-region.</li>

 <li>Your function may take in any arguments or return any values of your choosing.</li>

 <li>If all sq km data is available for the sub-region, print the message “There are no missing sq km values for this sub-region.”</li>

 <li>If any data is missing, print the UN Region/UN Sub-Region/Country information and the NaN sq km value.</li>

</ol>

<ul>

 <li>Stage 4: Sub-Region Calculations</li>

</ul>

<ol>

 <li>Add two new columns to the sub-region data: a) the change in population from 2000 to 2020 and b) the current population density (num of people per sq km).</li>

 <li>Print all columns for each country in the sub-region.</li>

 <li>Conservationists are concerned about the number of threatened plant, bird, fish, and mammal species in each country. Print the number of threatened species in each category for each country in the sub-region.</li>

 <li>To better estimate possible rehabilitation and sanctuary space, calculate and print the sq km area per the total number of threatened species for each country in the sub-region.</li>

 <li>Put a clear header before each printed dataset for better readability.</li>

</ol>

<ul>

 <li>Your code should include and use at least one multi-index Pandas DataFrame, at least one IndexSlice object, a user-defined function called <code>find_null</code>, at least one masking operation, and at least one built-in Pandas or NumPy computational method.</li>

 <li>Your code must follow the conventions discussed so far in the course (names<em>with</em>underscores, ClassNames, four spaces for indentations, spaces between variables/operators, comments throughout, etc.)</li>

 <li>All classes, methods, and functions must contain docstring documentation.

  <ol>

   <li>For each class, include a functionality summary and describe any class and/or instance variables (do not include a separate docstring for __init__)</li>

   <li>For each method/function, include a functionality summary and describe parameters and return values (or specify if there are none)</li>

   <li>Main functions do not need a docstring but should be well-commented</li>

  </ol></li>

 <li>Your code will be run by the TAs as your end user.</li>

 <li>FAQs about the assignment will be answered on the D2L discussion boards. Please check the boards for any clarifications before submitting.</li>

 <li>The grading rubric will be posted to D2L.</li>

</ul>

<h2 id="assignmenttasks">&#x1f4dd; Assignment Tasks</h2>

<ul>

 <li>Make sure to watch video lessons 18 – 24, labs 8 and 9, and review the corresponding Jupyter Notebooks.</li>

 <li>Clone this repository to your local computer.</li>

 <li>Open VSCode and start a new terminal. Make sure that your <code>ensf592</code> environment is activated.</li>

 <li><code>world_data.py</code> is provided as a starting point. Fill in the header with your own information.</li>

 <li>Remember to test your program execution via the terminal: <code>python world_data.py</code></li>

 <li>Take a screenshot of your successful program run and upload it to your assignment repository.</li>

 <li>Commit your screenshot and code.</li>

 <li>Push your local git history to github: <code>git push origin main</code></li>

 <li>Submit your repository HTTPS link to the Assignment 5 D2L dropbox.</li>

 <li>Tip: If you want to learn more about a specific aspect of a Python object or the functionality of Pandas, remember to take a look at the official documentation!</li>