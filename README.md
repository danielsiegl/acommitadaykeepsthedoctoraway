# a commit a day keeps the doctor away
Sample Repo to create a commit every day using GitHub Actions!
To achieve that I created a simple GitHub Action that does an empty commit triggered by a cron schedule.

See: [/.github/workflows/croncommit.yml](https://github.com/danielsiegl/acommitadaykeepsthedoctoraway/blob/main/.github/workflows/croncommit.yml)

Feel free to fork this - but you need to set 3 Repository Level Secrets:

acommitadaykeepsthedoctoraway/settings/secrets/actions

!(images/secrets.png)

- GITEMAIL
- GITNAME
- PAT (a classic Token)

