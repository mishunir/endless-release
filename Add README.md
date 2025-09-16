# Clone repo
git clone https://github.com/endless-labs/endless-bridge-contract.git
cd endless-bridge-contract

# Make 10 commits
echo "line 1" >> test.txt
git add .
git commit -m "Commit 1"

echo "line 2" >> test.txt
git add .
git commit -m "Commit 2"

# repeat until 10 commits
git push origin main
