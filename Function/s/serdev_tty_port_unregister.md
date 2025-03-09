# Function: <code>serdev_tty_port_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_tty_port_unregister",
      "external": false,
      "loc": "include/linux/serdev.h:319",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585178784,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:278",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585178784,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585414624,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:306",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585414624,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585538224,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:306",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585538224,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585758272,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:306",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585758272,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585900480,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:304",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585900480,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586638896,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:304",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586638896,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586747696,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:304",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586747696,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586631184,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:304",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586631184,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587177808,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:304",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587177808,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588490688,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:304",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588490688,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589927440,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:304",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589927440,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590236800,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:316",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590236800,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590577808,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:317",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590577808,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498719248,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:304",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498719248,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231346004,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:304",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231346004,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291871664,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:304",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291871664,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276232770,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:304",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276232770,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585661472,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:304",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585661472,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_tty_port_unregister",
      "external": false,
      "loc": "include/linux/serdev.h:324",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585850880,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:304",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585850880,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int serdev_tty_port_unregister(struct tty_port * port)
```

```json
{
  "name": "serdev_tty_port_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585958496,
      "name": "serdev_tty_port_unregister",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:304",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_unregister_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585958496,
      "name": "serdev_tty_port_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int serdev_tty_port_unregister(struct tty_port * port)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int serdev_tty_port_unregister(struct tty_port * port)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
