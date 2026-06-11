# PoC-EpicOnlineFix
Online Fix for Epic Games Launcher, currently i only tested on Hot Wheels Unleashed 2: Turbocharged
All the flow and how it works its exactly same just like Online-Fix.me

# Features:
- DLC Catalog — `UnlockAllDLC`, explicit `OwnedItems` / `Entitlements` lists, optional per-game `manifests/<App>/ecom.toml` overlay
- Patch EOS SDK on disk
- **EOS hooks**
  - `EOS_Auth_Login` — passthrough with exchange-code credential substitution
  - `EOS_Ecom_QueryOwnership` — synthesised "Owned" answers, no Epic catalog call
  - `EOS_AntiCheatClient_*` — fake-healthy responses, no EAC service contact
- Manifest Spoofer
- EAC & EOS Anti-Cheat Fake Process Handler
- Configuration generation for each game
- Many more

# Future:
- Working Achievements

# Preview:
Launcher & In Game:
<img width="1223" height="639" alt="image" src="https://github.com/user-attachments/assets/673827bd-c8b0-400b-bca0-eb1f349e45b6" />
<img width="2560" height="1384" alt="FxMItRl6of" src="https://github.com/user-attachments/assets/d37d735e-77cc-4ac1-bf1a-b4f35465f01a" />
<img width="2560" height="1440" alt="hotwheels2-Win64-Shipping_d2EkLiyjvE" src="https://github.com/user-attachments/assets/81c02432-3884-4243-b7f6-abdf0f5d6f78" />
<img width="2560" height="1440" alt="hotwheels2-Win64-Shipping_nefBRQHl9L" src="https://github.com/user-attachments/assets/a2d8ba31-1b8c-43c5-8be2-962732ed7c01" />
<img width="2560" height="1440" alt="hotwheels2-Win64-Shipping_pQnyGnZvBo" src="https://github.com/user-attachments/assets/80c23a7c-007e-4278-b37e-098ea8c20a49" />
