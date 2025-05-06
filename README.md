# stats500-homework-9-solved
**TO GET THIS SOLUTION VISIT:** [STATS500 Homework 9 Solved](https://www.ankitcodinghub.com/product/stats500-homework-9-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96607&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;STATS500 Homework 9 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
<ol>
<li>Consider Problem #6 on page 233 of Chap. 15 and the description of the dataset ’butterfat’: ’Average butterfat content (percentages) of milk for random samples of twenty cows (ten two- year old and ten mature (greater than four years old)) from each of five breeds.’ Use the butterfat data with ‘Butterfat’ as the response, ’Breed’ as the predictor, and only consider the ’Mature’ (see ’Age’) subset. Answer 6 (b), 6 (c) and 6 (d). Note: for 6 (d), after saving the results from “TukeyHSD”, you can plot these intervals as shown on pages 229-230 in the textbook.</li>
<li>Use the pima data and the codes below to answer the questions.
<pre>     library(faraway)
     data(pima)
     pima$diastolic[pima$diastolic == 0] &lt;- NA
     pima$glucose[pima$glucose == 0] &lt;- NA
     pima$triceps[pima$triceps == 0] &lt;- NA
     pima$insulin[pima$insulin == 0] &lt;- NA
     pima$bmi[pima$bmi == 0] &lt;- NA
     pima.dat &lt;- pima
     pregn &lt;- rep("common", length(pima$pregnant))
     pregn[pima.dat$pregnant&gt;=10] &lt;- "high"
     pima.dat$pregn &lt;- pregn
     test.out &lt;- glm(test~pregnant+ glucose+bmi+diabetes+pregnant:glucose,family=binomial,pima.dat)
     test2.out&lt;-glm(test~pregn+ glucose+bmi+diabetes+pregn:glucose,family=binomial,pima.dat)
</pre>
<pre>     summary(test.out)
     summary(test2.out)
</pre>
<ol>
<li>(a) &nbsp;Provide the model that corresponds to “test.out” in the R-codes above.</li>
<li>(b) &nbsp;Suppose you are interested to learn whether a higher level of bmi would lead to a higher chance of showing signs of diabetes using the model in the problem above. What would be the H0 and Ha? Describe your test result and conclusion.</li>
<li>(c) &nbsp;In “test2.out”, we are interested at learning whether the association between glucose level and the chance of showing signs of diabetes changes with two levels of times being pregnant: common/regular and high. Comment on what you find.</li>
</ol>
</li>
</ol>
</div>
</div>
</div>
