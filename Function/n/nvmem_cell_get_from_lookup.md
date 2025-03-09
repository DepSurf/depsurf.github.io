# Function: <code>nvmem_cell_get_from_lookup</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587785056,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:951",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785056,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
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
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588089840,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:700",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588089840,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588295664,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:697",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588295664,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589177232,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:956",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589177232,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589172768,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:1134",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589172768,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589066944,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:1137",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589066944,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589785360,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:1148",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589785360,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591297296,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:1151",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591297296,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593048368,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:1149",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593048368,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593500576,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:1301",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593500576,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594250624,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:1312",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594250624,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501818816,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:697",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234337448,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:697",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295216332,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:697",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278165542,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:697",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587899424,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:697",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899424,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587618704,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:697",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587618704,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588232720,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:697",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588232720,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```

```json
{
  "name": "nvmem_cell_get_from_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588368048,
      "name": "nvmem_cell_get_from_lookup",
      "external": false,
      "loc": "drivers/nvmem/core.c:697",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588368048,
      "name": "nvmem_cell_get_from_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct nvmem_cell * nvmem_cell_get_from_lookup(struct device * dev, const char * con_id)
```
</details>
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
