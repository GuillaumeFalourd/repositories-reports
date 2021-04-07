# repositories-reports

[![1 - Reports Generator](https://github.com/GuillaumeFalourd/repositories-reports/actions/workflows/1-reports-generator.yml/badge.svg)](https://github.com/GuillaumeFalourd/repositories-reports/actions/workflows/1-reports-generator.yml)

[![2 - Alternative Reports Generator](https://github.com/GuillaumeFalourd/repositories-reports/actions/workflows/2-alternative-reports-generator.yml/badge.svg)](https://github.com/GuillaumeFalourd/repositories-reports/actions/workflows/2-alternative-reports-generator.yml)

![Title](/docs/repository-title.png)

Repository with weekly insights reports for the Github user personal repositories

This repository uses [Github Actions](https://github.com/features/actions) and [Ritchie CLI](https://ritchiecli.io).

## Sample of generated reports

This repository will gather on the `/reports` directory weekly reports with the following datas:

### 🕵️ Insights from last 14 days

- Views 👀
- Uniques 👁
- Clones 📥

### 🕵️ Insights from the moment the automation is executed 

- Contributores 👥
- Forks 🔀
- Stars ⭐️
- Watchers 🎥

Reports will look like this one:

![Sample](/docs/report-sample.png)

## ♻️ Want to get your repo-reports?

- **Create a new repository** (you can clone or fork this one)

- Add 2 secrets on the new repository ([here is a reference](https://docs.github.com/en/actions/reference/encrypted-secrets)):
  - a secret `ACCESS_TOKEN` (you can create one [here](https://github.com/settings/tokens))
  - a secret `USERNAME_CREDENTIAL` with your Github User account (`GuillaumeFalourd` in my case)
