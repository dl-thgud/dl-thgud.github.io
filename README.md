# dl-thgud.github.io
----

## GitHub Pages

### empty repository
```
echo "# dl-thgud.github.io" >> README.md
git init
git add README.md
git config --global user.email "dl-thgud@naver.com"
git config --global user.name "dl-thgud"
git remote add origin https://github.com/dl-thgud/dl-thgud.github.io.git
git push -u origin master
```

```
git clone https://github.com/dl-thgud/dl-thgud.github.io.git
cd dl-thgud.github.io
echo "Hello World" > index.html
git add --all
git commit -m "Initial commit"
git push -u origin master
```

## Ruby 설치
```
sudo apt-get install ruby-full
```

## Jekyll 준비
```
gem install bundler jekyll
jekyll new dl-thgud.github.com
cd dl-thgud.github.com
```

## Jekyll 실행
```
bundle exec jekyll serve
```