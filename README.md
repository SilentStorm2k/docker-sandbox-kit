## Initial sandbox command to run (inside some scoped folder):

```sh
sbx run pi --kit "git+https://github.com/SilentStorm2k/docker-sandbox-kit.git#dir=pi" --kit "git+https://github.com/SilentStorm2k/docker-sandbox-kit.git#dir=pi-lmstudio" --kit "git+https://github.com/SilentStorm2k/docker-sandbox-kit.git#dir=skills"
```

## Subsequent sandbox commands:

```sh
sbx run pi-<folder_name_of_created_sandbox>
```
