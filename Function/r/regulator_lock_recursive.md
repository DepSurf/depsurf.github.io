# Function: <code>regulator_lock_recursive</code>

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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585283696,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:274",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585283696,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585491840,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:256",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585491840,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585636544,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:256",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585636544,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586353920,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:259",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586353920,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586471600,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:258",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586471600,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586355392,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:258",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586355392,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586888240,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:248",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586888240,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588177744,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:249",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588177744,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589571200,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:249",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589571200,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589873888,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:314",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589873888,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590211776,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:316",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590211776,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498291712,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:256",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498291712,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230977868,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:256",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230977868,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291462272,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:256",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291462272,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275990390,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:256",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275990390,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585397696,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:256",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585397696,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585267616,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:256",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585267616,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585586944,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:256",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585586944,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_recursive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585695072,
      "name": "regulator_lock_recursive",
      "external": false,
      "loc": "drivers/regulator/core.c:256",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585695072,
      "name": "regulator_lock_recursive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
int regulator_lock_recursive(struct regulator_dev * rdev, struct regulator_dev * * new_contended_rdev, struct regulator_dev * * old_contended_rdev, struct ww_acquire_ctx * ww_ctx)
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
