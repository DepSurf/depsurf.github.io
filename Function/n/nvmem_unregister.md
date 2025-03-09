# Function: <code>nvmem_unregister</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586862128,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:527",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/nvmem.c:rtc_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586862128,
      "name": "nvmem_unregister",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587349920,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:529",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/nvmem.c:rtc_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587349920,
      "name": "nvmem_unregister",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587653360,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:542",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/nvmem.c:rtc_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587653360,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587786613,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:728",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587786560,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588091893,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:474",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588090416,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588297717,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:471",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296240,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589177893,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:711",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589177808,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589173429,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:886",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589173344,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589067605,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:889",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589067520,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589786021,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:900",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589785936,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591297173,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:905",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_unregister",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591297040,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593048229,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:903",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_unregister",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593048080,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593500165,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:1053",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_unregister",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593500016,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594256485,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:1064",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_unregister",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594256288,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501816616,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:471",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501816616,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234335472,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:471",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mtd/mtdcore.c:del_mtd_device",
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234335472,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295213472,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:471",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295213472,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278163580,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:471",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278163490,
      "name": "nvmem_unregister",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587901477,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:471",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587900000,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587620757,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:471",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587619280,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588234773,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:471",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588233296,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void nvmem_unregister(struct nvmem_device * nvmem)
```

```json
{
  "name": "nvmem_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588370101,
      "name": "nvmem_unregister",
      "external": true,
      "loc": "drivers/nvmem/core.c:471",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588368624,
      "name": "nvmem_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int nvmem_unregister(struct nvmem_device * nvmem)
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
