# Diamond-Price-Prediction
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Brief-Description">Brief Description<a class="anchor-link" href="https://www.kaggle.com/code/hiteshbhakuni/diamond-price-prediction/#Brief-Description" target="_self" rel=" noreferrer nofollow">¶</a></h3><p>The dataset for this project contains attributes and prices of around 54,000 diamonds.</p>
<p><strong>Main Objectives:</strong></p>
<p>In this project, I'm visualizing feature correlations through pairplots to identify relevant features. Following that, I'll construct various regression models using advanced techniques, including GridSearch, ML pipelines, and hyperparameter tuning. The objective is to obtain the most accurate predictive model while highlighting the shortcomings of each model.</p>

<p><strong>Introduction:</strong></p>
<p>This project involves predicting the price of approximately 54,000 diamonds based on various attributes. These attributes include the weight (carat), dimensions (length, width, and depth), depth percentage (%Depth), table width, and quality, color, and clarity ratings. The goal is to build a predictive model that can accurately estimate the price of diamonds based on these features, which are crucial determinants in the diamond pricing market. This prediction task holds significant value for both buyers and sellers in the diamond industry, aiding in informed decision-making and price assessment.</p>

<p>The ten features and target are :</p>
<ol>
<li>Weight (carat): weight of the diamond.</li>
<li>Length (x): length of the diamond.</li>
<li>Width (y): width of the diamond</li>
<li>Depth (z): depth of the diamond.</li>
<li>%Depth: depth percentage. Formula: z / mean(x, y) = 2 * z / (x + y)</li>
<li>Table: width of top of the diamond relative to the widest point.</li>
<li>Quality: quality of the diamond. Possible values (from best to worst): ideal, premium, very good, good, fair.</li>
<li>Color: color of the diamond. Possible values: from D (best) to J (worst).</li>
<li>Clarity: measurement of how clear the diamond is. Possible values (from best to worst): IF, VVS1, VVS2, VS1, VS2, SI1, SI2, I1.</li>
<li>Price (target): price of the diamond in US dollars.</li>
</ol>

<p><strong>Machine Learning Analysis and Findings:</strong></p>
<p>In the upcoming analysis, I will conduct a comparison among four distinct regression models: Vanilla, Lasso, Ridge, and ElasticNet. The primary focus will be on assessing their accuracy in predicting Diamond prices. To achieve robust modeling, I'll employ various techniques including standard scaling, polynomial effects, regularization regression, cross- validation, and grid search. I'll also evaluate model performance using metrics such as RMS and R2 Score.</p>

<p><strong>Model Flaws and Strength and Advanced steps::</strong></p>
<p>In terms of simplicity, it's worth noting that vanilla linear regression delivered respectable predictive results, although not the absolute best. It stands out as the simplest and fastest model in terms of parameters. On the other hand, models like Lasso, Ridge, and ElasticNet yielded higher results in accuracy, but they introduced complexity and slowed down the training process, particularly when employing grid search to fine-tune parameters. This presents a tradeoff scenario: for larger datasets, these more complex models may offer superior performance, albeit with longer training times, whereas opting for the vanilla model might involve a slight accuracy sacrifice but significantly faster training.</p>

<p>In terms of the best model, LassoCV comes with the highest R2 score and we can't ignore that despite its training process is slow.</p>

<p><strong>Advanced steps::</strong></p>
<p>To boost the model's effectiveness, we utilize regularization techniques such as L1 (Lasso) and L2 (Ridge) to manage overfitting and stabilize coefficients. Furthermore, the inclusion of k-fold cross-validation assists in evaluating the model's resilience and fine-tuning hyperparameters, ensuring its ability to generalize effectively across various data subsets. These methods together result in heightened model accuracy and dependability in regression applications.</p>
<p>For more insight on this project 'Diamond Price Prediction,' please check <a href='https://github.com/Izuchukwu234/Diamond-Price-Prediction/blob/main/Diamond%20Price%20Analysis.pdf'>here</a></p>
</div>
