# NotePad
This is an AndroidStudio rebuild of google SDK sample NotePad
在noteslist_item.xml中再加入一个Textview
![3](https://github.com/oldman4ever/NotePad/blob/master/NotePad-master/screenshot/3.png)

新建笔记在NotePadProvider中的insert方法，修改笔记在NoteEditor中的updateNote方法，我们需要修改这个方法中的时间戳格式
NotePadProvider中的insert方法:
![4](https://github.com/oldman4ever/NotePad/blob/master/NotePad-master/screenshot/4.png)
NoteEditor中的updateNote方法:
![5](https://github.com/oldman4ever/NotePad/blob/master/NotePad-master/screenshot/5.png)
将修改时间的列投影出来
NotesList中PROJECTION添加上修改时间：
![6](https://github.com/oldman4ever/NotePad/blob/master/NotePad-master/screenshot/6.png)
将显示列dataColumns和他们的viewIDs加入修改时间这一属性
![7](https://github.com/oldman4ever/NotePad/blob/master/NotePad-master/screenshot/7.png)

最终结果：
![1](https://github.com/oldman4ever/NotePad/blob/master/NotePad-master/screenshot/1.png)

