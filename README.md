# DF 通用圓桌/座位圖產生器

一個基於 **Streamlit** 的輕量型 Web App，能從 DataFrame（Excel/CSV）快速產生：

- **圓桌布局**：支援網格與交錯排列  
- **桌名上色**：依桌名自動切換淺彩虹配色  
- **SVG 下載**：向量格式可做後製  
- （未來可擴充 PNG、標題、記錄上傳下載等）

---

## 快速上手

1. 開啟瀏覽器，進入：  
   `https://share.streamlit.io/chenmapper/table_app/main/app.py`  
2. 上傳含「姓名」欄位的 Excel/CSV  
3. 設定**列數**、**行數**、**交錯排列**、**桌名欄位**  
4. 下載 SVG 並開啟做後製

---

## 在本機跑

```bash
git clone https://github.com/chenmapper/table_app.git
cd table_app
pip install streamlit pandas svgwrite openpyxl xlrd
streamlit run app.py
