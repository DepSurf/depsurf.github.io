# Function: <code>bpf_skb_get_tunnel_opt</code>

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
u64 bpf_skb_get_tunnel_opt(u64 r1, u64 r2, u64 size, u64 r4, u64 r5)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586822512,
      "name": "bpf_skb_get_tunnel_opt",
      "external": false,
      "loc": "net/core/filter.c:2127",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586822512,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587020720,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:2385",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587020720,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587150560,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:2544",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587150560,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587654208,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:2942",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587654208,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587976496,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:3564",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587976496,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588129904,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:3752",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588129904,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588443984,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:3889",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588443984,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588650512,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:3896",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588650512,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589516960,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:3868",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589516960,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589523808,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:4276",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589523808,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589426448,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:4215",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589426448,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590152800,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:4273",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590152800,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591714368,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:4559",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591714368,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593500208,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:4577",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593500208,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593965072,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:4628",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593965072,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594747632,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:4702",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594747632,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502196768,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:3896",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502196768,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234948332,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:3896",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234948332,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295680560,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:3896",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295680560,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278454326,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:3896",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278454326,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588257248,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:3896",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588257248,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587970064,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:3896",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587970064,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588589072,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:3896",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588589072,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_get_tunnel_opt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588726560,
      "name": "bpf_skb_get_tunnel_opt",
      "external": true,
      "loc": "net/core/filter.c:3896",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588726560,
      "name": "bpf_skb_get_tunnel_opt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
u64 bpf_skb_get_tunnel_opt(u64 r1, u64 r2, u64 size, u64 r4, u64 r5)
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
<code>u64 to</code>
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
