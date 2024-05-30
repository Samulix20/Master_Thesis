# TFM Thesis

## Config

Requires the following repo secrets configured
```
OVERLEAF_TOKEN = "Overleaf git token, generated at https://www.overleaf.com/user/settings"
OVERLEAF_PROJECT_ID = "Can be obtained from project url https://es.overleaf.com/project/{id}"
USER_EMAIL = "User email for git identity"
USER_NAME = "User name for git identity"
GIT_TOKEN = "Github personal access token, can be created at https://github.com/settings/apps"
```

## Automatic overleaf sync

The `overleaf_sync.yml` workflows runs every dat at 8:00 and pulls changes from overleaf. This can be edited.

## Push to overleaf

Pushes on `main` branch to paths of `root` directory trigger the `overleaf_push.yml` workflow which pushes the changes also to Overleaf 
