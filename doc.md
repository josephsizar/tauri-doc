## creating new vite App With bun
```sh
bun create vite@latest
```
**choose react and typescript**

🚀 great you are on the moon

```sh
bun install

bun run dev
```
# That is Working 🔥
# you need to add tauri

```sh
bun add --dev @tauri-apps/cli
```

```sh
bunx tauri init
```
## some changes in src-tauri/tauri.config.json
```json
"distDir":  from "../build" to "../dist"
"identifier": from "com.tauri.dev" to "com.example.tauri"
```

## after that open terminal

```sh
bun run build
```
## start dev for tauri
```sh
bunx tauri dev
```





