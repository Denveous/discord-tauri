# Discord Tauri

Discord web in a small Tauri wrapper.

This is for people who want Discord without the Electron app constantly updating and sitting on extra RAM. It loads `https://discord.com/app` and injects Vencord's browser build.

## Build

```powershell
pnpm install
pnpm build
```

Builds and installers land under:

```text
src-tauri\target\release\bundle
```

## Notes

This is an unofficial Discord wrapper. Discord, Vencord, and Tauri are separate projects with their own licenses and policies.

RPC compatibility is experimental and intentionally minimal.

## License

MIT
