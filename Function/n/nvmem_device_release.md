# Function: <code>nvmem_device_release</code>

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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587783728,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:707",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_put",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release",
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587783728,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588088576,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:453",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588088576,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588294496,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:450",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588294496,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589176944,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:691",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589176944,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589172480,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:866",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589172480,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589066656,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:869",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589066656,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589785072,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:880",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589785072,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591296608,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:885",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591296608,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593047568,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:883",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593047568,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593499536,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:1032",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593499536,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594250394,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:1043",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501816504,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:450",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501816504,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234335364,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:450",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234335364,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295213248,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:450",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295213248,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278163372,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:450",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278163372,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587898256,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:450",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587898256,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587617536,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:450",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587617536,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588231552,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:450",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588231552,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void nvmem_device_release(struct kref * kref)
```

```json
{
  "name": "nvmem_device_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588366880,
      "name": "nvmem_device_release",
      "external": false,
      "loc": "drivers/nvmem/core.c:450",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588366880,
      "name": "nvmem_device_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void nvmem_device_release(struct kref * kref)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void nvmem_device_release(struct kref * kref)
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
