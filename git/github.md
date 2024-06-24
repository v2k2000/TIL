…or create a new repository on the command line
echo "# TIL" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/v2k2000/TIL.git
git push -u origin 


- README.md 디렉토리 최상단에 있는것을 깃허브에서 자동으로 연결하는 기능이 있다.