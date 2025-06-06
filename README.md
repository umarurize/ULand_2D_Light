![header](https://capsule-render.vercel.app/api?type=venom&height=150&color=gradient&text=ULand%202D%20Light&fontColor=0:8871e5,100:b678c4&fontSize=50&desc=A%20light%202D%20land%20system%20with%20rich%20features.&descAlignY=80&descSize=20&animation=fadeIn)

****

<code><a href="https://github.com/umarurize/ULand_2D_Light"><img height="25" src="https://github.com/umarurize/ULand_2D_Light/blob/master/logo/ULand.png" alt="ULand 2D Light" /></a>&nbsp;ULand 2D Light</code>

![Total Git clones](https://img.shields.io/badge/dynamic/json?label=Total%20Git%20clones&query=$&url=https://cdn.jsdelivr.net/gh/umarurize/ULand_2D_Light@master/clone_count.txt&color=brightgreen)
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/umarurize/ULand_2D_Light/total)

### :bell:Introductions
<details>
<summary>Rich features</summary>
    
- [x] Land create
- [x] Land info
- [x] Land buy
- [x] Land sell
- [x] Land member add
- [x] Land member remove
- [x] Land tp
- [x] Land security settings
- [x] Land tp setting
- [x] Land ownership transfer
- [x] Land public
- [x] Land manage (operators)

</details>

<details>
<summary>Ultra protection</summary>
    
- [x] Fire protection
- [x] Explosion protection
- [x] Wither protection
- [x] Block interaction
- [x] Block breaking
- [x] Entity protection
- [x] Player attacks

</details>

* **Full GUI:** Beautiful GUI forms for easy operation rather than commands.
* **Hot reload support:** Operators can edit/update `config.json` or `land.json` in game directly.
* **Localized languages support**

### :hammer:Installation
[Required pre-plugin] [UMoney](https://github.com/umarurize/UMoney)

[Optional pre-plugin] ZX_UI

Put `.whl` file into the endstone plugins folder, and then start the server. Enter the command `/utp` to call out the main form.

### :computer:Download
Now, you can get the release version form this repo or <code><a href="https://www.minebbs.com/resources/uland-2d-light-gui.9967/"><img height="20" src="https://github.com/umarurize/umaru-cdn/blob/main/images/minebbs.png" alt="Minebbs" /></a>&nbsp;Minebbs</code>.

### :file_folder:File structure
```
Plugins/
├─ uland/
│  ├─ config.json
│  ├─ land.json
│  ├─ lang/
│  │  ├─ zh_CN.json
│  │  ├─ en_US.json
```

### :pencil:Configuration
ULand allows operators or players to edit/update relevant settings through GUI forms with ease, here are just simple explanations for relevant configurations.

`config.json`
```json5
{
    "land_buy_price": 20,  // the unit price of the purchase of the land (per square block)
    "land_create_timeout": 60,  // the max time in seconds taken to create a land
    "max_area": 40000,  // the max legal area of a single land
    "max_land_per_player": 25,  // the max number of lands each player can have
    "is_land_sell_rate_on": true  // whether to enable the floating price (0.0~2.0) of land sell
    "land_sell_cool_down_timeout": 3 // land sell cooldown in days (When the previous configuration is set to true)
}
```

`land.json`
```json5
{
"DENHJE": {
        "DENHJE的领地": {
            "dimension": "Overworld",
            "range": "(-7977, ~, 2323) - (-8017, ~, 2275)",
            "area": 1920,
            "land_expense": 38400,
            "land_buy_time": "2025-02-24",
            "land_tp": [
                -7977,
                67,
                2323
            ],
            "permissions": [
                "xubaobao0310"
            ],
            "public_land": false,
            "fire_protect": true,
            "explode_protect": true,
            "anti_wither_enter": true,
            "anti_right_click_block": true,
            "anti_break_block": true,
            "anti_right_click_entity": true,
            "anti_player_attack": true
        }
    }
}
```

### :globe_with_meridians:Languages
- [x] `zh_CN`
- [x] `en_US`

Off course you can add your mother language to ULand, just creat `XX_XX.json` (such as `ja_JP.json`) and translate value with reference to `en_US.json`.

You can also creat a PR to this repo to make your mother language one of the official languages of ULand.

### :camera:Screenshots
You can view related screenshots of ULand from images folder of this repo.

### :fire:Operation document
you can go to the operation document folder of this repo to learn how to use ULand.

<div style="width: 100%; text-align: center;">
  <img src="https://github.com/umarurize/ULand_2D_Light/blob/master/logo/ULand2.png" style="max-width: 100%; height: auto;">
</div>

![](https://img.shields.io/badge/language-python-blue.svg) [![GitHub License](https://img.shields.io/github/license/umarurize/UTP)](LICENSE)


