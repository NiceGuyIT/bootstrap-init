# Bootstrap init

Bootstrap the onboarding of a computer.

1. Start Syncthing

```bash
cd syncthing
docker compose up --detach
```

2. Connect to Syncthing to the `bootstrap-init` folder
3. Start Nebula from the `bootstrap-init` folder.

```bash
cd bootstrap-init/work-01
docker compose up --detach
```
