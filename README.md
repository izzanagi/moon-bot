### MOON-BOT
> Script ini gratis, menggunakan 99% api dari [AlyaChan-APIs](https://api.alyachan.pro)

### Yang dibutuhkan
- [x] Server
- [x] WhatsApp
- [x] ffmpeg
- [x] imagemagick
- [x] Apikey

### Setting di config.js
```Javascript
global.owner = [
    ['6285755516792'],
    ['6285755125986'],
    ['6281252848955', 'owner', true]
]

global.mods = ['0']
global.prems = ['6285755516792', '6285755125986']

global.set = {
  link: 'Belum ada kak, hehe'
  wm: ' Xenzira ʙᴏᴛ ᴏɴʟɪɴᴇ',
  footer: 'ᴡʜᴀᴛꜱᴀᴘᴘ ʙᴏᴛ ʙʏ Xenzira',
  packname: 'Sticker By Xenzira-Bot',
  author: '@naando.io'
}

global.multiplier = 7
global.max_upload = 70
global.intervalmsg = 1800
```

### Plugins
```Javascript
let handler = async(m, {
  conn,
  usedPrefix,
  command,
  args,
  text,
  users,
  isOwner,
  isPrem
}) => {
  try {
    // di isi sembarang cok
  } catch {
    console.log(e)
    return conn.reply(m.chat, Func.jsonFormat(e), m)
  }
}
handler.help = ['command'] // anunya
handler.tags = ['category'] // category nya
handler.command = /^(command)$/i // command nya
handler.group = Boolean // Untuk Group
handler.limit = Boolean // Menggunakan Limit
handler.game = Boolean // fitur game
handler.rpg = Boolean // fitur rpg
handler.owner = Boolean // khusus owner
handler.admin = Boolean // khusus admin
handler.botAdmin = Boolean // bot harus menjadi admin!
handler.premium = Boolean // khusus use premium!
handler.private = Boolean // khusus chat pribadi!
```

### Instalasi & Run
```
$ npm install
$ npm start
```

menggunakan PM2

```
$ npm install pm2 -g
$ npm install
$ pm2 start index.js && pm2 save && pm2 logs
```

### Argumen `node . [--options]`

Contoh : node . --autread

### `--self`

Mengabaikan yang lain

### `--autoread`

autored chat

### `--db`

contoh : `node . --db 'mongodburi'`
Untuk menghubungkan ke database, pakai mongodb

### `--pairing`

menggunakan kode


[![Nurutomo](https://github.com/Nurutomo.png?size=100)](https://github.com/Nurutomo) | [![Nando35](https://github.com/Nando35.png?size=100)](https://github.com/Nando35)
----|----
[Nurutomo](https://github.com/Nurutomo) | [Nando35](https://github.com/Nando35)
 Penulis / Pencipta | Penerjemah
