# Today we are learning Git

## fast foward

当merge 的时候属于同一个commit

## 3 way merge

merge bugfix 后，master 会有2个parent commit.一个是C4 一个是C3

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/196c71be-d4fb-4786-a825-cfb0a99d250b/Untitled.png)

## 有冲突的3way merge

当C3和C4修改了同一个文件的时候，这时就会出现conflict

通过git ls-files -s

可以查看到
