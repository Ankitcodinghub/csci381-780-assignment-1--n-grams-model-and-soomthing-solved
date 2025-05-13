# csci381-780-assignment-1--n-grams-model-and-soomthing-solved
**TO GET THIS SOLUTION VISIT:** [CSCI381-780 Assignment 1- N-Grams Model and Soomthing Solved](https://www.ankitcodinghub.com/product/csci381-780-assignment-1-n-grams-model-and-soomthing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93710&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI381-780 Assignment 1- N-Grams Model and Soomthing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1 Language modeling

PART I:

(10 points) Do exercise 3.4 from Chapter 3 in the textbook: https://web.stanford.edu/ ̃jurafsky/slp3/3.pdf

PART II:

In this assignment, you will train several language models and will evaluate them on a test corpus. You can discuss in groups, but the homework is to be completed and submitted individually. Two files are provided with this assignment:

1. train.txt

2. test.txt

Each file is a collection of texts, one sentence per line. train.txt contains 10,000 sentences from the NewsCrawl corpus. You will use this corpus to train the language models. The test corpus test.txt is from the same domain and will be used to evaluate the language models that you trained.

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1. (5 points) 2. (5 points)

3. (10 points)

4. (15 points)

5. (15 points)

</div>
<div class="column">
How many word types (unique words) are there in the training corpus? Please include the padding symbols and the unknown token.

How many word tokens are there in the training corpus?

What percentage of word tokens and word types in the test corpus did not occur in training (before you mapped the unknown words to &lt; unk &gt; in training and test data)? Please include the padding symbols in your calculations.

Now replace singletons in the training data with &lt; unk &gt; symbol and map words (in the test corpus) not observed in training to &lt; unk &gt;. What percentage of bigrams (bigram types and bigram tokens) in the test corpus did not occur in training (treat &lt; unk &gt; as a regular token that has been observed).

Compute the log probability of the following sentence under the three models (ignore capitalization and pad each sentence as described above). Please list all of the parameters required to compute the probabilities and show the complete calculation. Which of the parameters have zero values under each model? Use log base 2 in your calculations. Map words not observed in the training corpus to the &lt; unk &gt; token.

</div>
</div>
<div class="layoutArea">
<div class="column">
1.1 Pre-processing

Prior to training, please complete the following pre-processing steps:

<ol>
<li>Pad each sentence in the training and test corpora with start and end symbols
(you can use &lt; s &gt; and &lt; /s &gt;, respectively).
</li>
<li>Lowercase all words in the training and test corpora. Note that the data already
has been tokenized (i.e. the punctuation has been split off words).
</li>
<li>Replace all words occurring in the training data once with the token &lt; unk &gt;.
Every word in the test data not seen in training should be treated as &lt; unk &gt;.

1.2 Training the models
</li>
</ol>
Please use train.txt to train the following language models: 1. A unigram maximum likelihood model.

2. A bigram maximum likelihood model.

3. A bigram model with Add-One smoothing.

1.3 Questions

Please answer the questions below:

</div>
</div>
<div class="layoutArea">
<div class="column">
• I look forward to hearing your reply .

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
6. (20 points) Compute the perplexity of the sentence above under each of the models.

7. (20 points) Compute the perplexity of the entire test corpus under each of the models. Discuss

the differences in the results you obtained.

1.4 Submission

Please include all the required code files in a tarball and email the tarball and the report to nlp.qc.cuny@gmail.com using subject line CSCI381/CSCI780 Homework 1:

<ol>
<li>The tarball should include the Python code along with a README file that has instructions on how to run it in order to obtain the answers to questions in Sec- tion 1.3</li>
<li>The report that should be attached separately to the same email should include the answers to the questions in PART I and PART II in Section 1.3</li>
</ol>
Your grade will be based on the correctness of your answers, the clarity and completeness of your responses, and the quality of the code that you submitted.

Please refer to the course webpage on late submission policy.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
