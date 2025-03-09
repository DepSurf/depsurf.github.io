# Function: <code>sr_do_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584878768,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:185",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_fake_playtrkind",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength",
        "drivers/scsi/sr_vendor.c:sr_cd_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584878768,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585241072,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:185",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_ioctl.c:sr_fake_playtrkind",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241072,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 605
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585440896,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:185",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_ioctl.c:sr_fake_playtrkind",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585440896,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 605
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585525040,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:185",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_ioctl.c:sr_fake_playtrkind",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585525040,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585956672,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_ioctl.c:sr_fake_playtrkind",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585956672,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586204896,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586204896,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586345616,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586345616,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586589136,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586589136,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586736576,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586736576,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587540800,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_ioctl.c:sr_fake_playtrkind",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587540800,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587607392,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_ioctl.c:sr_fake_playtrkind",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587607392,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587488592,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:182",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_ioctl.c:sr_fake_playtrkind",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587488592,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588064784,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:182",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_ioctl.c:sr_fake_playtrkind",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588064784,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589429136,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:188",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_ioctl.c:sr_fake_playtrkind",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589429136,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591005888,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:188",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_ioctl.c:sr_fake_playtrkind",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591005888,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591359568,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:188",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_ioctl.c:sr_fake_playtrkind",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591359568,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591709680,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:188",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_ioctl.c:sr_fake_playtrkind",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591709680,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499647736,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499647736,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232102108,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_ioctl.c:sr_fake_playtrkind",
        "drivers/scsi/sr_ioctl.c:sr_read_tocentry",
        "drivers/scsi/sr_ioctl.c:sr_read_tochdr",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232102108,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292971568,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292971568,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276830428,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276830428,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586427056,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586427056,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586303312,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586303312,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586691136,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586691136,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD * cd, struct packet_command * cgc)
```

```json
{
  "name": "sr_do_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586797168,
      "name": "sr_do_ioctl",
      "external": true,
      "loc": "drivers/scsi/sr_ioctl.c:186",
      "file": "drivers/scsi/sr_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_packet",
        "drivers/scsi/sr_ioctl.c:sr_is_xa",
        "drivers/scsi/sr_ioctl.c:sr_audio_ioctl",
        "drivers/scsi/sr_ioctl.c:sr_select_speed",
        "drivers/scsi/sr_ioctl.c:sr_get_mcn",
        "drivers/scsi/sr_ioctl.c:sr_tray_move",
        "drivers/scsi/sr_vendor.c:sr_cd_check",
        "drivers/scsi/sr_vendor.c:sr_set_blocklength"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586797168,
      "name": "sr_do_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
