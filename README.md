# Репозиторий с шаблонами проектов для tempro
# Repository Structure

## 🏷 Версионирование

### Формат тегов
<язык>/v<MAJOR>.<MINOR>.<PATCH>

Примеры:
- `go/v1.2.0`
- `python/v0.5.3`
- `js/v2.1.0-rc.1`

### Правила SemVer для каждого языка
| Версия    | Описание                          |
|-----------|-----------------------------------|
| `MAJOR`   | Breaking Версия языка                 |
| `MINOR`   | Major Версия зависимостей, новые шаблоны/шарды            |
| `PATCH`   | Исправления ошибок, изменения существующих шаблонов                |

## 📄 index.json (main branch)
```json
{
  "meta": {
    "updated_at": "2024-03-20T12:00:00Z",
    "signature": "cosign:sha256:a1b2c3..."
  },
  "templates": {
    "go": {
      "latest": "v1.2.0",
      "versions": [
        {
          "tag": "go/v1.2.0",
          "release_date": "2024-03-15",
          "checksum": "sha256:9f86d...",
          "changelog": "https://templates.com/go/CHANGELOG.md#v1.2.0"
        }
      ]
    }
  }
}
```
