---
title: first blog
date: 2020-04-21 18:30:33
author: Eve
tags:
---

# yijibiaoti
## erji
test test

```python
cap = None
camera = 'rtsp://admin:ldsw1234@10.168.1.248:554/h264/ch1/main/av_stream'
cap = cv2.VideoCapture(camera)

#import model
ctx = mx.gpu()
net=gluon.SymbolBlock.imports(symbol_file='mobilenet0.25-symbol.json', input_names=['data'], param_file='mobilenet0.25-0000.params', ctx=ctx)

#fps
```

