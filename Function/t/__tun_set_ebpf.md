# Function: <code>__tun_set_ebpf</code>

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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586430880,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2250",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586430880,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586576608,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2268",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586576608,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586828560,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2263",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586828560,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586974640,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2267",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974640,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587803885,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2240",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/tun.c:tun_free_netdev"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587799952,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587861645,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2167",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/tun.c:tun_free_netdev"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587857552,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587739757,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2172",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/tun.c:tun_free_netdev"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587736976,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588334994,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2228",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/tun.c:tun_free_netdev"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588332176,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589730194,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2260",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/tun.c:tun_free_netdev"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589723312,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591348850,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2264",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/tun.c:tun_free_netdev"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591342528,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591710578,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2278",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/tun.c:tun_free_netdev"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591704064,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592454866,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2290",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/tun.c:tun_free_netdev"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592446160,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499969936,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2267",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499969936,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232506668,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2267",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232506668,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293295104,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2267",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf",
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/tun.c:tun_free_netdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293295104,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277045378,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2267",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277045378,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586731648,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2267",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586731648,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586598864,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2267",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586598864,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586929200,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2267",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586929200,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
```

```json
{
  "name": "__tun_set_ebpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587036624,
      "name": "__tun_set_ebpf",
      "external": false,
      "loc": "drivers/net/tun.c:2267",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_set_ebpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036624,
      "name": "__tun_set_ebpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int __tun_set_ebpf(struct tun_struct * tun, struct tun_prog * * prog_p, struct bpf_prog * prog)
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
