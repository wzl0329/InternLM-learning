
# Second_Class

课程地址：

[tutorial/helloworld/hello_world.md at main · InternLM/tutorial (github.com)](https://github.com/InternLM/tutorial/blob/main/helloworld/hello_world.md)



![image-20240109162558758](img/img_2/image-20240109162558758.png)

**基础作业：**

- 使用 InternLM-Chat-7B 模型生成 300 字的小故事（需截图）。

  ![image-20240109172849299](img/img_2/image-20240109172849299.png)

- 熟悉 hugging face 下载功能，使用 `huggingface_hub` python 包，下载 `InternLM-20B` 的 config.json 文件到本地（需截图下载过程）。
-   在下载时如果网络连接错误可指定环境变量，同时使用local_dir指定本地路径
  
  ```python
  import os
  os.environ['HF_ENDPOINT'] = 'https://hf-mirror.com'
  from huggingface_hub import hf_hub_download  # Load model directly
  
  hf_hub_download(repo_id="internlm/internlm-7b", filename="config.json", local_dir="download")
  ```

  ![image-20240110183143578](img/img_2/image-20240110183143578.png)

**进阶作业（可选做）**

- 完成浦语·灵笔的图文理解及创作部署（需截图）

![image-20240110165433011](img/img_2/image-20240110165433011.png)

![image-20240110165204229](img/img_2/image-20240110165204229.png)

- 完成 Lagent 工具调用 Demo 创作部署（需截图）

  ![image-20240110155427832](img/img_2/image-20240110155427832.png)

  ![image-20240110155820244](img/img_2/image-20240110155820244.png)
