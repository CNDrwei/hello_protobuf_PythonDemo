Python中protobuf3基础demo
1.protoc --version查看你的protoc版本

2.编写addressbook.proto文件,详情见`addressbook.proto`

3.根据proto文件生成xxx_pb2.py文件`protoc --python_out=./ proto文件名称`

4. 新建data文件夹，编写`addressbook_test_writing.py`

5. 编写`addressbook_test_reading.py`就能看到data下面生成addressbook.txt文件了，也能完整的读取这个txt文件


