# Function: <code>blkcg_policy_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582874453,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:52",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool blkcg_policy_enabled(struct request_queue * q, const struct blkcg_policy * pol)
```

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583157360,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:52",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157360,
      "name": "blkcg_policy_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
bool blkcg_policy_enabled(struct request_queue * q, const struct blkcg_policy * pol)
```

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583269440,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:52",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269440,
      "name": "blkcg_policy_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
bool blkcg_policy_enabled(struct request_queue * q, const struct blkcg_policy * pol)
```

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583324784,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:53",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583324784,
      "name": "blkcg_policy_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool blkcg_policy_enabled(struct request_queue * q, const struct blkcg_policy * pol)
```

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583507888,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:53",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583507888,
      "name": "blkcg_policy_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool blkcg_policy_enabled(struct request_queue * q, const struct blkcg_policy * pol)
```

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583722304,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:53",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722304,
      "name": "blkcg_policy_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
bool blkcg_policy_enabled(struct request_queue * q, const struct blkcg_policy * pol)
```

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583828880,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:56",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583828880,
      "name": "blkcg_policy_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584023717,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:60",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584127298,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:60",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584529090,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:60",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584638812,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:60",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584666732,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:58",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585083176,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:61",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585808974,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:79",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool blkcg_policy_enabled(struct request_queue * q, const struct blkcg_policy * pol)
```

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586577984,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:111",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586577984,
      "name": "blkcg_policy_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
bool blkcg_policy_enabled(struct request_queue * q, const struct blkcg_policy * pol)
```

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586835984,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:113",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_deactivate_policy",
        "block/blk-cgroup.c:blkcg_activate_policy",
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586835984,
      "name": "blkcg_policy_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
bool blkcg_policy_enabled(struct request_queue * q, const struct blkcg_policy * pol)
```

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587113200,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:113",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_deactivate_policy",
        "block/blk-cgroup.c:blkcg_activate_policy",
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587113200,
      "name": "blkcg_policy_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495974164,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:60",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ],
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
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229311828,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:60",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ],
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
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290197576,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:60",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ],
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
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275076080,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:60",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584096034,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:60",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584031794,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:60",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584079794,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:60",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
      ],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkcg_policy_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584178423,
      "name": "blkcg_policy_enabled",
      "external": false,
      "loc": "block/blk-cgroup.c:60",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkg_alloc"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool blkcg_policy_enabled(struct request_queue * q, const struct blkcg_policy * pol)
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
bool blkcg_policy_enabled(struct request_queue * q, const struct blkcg_policy * pol)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool blkcg_policy_enabled(struct request_queue * q, const struct blkcg_policy * pol)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
