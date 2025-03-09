# Function: <code>bpfilter_umh_cleanup</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void bpfilter_umh_cleanup(struct umh_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588727104,
      "name": "bpfilter_umh_cleanup",
      "external": false,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588727104,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void bpfilter_umh_cleanup(struct umh_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589159136,
      "name": "bpfilter_umh_cleanup",
      "external": false,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589159136,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void bpfilter_umh_cleanup(struct umh_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589383120,
      "name": "bpfilter_umh_cleanup",
      "external": false,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589383120,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void bpfilter_umh_cleanup(struct umh_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590369664,
      "name": "bpfilter_umh_cleanup",
      "external": false,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590369664,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void bpfilter_umh_cleanup(struct umd_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590427035,
      "name": "bpfilter_umh_cleanup",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590426800,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void bpfilter_umh_cleanup(struct umd_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590352379,
      "name": "bpfilter_umh_cleanup",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590352144,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void bpfilter_umh_cleanup(struct umd_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591141707,
      "name": "bpfilter_umh_cleanup",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591141472,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void bpfilter_umh_cleanup(struct umd_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592796491,
      "name": "bpfilter_umh_cleanup",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592796240,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void bpfilter_umh_cleanup(struct umd_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594670763,
      "name": "bpfilter_umh_cleanup",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594670496,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void bpfilter_umh_cleanup(struct umh_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503026304,
      "name": "bpfilter_umh_cleanup",
      "external": false,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503026304,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void bpfilter_umh_cleanup(struct umh_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235715668,
      "name": "bpfilter_umh_cleanup",
      "external": false,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235715668,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void bpfilter_umh_cleanup(struct umh_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296724416,
      "name": "bpfilter_umh_cleanup",
      "external": false,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296724416,
      "name": "bpfilter_umh_cleanup",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void bpfilter_umh_cleanup(struct umh_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279096512,
      "name": "bpfilter_umh_cleanup",
      "external": false,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279096512,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void bpfilter_umh_cleanup(struct umh_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588989296,
      "name": "bpfilter_umh_cleanup",
      "external": false,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588989296,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void bpfilter_umh_cleanup(struct umh_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588701232,
      "name": "bpfilter_umh_cleanup",
      "external": false,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588701232,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void bpfilter_umh_cleanup(struct umh_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589425680,
      "name": "bpfilter_umh_cleanup",
      "external": false,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589425680,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void bpfilter_umh_cleanup(struct umh_info * info)
```

```json
{
  "name": "bpfilter_umh_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589469248,
      "name": "bpfilter_umh_cleanup",
      "external": false,
      "loc": "net/ipv4/bpfilter/sockopt.c:15",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589469248,
      "name": "bpfilter_umh_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void bpfilter_umh_cleanup(struct umh_info * info)
```
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct umh_info * info</code> ➡️ <code>struct umd_info * info</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void bpfilter_umh_cleanup(struct umd_info * info)
```
</details>
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
