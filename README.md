# knowledge-embeddings

pip install rapidocr_onnxruntime
pip install rapidocr_api

env/Scripts/python -s -m pip install pyinstaller -i https://pypi.tuna.tsinghua.edu.cn/simple

pyinstaller -F ocr_api.py --add-data "env\Lib\site-packages\rapidocr_onnxruntime:rapidocr_onnxruntime" --clean
