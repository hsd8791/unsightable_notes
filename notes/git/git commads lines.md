 git ������
 $ mkdir learngit
$ cd learngit
$ pwd/Users/michael/learngit
$ git init 
$ ls -ah //��ʾ��ǰ�ļ�

$ git add readme.txt
$ git commit -m "wrote a readme file"
git log
git reflog  //annotation reference log
git checkout  -- filename
git reset HEAD filename

$ ssh-keygen -t rsa -C "youremail@example.com"
## git push -u origin master  
error: src refspec master does not match any. ����ô����ԭ����,Ŀ¼��û���ļ�,��Ŀ¼�ǲ����ύ��ȥ��
git remote add origin git@github.com:hsd8791/gitlearn.git
git clone git@github.com:hsd8791/test2016.10.14.git

$ git remote -v
$ git push origin dev

�鿴��֧��git branch
������֧��git branch <name>
�л���֧��git checkout <name>
����+�л���֧��git checkout -b <name>
�ϲ�ĳ��֧����ǰ��֧��git merge <name>
ɾ����֧��git branch -d <name>


git tag <tagname>
git tag -a <tagname> -m '<message>'   <commit ID>
git tag -s v0.2 -m "signed version 0.2 released" fec145a  ˽�б�ǩ  ����~~

git show <tagname>
git tag

git push origin <tagname>��������һ�����ر�ǩ��
git push origin --tags��������ȫ��δ���͹��ı��ر�ǩ��
git tag -d <tagname>����ɾ��һ�����ر�ǩ��
git push origin :refs/tags/<tagname>����ɾ��һ��Զ�̱�ǩ

git pull ����ǰ��֧��Զ�̿�ȡ�����أ���Ӱ�챾���Ѿ��༭�������ݣ�
$ git commit -a -m ""          #�ȼ���: $ git commit -am ""

git remote set-url origin URL

git remote rm origin
git remote add origin git@github.com:Liutos/foobar.git


git remote set-branches [--add] <name> <branch>...
git remote set-url [--push] <name> <newurl> [<oldurl>]
git remote set-url --add <name> <newurl>
git remote set-url --delete <name> <url>