FROM python:3.9
# 
WORKDIR /
# 
COPY  requirements.txt ./
# 
RUN pip install --no-cache-dir -r requirements.txt 
# 
COPY train.py ./
#
COPY breast_cancer.csv ./
#
CMD ["python3", "train.py"]