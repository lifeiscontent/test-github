# Exercise Answers

### Exercise 1 - Beginner

1.  
  ```
  cd ../../
  ```
2.  
  ```
  ls
  ```
3.  
  ```
  ls -l
  ```
4.  
  ```
  ls -a
  ```
5.  
  ```
  mkdir clean_code_examples
  ```
6.  
  ```
  touch omarion.txt
  ```
7.  
  ```
  touch socks_to_buy
  vi socks_to_buy
  
  press i to enter insert mode and add this text:
  
  #!/usr/bin/env bash 
  "echo 'I should wait to buy socks until next Fall.'" > socks_to_buy.txt
  
  press esc to exit insert mode
  
  :w to save entered content
  
  press enter
  
  :q to quit vi mode
  
  press enter
  
  chmod +x  socks_to_buy.txt
  
  ./shopping
  
  
  
  ```
8.  
  ```
  pwd
  ```
9.  
  ```
  echo $(whoami)
  ```
10.  
  ```
  ls ../../
  ```
11.  
  ```
  touch list_of_best_cat_pictures.html
  ```
12.  
  ```
  mkdir ~/My_Documents
  cd ~/My_Documents
  ```
13.  
  ```
  ping 8.8.8.8
  ```
14.  
  ```
  ~/documents/
  ```
15.  
  ```
  echo "My name is `whomai`"
  ```
16.  
  ```
  tail -f tylers_favorite_songs.txt -f sarahs_favorite_songs.txt
  
  ctrl + c to quit out
  ```
17.  
  ```
  man echo 
  man echo > echo_options.txt
  ```
18.  
  ```
  ping 127.0.0.1 -c 2
  ```
19.  
  ```
  cat *.md
  ```
20.  
  ```
  rm -rf yesterdays_todo_list.md
  ```

### Exercise 2 - Intermediate

```
mkdir ~/commandline-practice
```
```
cd ~/commandline-practice
```

1.

```
touch myname.md
```
```
echo Obed Ampah > myname.md
```
```
touch myfavoritefoods.md
```
```
echo Pizza Salads Gummie Bears > myfavoritefoods.md
```
```
touch dreamproject.md
```
```
echo I would like to create an app to make interactive collages.  > dreamproject.md
```
```
touch music.md
```
```
echo Michael Franks - The Art of Tea - 1975 > music.md
```
```
touch colors.md
```
```
echo green > colors.md
```

2.

```
ls -lh >> filesizes.txt
```
3.
```
mkdir backups
```
```
cd ..
tar -czf backup1.tar commandline-practice
mv backup1.tar commandline-practice/backups/
```
4.
```
touch sites.txt
echo $'\ngoogle.com\n' >> sites.txt
echo $'\nrotoworld.com\n' >> sites.txt
echo $'\namazon.com\n' >> sites.
```
5.
```
curl -L study.moderndeveloper.com >> study.html 
```
6.
```
cd commandline-practice
mv backup1.tar `date`
```
7.
```
cd ..
wc -w dreamproject.md 

echo $'\nMy collage application would take in all your moments and display them in an ineractive collage.\n' >> dreamproject.md
```
8. 
```
grep -R "\.js" study.html >> javascripts.html
```
9.
```
cd ..
cat *.txt | wc
```
10.
```
cd ~/commandline-practice
cd ..
tar -czf backup2.tar commandline-practice/
mv backup2.tar commandline-practice/backups/
cd commandline-practice
find *.md *.html *.txt -delete
```

### Exercises 3 - Advanced

1.

```
#!/usr/bin/env bash
echo Expanding $1 into  $2
mkdir $2
tar -zxf $1 -C $2
echo "done"
```

2.

```
obed:commandline-practice obed_work$ clear
#!/usr/bin/env bash

mkdir $1


mkdir css
mkdir images
mkdir js
touch css/style.css
touch js/main.js
git clone https://github.com/h5bp/html5-boilerplate.git

````

