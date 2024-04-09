# HDFS command

<p>Help</p>

```
hdfs dfs -help
```

<p>Help with specific statement</p>

```
hdfs dfs -help <statement>
```

<p>Create directory</p>

```
hdfs dfs -mkdir /newfolder
```

<p>View directory (add -R to view sub-directories)</p>

```
hdfs dfs -ls /
```

<p>Copy file from local to HDFS</p>

```
hdfs dfs -put ~/filefromlocal.txt /folderhdfs/
```

<p>Copy file from HDFS to local</p>

```
hdfs dfs -get /folderhdfs/filefromhdfs.txt /localfolder/
```

<p>View file content</p>

```
hdfs dfs -cat /hdfsfolder/test.txt
```

<p>Move file/folder</p>

```
hdfs dfs -mv /hdfsfolder1 /hdfsfolder2
```

<p>Remove file/folder</p>

```
hdfs dfs -rm /hdfsfolder/test.txt
```
