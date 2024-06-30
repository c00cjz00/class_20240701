# class_20240701
- Get nvidia api key
https://build.nvidia.com/nvidia/nemotron-4-340b-instruct

- Open colab
https://colab.research.google.com/github/c00cjz00/class_20240701/blob/main/lesson01/02_api_case3.ipynb

- Add  api_key in 02_api_case3.ipynb 
```
from openai import OpenAI
client = OpenAI(
  base_url = "https://integrate.api.nvidia.com/v1",
  api_key = "nvapi-xxxxxxxxxxxxxxxxxxx"
)
```

