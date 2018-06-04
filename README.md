# GitHub网页版的使用
## 1.创建仓库
New repository，repository name就是项目的名称

## 2.删除仓库
1.  删除repository可以在repository的settings中，拉到最底部，可见delete this repository。
2.  要输入repository name再次确认防止误删除。

## 3.修改仓库
4.  可以uploads文件和文件夹，但是网页版限制文件数量。
5.  每次修改都要填写Commit changes
6.	可以在commits中查看各个修改节点，点击某节点右边的“Browse the repository at this point in the history”，直接查看该修改节点的状态，可以进行克隆和下载

## 4.分支branch
1.	用于合作完成项目。
2.	master是默认主branch，可以穿件一个新的branch。
3.	在新branch上面修改的项目可以与master上面的项目进行比较。点击“New pull request”进行Compare changes，根据变化情况，如果符满意修改情况，则进行合并操作“Merge pull request” - “Confirm merge”，然后删除分支“delete branch”。

## 5. 克隆和下载
1.	点击“Clone or download”，“open in desktop”是克隆到github的客户端，“download ZIP”是下载。

# 客户端操作
## 1.创建仓库
File - New repository，name就是项目的名称，local path是存放的本地地址。

## 2. 删除仓库
要在客户端中remove，也要在本地删除项目文件夹。

## 3.修改仓库
1. 在本地文件夹中修改，然后修改记录会显示在客户端中
2. 填写Commit changes，然后确定提交
3. 在History中可以看到各次修改记录，Revert此次修改记录，则相当于删除这次修改，而不是回到这个修改节点。

## 4.同步仓库
3. 第一次将本地仓库同步到云端（网页版），点击“Publish”，后面的话会变成“Fetcch origin”。
4. 如果修改了网页版的仓库，则客户端会显示“Pull”，点击“Pull”将云端的仓库同步到本地。

## 5.分支branch
1. 可以在客户端创建branch，然后publish到网页端；也可以在网页端创建branch，然后fetch到客户端。
2. 在客户端branch上的修改，需要进行“Push”到网页端；在网页端branch上的修改，需要进行“Pull”到客户端（有延迟）；
3. current branch选master，然后branch - compare to branch，选择要与之比较的branch，然后在右侧可以看到变化的情况，满意则“Merge into master”