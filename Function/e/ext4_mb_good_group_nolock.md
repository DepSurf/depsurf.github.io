# Function: <code>ext4_mb_good_group_nolock</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ext4_mb_good_group_nolock(struct ext4_allocation_context * ac, ext4_group_t group, int cr)
```

```json
{
  "name": "ext4_mb_good_group_nolock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583062320,
      "name": "ext4_mb_good_group_nolock",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2175",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583062320,
      "name": "ext4_mb_good_group_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
int ext4_mb_good_group_nolock(struct ext4_allocation_context * ac, ext4_group_t group, int cr)
```

```json
{
  "name": "ext4_mb_good_group_nolock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583140768,
      "name": "ext4_mb_good_group_nolock",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2141",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583140768,
      "name": "ext4_mb_good_group_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 727
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
int ext4_mb_good_group_nolock(struct ext4_allocation_context * ac, ext4_group_t group, int cr)
```

```json
{
  "name": "ext4_mb_good_group_nolock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583167584,
      "name": "ext4_mb_good_group_nolock",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2478",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583167584,
      "name": "ext4_mb_good_group_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
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
int ext4_mb_good_group_nolock(struct ext4_allocation_context * ac, ext4_group_t group, int cr)
```

```json
{
  "name": "ext4_mb_good_group_nolock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_good_group_nolock",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2488",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583509376,
      "name": "ext4_mb_good_group_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
    },
    {
      "addr": 18446744071592262848,
      "name": "ext4_mb_good_group_nolock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int ext4_mb_good_group_nolock(struct ext4_allocation_context * ac, ext4_group_t group, int cr)
```

```json
{
  "name": "ext4_mb_good_group_nolock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_good_group_nolock",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2485",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584038016,
      "name": "ext4_mb_good_group_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 974
    },
    {
      "addr": 18446744071594044555,
      "name": "ext4_mb_good_group_nolock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int ext4_mb_good_group_nolock(struct ext4_allocation_context * ac, ext4_group_t group, int cr)
```

```json
{
  "name": "ext4_mb_good_group_nolock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_good_group_nolock",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2448",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584670304,
      "name": "ext4_mb_good_group_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
    },
    {
      "addr": 18446744071596077365,
      "name": "ext4_mb_good_group_nolock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_mb_good_group_nolock(struct ext4_allocation_context * ac, ext4_group_t group, enum criteria cr)
```

```json
{
  "name": "ext4_mb_good_group_nolock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_good_group_nolock",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2617",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584893936,
      "name": "ext4_mb_good_group_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 929
    },
    {
      "addr": 18446744071596600933,
      "name": "ext4_mb_good_group_nolock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_mb_good_group_nolock(struct ext4_allocation_context * ac, ext4_group_t group, enum criteria cr)
```

```json
{
  "name": "ext4_mb_good_group_nolock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_good_group_nolock",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2636",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585123952,
      "name": "ext4_mb_good_group_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 929
    },
    {
      "addr": 18446744071597506333,
      "name": "ext4_mb_good_group_nolock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ext4_mb_good_group_nolock(struct ext4_allocation_context * ac, ext4_group_t group, int cr)
```
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int cr</code> ➡️ <code>enum criteria cr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
