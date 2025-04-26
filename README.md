# assignment-3-recommendation-systems-solved
**TO GET THIS SOLUTION VISIT:** [Assignment 3 (Recommendation Systems) Solved](https://www.ankitcodinghub.com/product/assignment-3-recommendation-systems-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;8207&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Assignment 3 (Recommendation Systems) Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (4 votes)    </div>
    </div>
<div class="product-description">
This assignment is worth 20 points. The assignment is individual effort.

Problem Definition

Let’s say we have 8 users, and they have rated 8 different albums on a scale of 1 to 5. Note that not all users have rated all albums.

songData3 = {“Angelica”: {“Blues Traveler”: 3.5, “Broken Bells”: 2.0, “Norah Jones”: 4.5, “Phoenix”: 5.0, “Slightly Stoopid”: 1.5, “The Strokes”: 2.5, “Vampire Weekend”: 2.0},

“Bill”:{“Blues Traveler”: 2.0, “Broken Bells”: 3.5, “Deadmau5”: 4.0, “Phoenix”: 2.0, “Slightly Stoopid”: 3.5, “Vampire Weekend”: 3.0},

“Chan”: {“Blues Traveler”: 5.0, “Broken Bells”: 1.0, “Deadmau5”: 1.0, “Norah Jones”: 3.0, “Phoenix”: 5, “Slightly Stoopid”: 1.0},

“Dan”: {“Blues Traveler”: 3.0, “Broken Bells”: 4.0, “Deadmau5”: 4.5, “Phoenix”: 3.0, “Slightly Stoopid”: 4.5, “The Strokes”: 4.0, “Vampire Weekend”: 2.0},

“Hailey”: {“Broken Bells”: 4.0, “Deadmau5”: 1.0, “Norah Jones”: 4.0, “The Strokes”: 4.0, “Vampire Weekend”: 1.0},

“Jordyn”:&nbsp; {“Broken Bells”: 4.5, “Deadmau5”: 4.0, “Norah Jones”: 5.0, “Phoenix”: 5.0, “Slightly Stoopid”: 4.5, “The Strokes”: 4.0, “Vampire Weekend”: 4.0},

“Sam”: {“Blues Traveler”: 5.0, “Broken Bells”: 2.0, “Norah Jones”: 3.0, “Phoenix”: 5.0, “Slightly Stoopid”: 4.0, “The Strokes”: 5.0},

“Veronica”: {“Blues Traveler”: 3.0, “Norah Jones”: 5.0, “Phoenix”: 4.0, “Slightly Stoopid”: 2.5, “The Strokes”: 3.0}

}

Requirement for this Assignment

You have been provided with a framework for this assignment: “Assignment 3 –&nbsp;<a href="http://framework.py/" target="_blank" rel="nofollow noopener noreferrer">Framework.py</a>”.

The Framework defines a Class called similarity. You must use the class as-is with no changes. The class includes a class initialization method which takes two rating dictionaries ratingP and ratingQ as parameters. The class has two methods:

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; minkowski which takes a single parameter r, and returns the Minkowki Distance between the two dictionaries (that the Class object is instantiated with).

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; pearson which takes no parameters, and returns the Pearson Correlation between the two dictionaries (that the Class object is instantiated with).

Given a userX, write code to find the NN (k=1) recommendations for userX based on the Euclidean Similarity measure. Pseudo-code has been provided to you in the framework. So, you essentially need to plug in appropriate code for steps 1 through 5 in the framework.

Since this is the same data as used in the Recommendation Systems Lecture, you should check your output against the Lecture for accuracy.

Assignment Submission

Some things to keep in mind as you code:

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Make your code readable – for instance, use meaningful variable names and comments.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Make your code elegant – for instance, balance the number of variables you introduce – too many or too few make your code difficult to debug, read, and maintain.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Make your output readable and user-friendly

Once you have written up the script, save it as follows. Submit the script by uploading your python script. Note: upload the actual script – DO NOT attach a screenshot of the script!

&lt;FirstName&lt;<a href="http://lastnameassignment3.py/" target="_blank" rel="nofollow noopener noreferrer">LastNameAssignment3.py</a>.

[Example:&nbsp;<a href="http://hinaaroraassignment3.py/" target="_blank" rel="nofollow noopener noreferrer">HinaAroraAssignment3.py</a>]

The submitted script will be run as-is for grading. I will be plugging in different users for userX to see if your code is giving me the correct recommendations.

Points will be deducted for scripts that:

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; are difficult to read/follow

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; don’t compile/run

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; don’t have all the various pieces of code required

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; have hard-code values instead of using variables

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; have logical errors

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; don’t result in the expected output

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; don’t have user-friendly output

&nbsp;

</div>
<div class="ui divider"></div>
