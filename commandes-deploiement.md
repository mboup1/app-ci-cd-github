npm install -g angular-cli-ghpages


Configurer les Autorisations d'Écriture pour les Actions :
repository/setting/actions/general
-Read and write permissions
- Allow GitHub Actions to create and approve pull requests


ng build --output-path=dist --base-href=/app-test-ci-cd-github/
npx angular-cli-ghpages --dir=dist/browser

https://mboup1.github.io/app-ci-cd-github-angular/




<!-- ng build --output-path=dist/app-test-ci-cd-github --base-href=/app-test-ci-cd-github/
npx angular-cli-ghpages --dir=dist/app-test-ci-cd-github -->
