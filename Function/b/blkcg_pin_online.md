# Function: <code>blkcg_pin_online</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkcg_pin_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581434428,
      "name": "blkcg_pin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:423",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584523041,
      "name": "blkcg_pin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:423",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_css_online"
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
  "name": "blkcg_pin_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581477325,
      "name": "blkcg_pin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:413",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584632177,
      "name": "blkcg_pin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:413",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_css_online"
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
  "name": "blkcg_pin_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581498098,
      "name": "blkcg_pin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:413",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584660017,
      "name": "blkcg_pin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:413",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_css_online"
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
  "name": "blkcg_pin_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581758100,
      "name": "blkcg_pin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:418",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585074625,
      "name": "blkcg_pin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:418",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_css_online"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blkcg_pin_online(struct cgroup_subsys_state * blkcg_css)
```

```json
{
  "name": "blkcg_pin_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585800847,
      "name": "blkcg_pin_online",
      "external": true,
      "loc": "block/blk-cgroup.c:1112",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:cgwb_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585809792,
      "name": "blkcg_pin_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blkcg_pin_online(struct cgroup_subsys_state * blkcg_css)
```

```json
{
  "name": "blkcg_pin_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586581585,
      "name": "blkcg_pin_online",
      "external": true,
      "loc": "block/blk-cgroup.c:1124",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_css_online"
      ],
      "caller_func": [
        "mm/backing-dev.c:cgwb_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586591392,
      "name": "blkcg_pin_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blkcg_pin_online(struct cgroup_subsys_state * blkcg_css)
```

```json
{
  "name": "blkcg_pin_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586839265,
      "name": "blkcg_pin_online",
      "external": true,
      "loc": "block/blk-cgroup.c:1257",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_css_online"
      ],
      "caller_func": [
        "mm/backing-dev.c:cgwb_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586849776,
      "name": "blkcg_pin_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blkcg_pin_online(struct cgroup_subsys_state * blkcg_css)
```

```json
{
  "name": "blkcg_pin_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587116465,
      "name": "blkcg_pin_online",
      "external": true,
      "loc": "block/blk-cgroup.c:1270",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_css_online"
      ],
      "caller_func": [
        "mm/backing-dev.c:cgwb_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587127088,
      "name": "blkcg_pin_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void blkcg_pin_online(struct cgroup_subsys_state * blkcg_css)
```
</details>
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
