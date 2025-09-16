for i in {1..10}
do
  echo "Commit $i" >> history.txt
  git add .
  git commit -m "Commit $i"
done
git push origin main
