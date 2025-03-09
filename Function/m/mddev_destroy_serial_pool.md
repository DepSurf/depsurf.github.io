# Function: <code>mddev_destroy_serial_pool</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_destroy_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```

```json
{
  "name": "mddev_destroy_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588719577,
      "name": "mddev_destroy_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:255",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:unbind_rdev_from_array"
      ],
      "caller_func": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588688688,
      "name": "mddev_destroy_serial_pool.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    },
    {
      "addr": 18446744071588741333,
      "name": "mddev_destroy_serial_pool.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588714768,
      "name": "mddev_destroy_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_destroy_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```

```json
{
  "name": "mddev_destroy_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588747097,
      "name": "mddev_destroy_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:253",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:unbind_rdev_from_array"
      ],
      "caller_func": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588715488,
      "name": "mddev_destroy_serial_pool.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071591584298,
      "name": "mddev_destroy_serial_pool.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588742288,
      "name": "mddev_destroy_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_destroy_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```

```json
{
  "name": "mddev_destroy_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588632649,
      "name": "mddev_destroy_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:253",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:unbind_rdev_from_array"
      ],
      "caller_func": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588601552,
      "name": "mddev_destroy_serial_pool.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071591527361,
      "name": "mddev_destroy_serial_pool.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588627424,
      "name": "mddev_destroy_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_destroy_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```

```json
{
  "name": "mddev_destroy_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589310073,
      "name": "mddev_destroy_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:254",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:unbind_rdev_from_array"
      ],
      "caller_func": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589278416,
      "name": "mddev_destroy_serial_pool.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071592638777,
      "name": "mddev_destroy_serial_pool.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071589304800,
      "name": "mddev_destroy_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_destroy_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```

```json
{
  "name": "mddev_destroy_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590781808,
      "name": "mddev_destroy_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:255",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:unbind_rdev_from_array"
      ],
      "caller_func": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590769152,
      "name": "mddev_destroy_serial_pool.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
    },
    {
      "addr": 18446744071594523232,
      "name": "mddev_destroy_serial_pool.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071590776592,
      "name": "mddev_destroy_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void mddev_destroy_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```

```json
{
  "name": "mddev_destroy_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592456256,
      "name": "mddev_destroy_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:267",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592456256,
      "name": "mddev_destroy_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
void mddev_destroy_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```

```json
{
  "name": "mddev_destroy_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592876512,
      "name": "mddev_destroy_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:253",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592876512,
      "name": "mddev_destroy_serial_pool",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_destroy_serial_pool(struct mddev * mddev, struct md_rdev * rdev)
```

```json
{
  "name": "mddev_destroy_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593647267,
      "name": "mddev_destroy_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:265",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:serialize_policy_store"
      ],
      "caller_func": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593614128,
      "name": "mddev_destroy_serial_pool.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    },
    {
      "addr": 18446744071593626608,
      "name": "mddev_destroy_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void mddev_destroy_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool is_suspend</code>
</li>
</ul>
</details>
</li>
</ul>
