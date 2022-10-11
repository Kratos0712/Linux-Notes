# Archiving and Compression in linux

## Archieve file
```
tar -zcvf doc.tar.gz Directory/

### Archiving and Compressing with tar
- 'f' will specify the filename for the directory (docs.tar.gz in this case)

- 'v' is verbose, means that we will get one line of output for each file we are compressing

- 'c' is for create, we are creating a new archive

- 'z' is for zipping (we are using the g zip program), used to compress archive as well as archiving it

## Unarchieve file
```
tar -zxf doc.tar.gz
```
### Unzips a tar directory HERE (in this location) 
- 'z' shows that it is g zipped

- 'x' means to extract it 

- 'f' defines the archive filename (in this case: docs.tar.gz)
