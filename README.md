# streamlit-analytics-app-quickstart
## 代码样例
```
import streamlit as st
import streamlit_analytics2 as streamlit_analytics

with streamlit_analytics.track():
    st.write("Hello, World!")
    st.button("Click me")
```


## 查看结果
 - 在url后面添加'?analytics=on'就可以查看统计.

<img width="784" alt="image" src="https://github.com/zgimszhd61/streamlit-analytics-app-quickstart/assets/114722053/404b5fc2-947a-49de-870c-6c93d3446405">
