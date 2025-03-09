# Function: <code>nvm_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int nvm_register(struct request_queue * q, char * disk_name, struct nvm_dev_ops * ops)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584364688,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:539",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584364688,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1372
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
int nvm_register(struct request_queue * q, char * disk_name, struct nvm_dev_ops * ops)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584700480,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:661",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584700480,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1449
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
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584887792,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:778",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584887792,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1350
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
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584978224,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1073",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584978224,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1601
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
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585399440,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1079",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585399440,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1619
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:929",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585642720,
      "name": "nvm_register.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585637728,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 787
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585772144,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1141",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585772058,
      "name": "nvm_register.cold.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071585767088,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1150",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586003875,
      "name": "nvm_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    },
    {
      "addr": 18446744071585999424,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1179",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586151026,
      "name": "nvm_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    },
    {
      "addr": 18446744071586146592,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1178",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586907869,
      "name": "nvm_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071586904208,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1173",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591483793,
      "name": "nvm_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071586989072,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1173",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591427749,
      "name": "nvm_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071586874416,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498939544,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1179",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498939544,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231511100,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1179",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231511100,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292076208,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1179",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292076208,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276324384,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1179",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276324384,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1179",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/lightnvm.c:nvme_nvm_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585911394,
      "name": "nvm_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    },
    {
      "addr": 18446744071585906960,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1179",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586101042,
      "name": "nvm_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    },
    {
      "addr": 18446744071586096608,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int nvm_register(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvm_register",
      "external": true,
      "loc": "drivers/lightnvm/core.c:1179",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586209650,
      "name": "nvm_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    },
    {
      "addr": 18446744071586205216,
      "name": "nvm_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nvm_dev * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param removed. </b>
<code>char * disk_name</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nvm_dev_ops * ops</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int nvm_register(struct nvm_dev * dev)
```
</details>
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
int nvm_register(struct nvm_dev * dev)
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
