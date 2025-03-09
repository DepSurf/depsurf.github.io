# Function: <code>kill_dev_dax</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586446480,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:355",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586446480,
      "name": "kill_dev_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586594416,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:355",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586594416,
      "name": "kill_dev_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587382845,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:363",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587380416,
      "name": "kill_dev_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587450018,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:360",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587440864,
      "name": "kill_dev_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587331694,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:361",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587322640,
      "name": "kill_dev_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587898520,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:359",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587889488,
      "name": "kill_dev_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589248081,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:381",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589238496,
      "name": "kill_dev_dax",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590807585,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:381",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590797312,
      "name": "kill_dev_dax",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591148669,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:395",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591138832,
      "name": "kill_dev_dax",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591494662,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:396",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591484528,
      "name": "kill_dev_dax",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499478848,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:355",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499478848,
      "name": "kill_dev_dax",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231951716,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:355",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231951716,
      "name": "kill_dev_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292757952,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:355",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292757952,
      "name": "kill_dev_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276697144,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:355",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276697144,
      "name": "kill_dev_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586284896,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:355",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586284896,
      "name": "kill_dev_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586122384,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:355",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax",
        "drivers/dax/device.c:dev_dax_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586122384,
      "name": "kill_dev_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586542384,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:355",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586542384,
      "name": "kill_dev_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void kill_dev_dax(struct dev_dax * dev_dax)
```

```json
{
  "name": "kill_dev_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586654160,
      "name": "kill_dev_dax",
      "external": true,
      "loc": "drivers/dax/bus.c:355",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:__devm_create_dev_dax",
        "drivers/dax/bus.c:unregister_dev_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586654160,
      "name": "kill_dev_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void kill_dev_dax(struct dev_dax * dev_dax)
```
</details>
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
