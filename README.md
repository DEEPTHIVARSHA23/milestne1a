# milestne1a
import yaml

with open(r'C:\Users\Hp\Downloads\DataSet.zip\Milestone1\Milestone1A.yaml') as file: documents = yaml.full_load(file)

for item,doc in documents.items():
    print(item,".",doc)
