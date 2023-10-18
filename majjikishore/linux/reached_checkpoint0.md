mkdir majjikishore
cd majjikishore/
mkdir Documents
touch file1.txt file2.txt file3.txt
ll
touch .hidden_file
ll -a
vim file1.txt
cat file1.txt
mkdir "-"
cd ./-
cd .
cd -
cp Documents My_Docs
cp -r  Documents My_Docs
cat .hidden_file
cd My_Docs/
mv Documents/file1.txt Documents/file1.txt .
mv file2.txt .
cd Documents/
mv file2.txt ../
cd ..
rm -rf majjikishore/
ls
