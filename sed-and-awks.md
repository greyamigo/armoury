* Remove certain line / lines in a file
  ```sed -i.bak -e '1,17d;17d' /Users/greyamigo/.ssh/known_hosts```

* Standard sed substitution
  ```sed -e "s/%ENV%/${APPNAME}/g" scripts/env_variables.sh >tmp_1.sh ``` 