# Function: <code>ext4_mb_prefetch_fini</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ext4_mb_prefetch_fini(struct super_block * sb, ext4_group_t group, unsigned int nr)
```

```json
{
  "name": "ext4_mb_prefetch_fini",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583154464,
      "name": "ext4_mb_prefetch_fini",
      "external": true,
      "loc": "fs/ext4/mballoc.c:2252",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/super.c:ext4_run_li_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154464,
      "name": "ext4_mb_prefetch_fini",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void ext4_mb_prefetch_fini(struct super_block * sb, ext4_group_t group, unsigned int nr)
```

```json
{
  "name": "ext4_mb_prefetch_fini",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583179680,
      "name": "ext4_mb_prefetch_fini",
      "external": true,
      "loc": "fs/ext4/mballoc.c:2591",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/super.c:ext4_run_li_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583179680,
      "name": "ext4_mb_prefetch_fini",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void ext4_mb_prefetch_fini(struct super_block * sb, ext4_group_t group, unsigned int nr)
```

```json
{
  "name": "ext4_mb_prefetch_fini",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_prefetch_fini",
      "external": true,
      "loc": "fs/ext4/mballoc.c:2609",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/super.c:ext4_run_li_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592263988,
      "name": "ext4_mb_prefetch_fini.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583521504,
      "name": "ext4_mb_prefetch_fini",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
void ext4_mb_prefetch_fini(struct super_block * sb, ext4_group_t group, unsigned int nr)
```

```json
{
  "name": "ext4_mb_prefetch_fini",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_prefetch_fini",
      "external": true,
      "loc": "fs/ext4/mballoc.c:2606",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/super.c:ext4_run_li_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594045727,
      "name": "ext4_mb_prefetch_fini.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071584054720,
      "name": "ext4_mb_prefetch_fini",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void ext4_mb_prefetch_fini(struct super_block * sb, ext4_group_t group, unsigned int nr)
```

```json
{
  "name": "ext4_mb_prefetch_fini",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_prefetch_fini",
      "external": true,
      "loc": "fs/ext4/mballoc.c:2569",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/super.c:ext4_run_li_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596078646,
      "name": "ext4_mb_prefetch_fini.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071584687008,
      "name": "ext4_mb_prefetch_fini",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
void ext4_mb_prefetch_fini(struct super_block * sb, ext4_group_t group, unsigned int nr)
```

```json
{
  "name": "ext4_mb_prefetch_fini",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584912416,
      "name": "ext4_mb_prefetch_fini",
      "external": true,
      "loc": "fs/ext4/mballoc.c:2739",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/super.c:ext4_run_li_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584912416,
      "name": "ext4_mb_prefetch_fini",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void ext4_mb_prefetch_fini(struct super_block * sb, ext4_group_t group, unsigned int nr)
```

```json
{
  "name": "ext4_mb_prefetch_fini",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585145344,
      "name": "ext4_mb_prefetch_fini",
      "external": true,
      "loc": "fs/ext4/mballoc.c:2763",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/super.c:ext4_run_li_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585145344,
      "name": "ext4_mb_prefetch_fini",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void ext4_mb_prefetch_fini(struct super_block * sb, ext4_group_t group, unsigned int nr)
```
</details>
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
