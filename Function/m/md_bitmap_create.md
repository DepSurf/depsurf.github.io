# Function: <code>md_bitmap_create</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1809",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:get_bitmap_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587439206,
      "name": "md_bitmap_create.cold.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071587435328,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2083
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1812",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:get_bitmap_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587711798,
      "name": "md_bitmap_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587708656,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1018
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1812",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:get_bitmap_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587916102,
      "name": "md_bitmap_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587912960,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1018
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1807",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588767652,
      "name": "md_bitmap_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588764720,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1808",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591591604,
      "name": "md_bitmap_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588785184,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1810",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591534713,
      "name": "md_bitmap_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588671056,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1810",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592647550,
      "name": "md_bitmap_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071589349264,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1811",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594532581,
      "name": "md_bitmap_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071590823008,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592510704,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1811",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592510704,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592941184,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1877",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592941184,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593690928,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1881",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593690928,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 701
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501144472,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1812",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:get_bitmap_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501144472,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1100
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233658496,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1812",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:get_bitmap_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233658496,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1032
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294651408,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1812",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:get_bitmap_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294651408,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1312
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277857466,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1812",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:get_bitmap_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277857466,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 888
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1812",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:get_bitmap_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587547078,
      "name": "md_bitmap_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587543936,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1018
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1812",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:get_bitmap_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587315174,
      "name": "md_bitmap_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587312032,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1018
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1812",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:get_bitmap_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587872246,
      "name": "md_bitmap_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587869104,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1018
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
```

```json
{
  "name": "md_bitmap_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_create",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1812",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_run",
        "drivers/md/md-bitmap.c:get_bitmap_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587987358,
      "name": "md_bitmap_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071587984144,
      "name": "md_bitmap_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1063
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
struct bitmap * md_bitmap_create(struct mddev * mddev, int slot)
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
