- hexo分支上为博客的源文件，master分支上为执行`hexo g -d`后生成的博客文件
- 换电脑后更博：
  1. git clone hexo分支
  2. npm install hexo
  3. npm install
  4. npm install hexo-deployer-git
- 更博：
  1. git add .
  2. git commit -m "..."
  3. git push origin hexo
  4. hexo g -d