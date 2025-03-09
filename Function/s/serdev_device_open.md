# Function: <code>serdev_device_open</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585174384,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:118",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585174384,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585410848,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:143",
      "file": "drivers/tty/serdev/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585409744,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585533936,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:146",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533936,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585755488,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:146",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585755488,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585897744,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:146",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585897744,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586634128,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:147",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586634128,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586743152,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:147",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586743152,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586626752,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:147",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626752,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587173360,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:147",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587173360,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588485616,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:147",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588485616,
      "name": "serdev_device_open",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589921648,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:147",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589921648,
      "name": "serdev_device_open",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590230912,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:147",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590230912,
      "name": "serdev_device_open",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590571744,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:149",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590571744,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498716552,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:146",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498716552,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231343712,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:146",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231343712,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291865184,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:146",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291865184,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276228760,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:146",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276228760,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585658736,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:146",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585658736,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585848144,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:146",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585848144,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int serdev_device_open(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585955760,
      "name": "serdev_device_open",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:146",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585955760,
      "name": "serdev_device_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int serdev_device_open(struct serdev_device * serdev)
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
int serdev_device_open(struct serdev_device * serdev)
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
