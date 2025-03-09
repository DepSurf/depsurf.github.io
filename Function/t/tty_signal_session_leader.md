# Function: <code>tty_signal_session_leader</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583962141,
      "name": "tty_signal_session_leader",
      "external": false,
      "loc": "drivers/tty/tty_io.c:615",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:__tty_hangup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584294959,
      "name": "tty_signal_session_leader",
      "external": false,
      "loc": "drivers/tty/tty_io.c:622",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:__tty_hangup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584477023,
      "name": "tty_signal_session_leader",
      "external": false,
      "loc": "drivers/tty/tty_io.c:622",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:__tty_hangup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584601072,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:190",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601072,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585013520,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:191",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585013520,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585247680,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:191",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585247680,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585367088,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:191",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585367088,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585580768,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:191",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585580768,
      "name": "tty_signal_session_leader",
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585721680,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:191",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585721680,
      "name": "tty_signal_session_leader",
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586452720,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:191",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586452720,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586567136,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:193",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586567136,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586451296,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:196",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586451296,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586978240,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:196",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586978240,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588275168,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:196",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588275168,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589690352,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:196",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589690352,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589994992,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:196",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589994992,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590333392,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:196",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590333392,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498415200,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:191",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498415200,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231086212,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:191",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231086212,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291599488,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:191",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291599488,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276071610,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:191",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276071610,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585482704,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:191",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585482704,
      "name": "tty_signal_session_leader",
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585352624,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:191",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585352624,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585672080,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:191",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672080,
      "name": "tty_signal_session_leader",
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
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```

```json
{
  "name": "tty_signal_session_leader",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585780192,
      "name": "tty_signal_session_leader",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:191",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585780192,
      "name": "tty_signal_session_leader",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int tty_signal_session_leader(struct tty_struct * tty, int exit_session)
```
</details>
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
