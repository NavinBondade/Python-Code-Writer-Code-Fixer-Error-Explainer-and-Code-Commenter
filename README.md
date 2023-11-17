# Python Code Fixer and Explainer
<p align="center">
<img src="https://content.fortune.com/wp-content/uploads/2023/09/FORTUNE-CODE-FINAL-WEB-1.jpg">
</p>
<p>Programming is not an easy task as it involves many types of complexities, because of which we often encounter various errors. Comprehending these errors and fixing the code requires a strong understanding of the code and brilliant debugging skills. The errors are often so subtle and tough to catch that the developer spends hours fixing them. Also, a huge chuck of time goes into searching the solution online at websites like StackOverflow. In short, this is a very hectic and time-consuming task. So, in order to make it easy, I have developed an AI system that not only fixes your Python code with one click but also explains the error and its solutions. 
</p>
<h2>Libraries Used</h2>
<ul>
  <li>LangChain</li>
  <li>Hugging Face</li>
  <li>Streamlit</li>
</ul>
<h2>Methodology</h2>
<p>The AI system has two engines, meaning it utilizes two large language modes at its core. The first one is the CodeLlama model that is used to fix the errored code of the user. With the prompt engineering technique, I crafted a custom prompt that incorporate instructions about what the CodeLlama model should do. The prompt also includes the errored code and the error message generated by the Python interpreter. This prompt acts as input to the CodeLlama model. </p>
<p>
Considering the error message with respect to the user's code, the CodeLlama model produces the error-free fixed code. The second model here is the Zephyr model. A custom prompt mentioning "explain the error" and the user-provided error message is passed to the Zephyr model. After understanding the error, the model outputs a short but accurate explanation of the error message. Streamlit is used to develop the web app.</p>
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
<h2>Run The Code</h2>
```rb
# path/to/your/file.rb
class MyClass
end
<h2>Demo Video</h2>


https://github.com/NavinBondade/Python-Code-Fixer-and-Explainer/assets/43030152/61308ebf-a372-4e1b-86af-47cf0a849a51


<h2>Errors Fixed By The AI </h2>
<h3>Module Not Found Error:</h3>
<p align="center">
<img src="Python Code Fixer and Explainer/results/q1.png" width="650" height="750">
</p>
<h3>Named Error:</h3>
<p align="center">
<img src="Python Code Fixer and Explainer/results/q2.png"  width="650" height="850">
</p>
<h3>Index Out of Range Error:</h3>
<p align="center">
<img src="Python Code Fixer and Explainer/results/q3.png"  width="650" height="750">
</p>
<h3>Attribute Error:</h3>
<p align="center">
<img src="Python Code Fixer and Explainer/results/q4.png"  width="650" height="750">
</p>
<h2>Conclusion</h2>
<p>Here in this project, I have built an AI system that fixes the errors of the user's code using two large language modes, i.e. CodeLlama and Zephyr.</p>
