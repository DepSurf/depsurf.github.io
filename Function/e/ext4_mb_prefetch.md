# Function: <code>ext4_mb_prefetch</code>

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
ext4_group_t ext4_mb_prefetch(struct super_block * sb, ext4_group_t group, unsigned int nr, int * cnt)
```

```json
{
  "name": "ext4_mb_prefetch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583154048,
      "name": "ext4_mb_prefetch",
      "external": true,
      "loc": "fs/ext4/mballoc.c:2201",
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
      "addr": 18446744071583154048,
      "name": "ext4_mb_prefetch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
ext4_group_t ext4_mb_prefetch(struct super_block * sb, ext4_group_t group, unsigned int nr, int * cnt)
```

```json
{
  "name": "ext4_mb_prefetch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583179248,
      "name": "ext4_mb_prefetch",
      "external": true,
      "loc": "fs/ext4/mballoc.c:2540",
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
      "addr": 18446744071583179248,
      "name": "ext4_mb_prefetch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
ext4_group_t ext4_mb_prefetch(struct super_block * sb, ext4_group_t group, unsigned int nr, int * cnt)
```

```json
{
  "name": "ext4_mb_prefetch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_prefetch",
      "external": true,
      "loc": "fs/ext4/mballoc.c:2558",
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
      "addr": 18446744071592263950,
      "name": "ext4_mb_prefetch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071583521056,
      "name": "ext4_mb_prefetch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
ext4_group_t ext4_mb_prefetch(struct super_block * sb, ext4_group_t group, unsigned int nr, int * cnt)
```

```json
{
  "name": "ext4_mb_prefetch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_prefetch",
      "external": true,
      "loc": "fs/ext4/mballoc.c:2555",
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
      "addr": 18446744071594045685,
      "name": "ext4_mb_prefetch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584054224,
      "name": "ext4_mb_prefetch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
ext4_group_t ext4_mb_prefetch(struct super_block * sb, ext4_group_t group, unsigned int nr, int * cnt)
```

```json
{
  "name": "ext4_mb_prefetch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_prefetch",
      "external": true,
      "loc": "fs/ext4/mballoc.c:2518",
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
      "addr": 18446744071596078604,
      "name": "ext4_mb_prefetch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584686480,
      "name": "ext4_mb_prefetch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
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
ext4_group_t ext4_mb_prefetch(struct super_block * sb, ext4_group_t group, unsigned int nr, int * cnt)
```

```json
{
  "name": "ext4_mb_prefetch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584912080,
      "name": "ext4_mb_prefetch",
      "external": true,
      "loc": "fs/ext4/mballoc.c:2690",
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
      "addr": 18446744071584912080,
      "name": "ext4_mb_prefetch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
ext4_group_t ext4_mb_prefetch(struct super_block * sb, ext4_group_t group, unsigned int nr, int * cnt)
```

```json
{
  "name": "ext4_mb_prefetch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585145008,
      "name": "ext4_mb_prefetch",
      "external": true,
      "loc": "fs/ext4/mballoc.c:2714",
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
      "addr": 18446744071585145008,
      "name": "ext4_mb_prefetch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
ext4_group_t ext4_mb_prefetch(struct super_block * sb, ext4_group_t group, unsigned int nr, int * cnt)
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
