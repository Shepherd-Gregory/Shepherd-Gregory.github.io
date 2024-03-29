- If you change anything in `_config.yml`, you have to rebuild the website again after that (e.g., if you are running `bundle exec jekyll serve`, you have to kill it and re-run again). [Directory is not right after changing _config.yml](https://github.com/alshedivat/al-folio/issues/318)

  > ```shell
  > $ bundle install
  > $ bundle exec jekyll serve
  > ```



- Markdown emo

  https://github.com/ikatyang/emoji-cheat-sheet

Sometimes, the deployment can not be successful, due to the version of ruby, then please tune the version in the deploy.yml file:

> with:
>         ruby-version: '3.1'
