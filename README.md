# fileProcessing

Sample:
from fileProcessing import FileProcessing
fp = FileProcessing("read_dir", "save_dir")
# 加载json数据
json_file = fp.load_data("name")
# 加载csv数据
csv_file = fp.load_data("name", "csv")
# 保存
fp.save_file(data, "file_name", "json")
