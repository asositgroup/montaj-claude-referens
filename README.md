# montaj-claude-referens (private)

[montaj-claude](https://github.com/asositgroup/montaj-claude) uchun shaxsiy qism — public qilib bo'lmaydigan fayllar:
- `VideoMontaj/styles/*/referens/` — uslub pasportlarining referens video va kadr varaqlari (boshqa mualliflar kontenti);
- `VideoMontaj/videos/c0038-500-dollar/` — namuna loyihaning `video.mp4`, render, SFX va musiqasi (Mixkit).

Papkalar `~/VideoMontaj` tuzilmasida — avval asosiy reponi o'rnating (`ornatish.sh` / `ornatish.cmd`), keyin shu reponi ustiga qo'shing.

**Mac:**
```bash
git clone https://github.com/asositgroup/montaj-claude-referens.git ~/montaj-claude-referens
rsync -a ~/montaj-claude-referens/VideoMontaj/ ~/VideoMontaj/
```

**Windows (PowerShell):**
```powershell
git clone https://github.com/asositgroup/montaj-claude-referens.git "$env:USERPROFILE\montaj-claude-referens"
robocopy "$env:USERPROFILE\montaj-claude-referens\VideoMontaj" "$env:USERPROFILE\VideoMontaj" /E
```
