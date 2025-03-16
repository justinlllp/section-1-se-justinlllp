# 使用 Python 3.11 slim 版本作為基礎映像
FROM python:3.11-slim

# 設定工作目錄
WORKDIR /app

# 複製當前資料夾內容到容器的 /app 資料夾
COPY . /app

# 安裝應用所需的依賴（例如 Flask）
RUN pip install --no-cache-dir -r requirements.txt

# 開放容器內部的 5000 埠
EXPOSE 5000

# 設定容器啟動時執行的命令
CMD ["python", "main.py"]
