| Feature | Description | Code Example |
| --- | --- | --- |
| Interactive Tables | Allows for interactive exploration of data frames. | `from google.colab import data_table` <br> `import pandas as pd` <br> `data = {'Name': ['Alice', 'Bob', 'Charlie'], 'Age': [25, 30, 35]}` <br> `df = pd.DataFrame(data)` <br> `data_table.DataTable(df, include_index=False)` |
| Execution History | Shows a history of executed code cells. | Not applicable. This feature is built into the Colab interface. |
| Command Palette | Provides a quick way to access various commands and settings. | Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac) |
| Code Snippets | Offers predefined code snippets for common tasks. | Click on "Code snippets" in the left sidebar. |
| Collaborative Editing | Supports real-time collaboration with others. | Share the Colab notebook link with others. |
| Markdown Support | Allows for rich text formatting in text cells. | Use Markdown syntax in text cells. |
| GPU/TPU Support | Provides access to GPU/TPU for accelerated computing. | Go to "Runtime" -> "Change runtime type" -> Select GPU/TPU. |
| Integration with Google Drive | Allows for easy access and management of files. | `from google.colab import drive` <br> `drive.mount('/content/drive')` |
| Extensions | Supports various extensions for additional functionality. | Not applicable. Colab does not support extensions. |
| Customizable Shortcuts | Allows users to customize keyboard shortcuts. | Go to "Tools" -> "Keyboard shortcuts" to customize. |
| TensorFlow Integration | Provides seamless integration with TensorFlow for machine learning tasks. | `import tensorflow as tf` <br> `print(tf.__version__)` |

