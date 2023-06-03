# BankLoanOffer
<div style="width: 100%; background-color: #6a89cc; color: white; padding: 20px; border: 3px solid #0c2461; margin-bottom: 20px;border-radius:10px;">
    <h3 style="color: #0c2461;">Introduction</h3>
    <span >Nowadays, the importance of identifying customers and how to offer them is very serious, so companies want to know the possibility of accepting that offer before making an offer to their customers so that they can give the right offer to their customers.<br/>
In this dataset, we have many bank customers, each of whom has characteristics, and finally, we can find out whether they have accepted the previous offer to receive a loan from the bank or not. By building a good model, we can predict that another person who We are supposed to make a proposal will accept our proposal or not, and at the end, we will give a person with known characteristics to the model to determine whether he will accept the loan or not.
    </span> 
    <h3 style="color: #0c2461;">Tasks in this notebook</h3>
    <ul style="list-style-type: none; padding-left: 0;">
        <li><span style="margin-left: -10px;"></span> Import libraries</li>
        <li><span style="margin-left: -10px;"></span> Read dataset and get information from data</li>
        <li><span style="margin-left: -10px;"></span> Cleaning Dataset</li>
        <li><span style="margin-left: -10px;"></span> Features</li>
        <li>
            <span style="margin-left: -10px;"></span> Modeling
            <ul style="list-style-type: none; padding-left: 20px;">
                <li><span style="margin-left: -10px;"></span> Logestic Regression</li>
                <li><span style="margin-left: -10px;"></span> Complement Naive Bayes (CNB)</li>
                <li><span style="margin-left: -10px;"></span> KNN (K-Nearest Neighbors)</li>
                <li><span style="margin-left: -10px;"></span> Decision Tree classifier</li>
                <li><span style="margin-left: -10px;"></span> Random Forest classifier</li>
            </ul>
        </li>
        <li><span style="margin-left: -10px;"></span>Predict an unseen data</li>
    </ul>
</div>


|Column|description|
|:------------------------------:|:-----------------------------:|
|<code>ID</code>|Customer ID|
|<code>Age</code>|Customer's age|
|<code>Experience</code>|Years of customer experience|
|<code>Income</code>|Customer's annual income|
|<code>ZIP Code</code>|Customer's home address zipcode|
|<code>Family</code>|Customer's family members count|
|<code>CCAvg</code>|Avg. spending on credit cards per month|
|<code>Education</code>|Education level<br><i>undergraduate : 1<br>graduated : 2<br>Advanced education : 3<i/>|
|<code>Mortgage</code>|value of house mortgage|
|<code><b>Personal Loan [target variable]<b/></code>|Did the customers accept the offer in the last campaign?|
|<code>Securities Account</code>|Does the customer have a securities account with the bank?|
|<code>CD Account</code>|Does the customer have a certificate of deposit (CD) account with the bank?|
|<code>Online</code>|Does the customer use internet banking facilities?|
|<code>CreditCard</code>|Does the customer use a credit card issued by UniversalBark|
