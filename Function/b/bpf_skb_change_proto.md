# Function: <code>bpf_skb_change_proto</code>

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
u64 bpf_skb_change_proto(u64 r1, u64 r2, u64 flags, u64 r4, u64 r5)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586829936,
      "name": "bpf_skb_change_proto",
      "external": false,
      "loc": "net/core/filter.c:1933",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586829936,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1213
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587021008,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2055",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587021008,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1213
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587148096,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2099",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587148096,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587655568,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2164",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587655568,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587979392,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2693",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587979392,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 691
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588131120,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2883",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588131120,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588447472,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2929",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588447472,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588651648,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2931",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588651648,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589518640,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2969",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589518640,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589528320,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:3338",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589528320,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589436192,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:3331",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589436192,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590161792,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:3300",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590161792,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591722448,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:3301",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591722448,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593510560,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:3311",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593510560,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 772
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593973904,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:3327",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593973904,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 772
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594758352,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:3361",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594758352,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 772
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502198696,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2931",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502198696,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234949380,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2931",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234949380,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295692144,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2931",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295692144,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278455322,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2931",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278455322,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588258384,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2931",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588258384,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587971200,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2931",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587971200,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588590208,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2931",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588590208,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_change_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588727696,
      "name": "bpf_skb_change_proto",
      "external": true,
      "loc": "net/core/filter.c:2931",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588727696,
      "name": "bpf_skb_change_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
u64 bpf_skb_change_proto(u64 r1, u64 r2, u64 flags, u64 r4, u64 r5)
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
<code>u64 proto</code>
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
