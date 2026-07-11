# webOS Homebrew Repo

Небольшой custom-репозиторий для [Homebrew Channel](https://github.com/webosbrew/webos-homebrew-channel) на LG webOS TV.

Сейчас в списке:

- **[KPuppy](https://github.com/twttr/KPuppy)** — клиент KinoPub для webOS

## Как добавить на телевизор

1. Откройте **Homebrew Channel** → **Settings**.
2. Добавьте **Custom Repository** с этим URL:

```text
https://raw.githubusercontent.com/<GITHUB_USER>/webos-homebrew-repo/main/apps.json
```

3. Вернитесь в список приложений, найдите **KPuppy** и установите.

Root **не требуется**.

## Обновления

`manifestUrl` указывает на `releases/latest` upstream-проекта KPuppy, поэтому при выходе новой версии Homebrew Channel сможет предложить обновление.
