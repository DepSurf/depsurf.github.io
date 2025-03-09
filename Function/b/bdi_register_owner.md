# Function: <code>bdi_register_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580711584,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:828",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580711584,
      "name": "bdi_register_owner",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580777408,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:834",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580777408,
      "name": "bdi_register_owner",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580814800,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:897",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814800,
      "name": "bdi_register_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580904928,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:912",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580904928,
      "name": "bdi_register_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581040752,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:910",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581040752,
      "name": "bdi_register_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581118128,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:913",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118128,
      "name": "bdi_register_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581182968,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:900",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581187468,
      "name": "bdi_register_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071581182912,
      "name": "bdi_register_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581241184,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:980",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581241184,
      "name": "bdi_register_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492639064,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:980",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492639064,
      "name": "bdi_register_owner",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226481980,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:980",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226481980,
      "name": "bdi_register_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285956032,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:980",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285956032,
      "name": "bdi_register_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272655832,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:980",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272655832,
      "name": "bdi_register_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581210032,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:980",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210032,
      "name": "bdi_register_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581156784,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:980",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581156784,
      "name": "bdi_register_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581201232,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:980",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581201232,
      "name": "bdi_register_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```

```json
{
  "name": "bdi_register_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581264528,
      "name": "bdi_register_owner",
      "external": true,
      "loc": "mm/backing-dev.c:980",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264528,
      "name": "bdi_register_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int bdi_register_owner(struct backing_dev_info * bdi, struct device * owner)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
