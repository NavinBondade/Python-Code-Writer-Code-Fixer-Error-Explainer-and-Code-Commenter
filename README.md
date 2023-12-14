# Python Code Writer, Code Fixer, Error Explainer and Come Commenter Powered By CodeLLAMA and Zephyr
<p align="center">
<img src="https://www.simplilearn.com/ice9/free_resources_article_thumb/Best_AI_Code_Generators.jpg">
</p>
<p>Writing functional code is not an easy task as it involves many types of complexities. It requires a strong understanding of the programming language and brilliant debugging skills. Developers have often found either writing very unoptimal code or totally lost in resolving bugs and errors. In order to make it easy and less time-consuming, I have developed an AI system that writes Python code as per the user-provided question. The system is also capable of fixing errors in your Python code, explaining the error and its solutions, and commenting out the entire code for better documentation.
</p>
<h2>Libraries Used</h2>
<ul>
  <li>LangChain</li>
  <li>Hugging Face</li>
  <li>Streamlit</li>
</ul>
<h2>Methodology</h2>
<h3>Python Code Fixer and Error Explaine</h3>
<p>This AI system has two engines, meaning it utilizes two large language modes at its core. The first one is the CodeLlama model that is used to fix the errored code of the user. With the prompt engineering technique, I crafted a custom prompt that incorporate instructions about what the CodeLlama model should do. The prompt also includes the errored code and the error message generated by the Python interpreter. This prompt acts as input to the CodeLlama model. </p>
<p>
Considering the error message with respect to the user's code, the CodeLlama model produces the error-free fixed code. The second model here is the Zephyr model. A custom prompt mentioning "explain the error" and the user-provided error message is passed to the Zephyr model. After understanding the error, the model outputs a short but accurate explanation of the error message. Streamlit is used to develop the web app.</p>
<h3>Python Code Writer</h3>
<p>In this system, the model CodeLlama model for writing the Python code as per the user-provided question. A custom prompt has been designed mentioning that the model is an expert Python programmer and its job is to write error-free Python code as per the user's question. This prompt plus the question asked is given to the model to generate an accurate and optimized Python code. </p>
<h2>Code Llama</h2>
<p align="center">
<img src="https://eu-images.contentstack.com/v3/assets/blt6b0f74e5591baa03/blte5bc08f6abc8fa88/64e8d065d0894c88706deab4/Code_Llama_(1).png?disable=upscale&width=1200&height=630&fit=crop">
</p>
<p>Code Llama is a code-specialized version of Llama 2 that was created by further training Llama 2 on its code-specific datasets, sampling more data from that same dataset for longer. Essentially, Code Llama features enhanced coding capabilities, built on top of Llama 2. It can generate code, and natural language about code, from both code and natural language prompts. It can also be used for code completion and debugging. </p>
<h2>Zephyr 7B Beta</h2>
<p align="center">
<img src="https://huggingface.co/HuggingFaceH4/zephyr-7b-alpha/resolve/main/thumbnail.png">
</p>
<p>
Zephyr is a series of language models that are trained to act as helpful assistants. Zephyr-7B-β is the second model in the series, and is a fine-tuned version of mistralai/Mistral-7B-v0.1 that was trained on on a mix of publicly available, synthetic datasets using Direct Preference Optimization (DPO).
</p>
<h2>Demo Video</h2>
<h3>Python Code Fixer and Error Explaine</h3>


https://github.com/NavinBondade/Python-Code-Fixer-and-Explainer/assets/43030152/300a62ef-1b4b-4630-9879-4f4fb88436be



<h3>Python Code Writer</h3>


https://github.com/NavinBondade/Python-Code-Fixer-and-Explainer/assets/43030152/666cfda5-d200-4afa-a436-84fc73766f8f

<h3>Python Comment Writer</h3>


https://github.com/NavinBondade/Python-Code-Writer-Code-Fixer-Error-Explainer-and-Code-Commenter/assets/43030152/1f86731b-ac17-4884-8083-a128ee9db09a



<h2>Python Code Written By The AI </h2>
<h3>Data Science & Machine Learning Questions:</h3>
<h4>How to train neural network in tensorflow?</h4>
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/d1.png">
<h4>Write an example of linear regression in scikit learn?</h4>
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/d4.png">
<h4>How to convert numpy array into tensor?</h4>
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/d2.png">
<h4>How to split dataset in train and test using scikit learn?</h4>
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/d3.png">
<h3>General Python Questions</h3>
<h4>Write a program to print the given number is odd or even.</h4>
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/c3.png">
<h4>Write a program to find a fibonacci of a number.</h4>
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/c4.png">
<h4>Write a program to remove duplicates from a list.</h4>
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/c6.png">
<h4>Write a program to find the second largest number in a list.</h4>
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/c1.png">


<h2>Errors Fixed & Explained By The AI </h2>
<h3>Module Not Found Error:</h3>
<p align="center">
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/q1.png" width="650" height="750">
</p>
<h3>Named Error:</h3>
<p align="center">
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/q2.png"  width="650" height="850">
</p>
<h3>Index Out of Range Error:</h3>
<p align="center">
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/q3.png"  width="650" height="750">
</p>
<h3>Attribute Error:</h3>
<p align="center">
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/q4.png"  width="650" height="750">
</p>

<h2>Comments Added By The AI  To Python Code</h2>
<h3>Python Program to Find Armstrong Number in an Interval</h3>
<p align="center">
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/comment1.png"  width="650" height="1000">
</p>
<h3>Python Program to Create a Countdown Timer</h3>
<p align="center">
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/comment13.png"  width="650" height="850">
</p>
<h3>Python Program to Transpose a Matrix</h3>
<p align="center">
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/comment2.png"  width="650" height="950">
</p>
<h3>Python Program to Reverse a Number</h3>
<p align="center">
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/comment4.png"  width="650" height="750">
</p>
<h3>Python Program to Find Sum of Array</h3>
<p align="center">
<img src="Python Code Writer, Code Fixer, Error Explainer and Come Commenter/results/comment5.png"  width="650" height="850">
</p>


<h2>Conclusion</h2>
<p>Here in this project, I have built an AI system that writes Python code as per user's question, fixes the errors of the user's code, explain the error and also comment out the code using two large language modes, i.e. CodeLlama and Zephyr.</p>
