# new-demo


mkdir my-html-pages
<br>
cd my-html-pages
<br>
git init
<br>
echo "<!DOCTYPE html><html><head><title>Page 1</title></head><body>Page 1 Content</body></html>" > page1.html
echo "<!DOCTYPE html><html><head><title>Page 2</title></head><body>Page 2 Content</body></html>" > page2.html
echo "<!DOCTYPE html><html><head><title>Page 3</title></head><body>Page 3 Content</body></html>" > page3.html
<br>
git add .
<br>
git commit -m "Initial commit with 3 HTML pages"
<br>
git remote add origin https://github.com/<your-username>/my-html-pages.git
<br>
git branch -M main
<br>
git push -u origin main
<br>
git pull origin main


