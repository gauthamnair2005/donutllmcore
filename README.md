# Donut LLM Core Library
This library will be used by future versions of Donut-LLM-Tools, instead of CreateLLM library.

## Usage
### LLM Creation
```python
import DonutLLMCore
model = DonutLLMCore.ModelTrainer(path,max_iters=100)
model = model.trainer()
```

### LLM Usage
```python
import DonutLLMCore
path = input("Enter the path of the model : ")
model = DonutLLMCore.LLMModel(path)
prompt = input("Enter prompt : ")
print(model.generate(prompt))
```