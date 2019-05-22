# git-webinar

- Create repo with readme
  - `git clone git@...url`
- `git init`
  - `git remote add origin git@...url`
- создаём файл `.gitignore` (со списком игнорируемых файлов)
- `git add .`
- `git commit -m 'initial commit'`
- `git push origin master`

- `git checkout -b gh-pages`
- Пишем код
- `git add .`
- `git commit -m 'COde for review'`
- `git push origin gh-pages --set-upstream`

- Создаём **Pull Request** на Github
  - base: `master`
  - compare `gh-pages`
- Github -> settings выбираете ветку `gh-pages` для публичной страницы
- ссылку на публичную страницу добавляете в описание **Pull Request**
- ссылку на **Pull Request** присылаете на проверку

