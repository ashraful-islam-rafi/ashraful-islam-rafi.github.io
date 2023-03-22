### how to run on local machine...
ref: https://jekyllrb.com/docs/installation/

if everything is installed, follow below steps:
```
1. cd _to_project_dir_
2. bundle install
3. bundle exec jekyll serve --incremental
4. goto http://localhost:4000
```

If facing,  `require': cannot load such file -- webrick (LoadError)` then run the following commands:
```
>> bundle add webrick
>> bundle exec jekyll serve --incremental
```