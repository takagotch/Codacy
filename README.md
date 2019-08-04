### codacy
---
https://github.com/codacy

https://www.codacy.com/

```sh
sbt docker:publishLocal
docker run -it -v $srcDir:/src <DCOKER_NAME>:<DOCKER_VERSION>

bundle install --path vendor/bundle
bundle exec src/main/ruby/rubocop_doc/generator.rb
bundle exec src/main/ruby/codacy/rubocop/generator.rb
rm -f rubocop-doc.yml
```

```
```

```
```


