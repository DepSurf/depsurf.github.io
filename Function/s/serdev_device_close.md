# Function: <code>serdev_device_close</code>

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
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585174448,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:129",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585174448,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585409861,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:154",
      "file": "drivers/tty/serdev/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585409808,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585534128,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:174",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585534128,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585753968,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:174",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585753968,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585896192,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:174",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585896192,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586636709,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:175",
      "file": "drivers/tty/serdev/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586634288,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586745733,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:175",
      "file": "drivers/tty/serdev/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586743312,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586629237,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:175",
      "file": "drivers/tty/serdev/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626912,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587175877,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:175",
      "file": "drivers/tty/serdev/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587173520,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588488437,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:175",
      "file": "drivers/tty/serdev/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588485776,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589924901,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:175",
      "file": "drivers/tty/serdev/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589921824,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590234165,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:175",
      "file": "drivers/tty/serdev/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590231088,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590571920,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:177",
      "file": "drivers/tty/serdev/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590571920,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498713664,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:174",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498713664,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231341784,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:174",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231341784,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291865440,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:174",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291865440,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276228886,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:174",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276228886,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585657184,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:174",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585657184,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585846592,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:174",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585846592,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void serdev_device_close(struct serdev_device * serdev)
```

```json
{
  "name": "serdev_device_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585954208,
      "name": "serdev_device_close",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:174",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/core.c:devm_serdev_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585954208,
      "name": "serdev_device_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void serdev_device_close(struct serdev_device * serdev)
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
void serdev_device_close(struct serdev_device * serdev)
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
