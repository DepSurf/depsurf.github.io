# Function: <code>bpf_skb_under_cgroup</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586821632,
      "name": "bpf_skb_under_cgroup",
      "external": false,
      "loc": "net/core/filter.c:2286",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586821632,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587010032,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:2539",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587010032,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587136816,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:2699",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136816,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587641488,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:3098",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587641488,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587948912,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:3723",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587948912,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588097024,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:3911",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588097024,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588425584,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4048",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588425584,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588630944,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4055",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588630944,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589492528,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4027",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589492528,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589494592,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4435",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589494592,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589393072,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4374",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589393072,
      "name": "bpf_skb_under_cgroup",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4432",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592703413,
      "name": "bpf_skb_under_cgroup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071590166288,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4723",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594589874,
      "name": "bpf_skb_under_cgroup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071591725360,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4741",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596328458,
      "name": "bpf_skb_under_cgroup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593514672,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4795",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596858323,
      "name": "bpf_skb_under_cgroup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593975712,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4869",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597783345,
      "name": "bpf_skb_under_cgroup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071594759312,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502176928,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4055",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502176928,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234922300,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4055",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234922300,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295649760,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4055",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295649760,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278430662,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4055",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278430662,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588237680,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4055",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588237680,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587950496,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4055",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587950496,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588569504,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4055",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588569504,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_under_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588706960,
      "name": "bpf_skb_under_cgroup",
      "external": true,
      "loc": "net/core/filter.c:4055",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588706960,
      "name": "bpf_skb_under_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
u64 bpf_skb_under_cgroup(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 skb</code>
</li>
<li>
<b>Param added. </b>
<code>u64 map</code>
</li>
<li>
<b>Param added. </b>
<code>u64 idx</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
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
