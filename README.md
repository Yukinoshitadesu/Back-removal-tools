# Back-removal-tools
```python
##自動去背
!pip install rembg
from rembg import remove
from PIL import Image

# Open the input image
image_input = Image.open("你的圖片位址")

# Remove the background
output = remove(image_input)

# Save the output image
output.save("你要輸出的圖片位址")  # You need to specify a file path for saving
```
