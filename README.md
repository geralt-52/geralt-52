# Lead Scoring Case Study



## 💡 Problem Statement <a name = "idea"></a>


<div class="text_component ckOutput">
    <p>As you can see, there are a lot of leads generated in the initial stage (top) but only a few of them come out as
        paying customers from the bottom. In the middle stage, you need to nurture the potential leads well (i.e.
        educating the leads about the product, constantly communicating etc. ) in order to get a higher lead conversion.
    </p>
    <p>&nbsp;</p>
    <p>X Education has appointed you to help them select the most promising leads, i.e. the leads that are most likely
        to convert into paying customers. The company requires you to build a model wherein you need to assign a lead
        score to each of the leads such that the customers with a higher lead score have a higher conversion chance and
        the customers with a lower lead score have a lower conversion chance. The CEO, in particular, has given a
        ballpark of the target lead conversion rate to be&nbsp;around 80%.</p>
    <p>&nbsp;</p>
    <p><strong>Data</strong><br>You have been provided with a leads dataset from the past with around 9000 data points.
        This dataset consists of various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last
        Activity, etc. which may or may not be useful in ultimately deciding whether a lead will be converted or not.
        The target variable, in this case, is the column ‘Converted’ which tells whether a past lead was converted or
        not wherein 1 means it was converted and 0 means it wasn’t converted. You can learn more about the dataset from
        the data dictionary provided in the zip folder at the end of the page. Another thing that you also need to check
        out are the levels present in the categorical variables. Many of the categorical variables have a level called
        'Select' which needs to be handled because it is as good as a null value (think why?).</p>
    <p>&nbsp;</p>
    <h2><strong>Goals of the Case Study</strong></h2>
    <p>There are quite a few goals for this case study:</p>
    <ol>
        <li>Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be
            used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most
            likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.
        </li>
        <li>There are some more problems presented by the company which your model should be able to adjust to if the
            company's requirement changes in the future so you will need to handle these as well. These problems are
            provided in a separate doc file. Please fill it based on the logistic regression model you got in the first
            step. Also, make sure you include this in your final PPT where you'll make recommendations.</li>
    </ol>
    <p>&nbsp;</p>
    <h2><strong>Results Expected</strong></h2>
    <ol>
        <li>A well-commented Jupyter notebook with at least the logistic regression model, the conversion predictions
            and evaluation metrics.</li>
        <li>The word document filled with solutions to all the problems.</li>
        <li>The overall approach of the analysis in a presentation.<ol>
                <li>Mention the problem statement and the analysis approach briefly&nbsp;</li>
                <li>Explain the results&nbsp;in business terms</li>
                <li>Include visualisations and summarise the most important results in the presentation</li>
            </ol>
        </li>
        <li>A brief summary report in 500 words explaining how you proceeded with the assignment and the learnings that
            you gathered.</li>
    </ol>
    <p>&nbsp;</p>
</div>

## 🎉 Labs completed by <a name="acknowledgments" href="https://github.com/geralt-52">Sourav Sharma</a>

