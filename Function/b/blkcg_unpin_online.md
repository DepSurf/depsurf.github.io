# Function: <code>blkcg_unpin_online</code>

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
  "name": "blkcg_unpin_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581434833,
      "name": "blkcg_unpin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:437",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584529690,
      "name": "blkcg_unpin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:437",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_css_offline"
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
  "name": "blkcg_unpin_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581476193,
      "name": "blkcg_unpin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:427",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584639514,
      "name": "blkcg_unpin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:427",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_css_offline"
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
  "name": "blkcg_unpin_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581496945,
      "name": "blkcg_unpin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:427",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584667434,
      "name": "blkcg_unpin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:427",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_css_offline"
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
  "name": "blkcg_unpin_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581755377,
      "name": "blkcg_unpin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:432",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585083818,
      "name": "blkcg_unpin_online",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:432",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_css_offline"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void blkcg_unpin_online(struct cgroup_subsys_state * blkcg_css)
```

```json
{
  "name": "blkcg_unpin_online",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585809920,
      "name": "blkcg_unpin_online",
      "external": true,
      "loc": "block/blk-cgroup.c:1126",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:cgwb_release_workfn",
        "block/blk-cgroup.c:blkcg_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585809920,
      "name": "blkcg_unpin_online",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void blkcg_unpin_online(struct cgroup_subsys_state * blkcg_css)
```

```json
{
  "name": "blkcg_unpin_online",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586591536,
      "name": "blkcg_unpin_online",
      "external": true,
      "loc": "block/blk-cgroup.c:1138",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:cgwb_release_workfn",
        "block/blk-cgroup.c:blkcg_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586591536,
      "name": "blkcg_unpin_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void blkcg_unpin_online(struct cgroup_subsys_state * blkcg_css)
```

```json
{
  "name": "blkcg_unpin_online",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586849920,
      "name": "blkcg_unpin_online",
      "external": true,
      "loc": "block/blk-cgroup.c:1271",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:cgwb_release_workfn",
        "block/blk-cgroup.c:blkcg_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586849920,
      "name": "blkcg_unpin_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void blkcg_unpin_online(struct cgroup_subsys_state * blkcg_css)
```

```json
{
  "name": "blkcg_unpin_online",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587127232,
      "name": "blkcg_unpin_online",
      "external": true,
      "loc": "block/blk-cgroup.c:1284",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:cgwb_release_workfn",
        "block/blk-cgroup.c:blkcg_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587127232,
      "name": "blkcg_unpin_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void blkcg_unpin_online(struct cgroup_subsys_state * blkcg_css)
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
