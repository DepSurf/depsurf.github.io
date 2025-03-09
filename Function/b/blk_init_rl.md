# Function: <code>blk_init_rl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int blk_init_rl(struct request_list * rl, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "blk_init_rl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582750560,
      "name": "blk_init_rl",
      "external": true,
      "loc": "block/blk-core.c:615",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_allocated_queue",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582750560,
      "name": "blk_init_rl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int blk_init_rl(struct request_list * rl, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "blk_init_rl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583028512,
      "name": "blk_init_rl",
      "external": true,
      "loc": "block/blk-core.c:617",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_allocated_queue",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583028512,
      "name": "blk_init_rl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int blk_init_rl(struct request_list * rl, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "blk_init_rl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583133296,
      "name": "blk_init_rl",
      "external": true,
      "loc": "block/blk-core.c:618",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_allocated_queue",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583133296,
      "name": "blk_init_rl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int blk_init_rl(struct request_list * rl, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "blk_init_rl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583189776,
      "name": "blk_init_rl",
      "external": true,
      "loc": "block/blk-core.c:718",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_allocated_queue",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583189776,
      "name": "blk_init_rl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int blk_init_rl(struct request_list * rl, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "blk_init_rl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583355511,
      "name": "blk_init_rl",
      "external": true,
      "loc": "block/blk-core.c:768",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_init_allocated_queue"
      ],
      "caller_func": [
        "block/blk-core.c:blk_init_allocated_queue",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583355168,
      "name": "blk_init_rl.part.84",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071583366192,
      "name": "blk_init_rl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int blk_init_rl(struct request_list * rl, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "blk_init_rl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583565043,
      "name": "blk_init_rl",
      "external": true,
      "loc": "block/blk-core.c:868",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_init_allocated_queue"
      ],
      "caller_func": [
        "block/blk-core.c:blk_init_allocated_queue",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583564704,
      "name": "blk_init_rl.part.82",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    },
    {
      "addr": 18446744071583575648,
      "name": "blk_init_rl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int blk_init_rl(struct request_list * rl, struct request_queue * q, gfp_t gfp_mask)
```
</details>
</li>
</ul>
