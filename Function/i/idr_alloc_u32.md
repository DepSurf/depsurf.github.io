# Function: <code>idr_alloc_u32</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589129520,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:34",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_create",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589129520,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589364208,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:32",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589364208,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589821248,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589821248,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590047536,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590047536,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585041504,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585041504,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585193232,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585193232,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585076320,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076320,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585523152,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585523152,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586676160,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586676160,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595756224,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595756224,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596280544,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596280544,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597165248,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597165248,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503822104,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503822104,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236443516,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236443516,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297666608,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297666608,
      "name": "idr_alloc_u32",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279717686,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279717686,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589649792,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589649792,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589375600,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589375600,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590093168,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590093168,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```

```json
{
  "name": "idr_alloc_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590143424,
      "name": "idr_alloc_u32",
      "external": true,
      "loc": "lib/idr.c:33",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590143424,
      "name": "idr_alloc_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int idr_alloc_u32(struct idr * idr, void * ptr, u32 * nextid, long unsigned int max, gfp_t gfp)
```
</details>
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
