# Function: <code>bpf_setsockopt</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```

```json
{
  "name": "bpf_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587141232,
      "name": "bpf_setsockopt",
      "external": true,
      "loc": "net/core/filter.c:2790",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587141232,
      "name": "bpf_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
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
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```

```json
{
  "name": "bpf_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587646320,
      "name": "bpf_setsockopt",
      "external": true,
      "loc": "net/core/filter.c:3189",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587646320,
      "name": "bpf_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```

```json
{
  "name": "bpf_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_setsockopt",
      "external": true,
      "loc": "net/core/filter.c:3835",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587989392,
      "name": "bpf_setsockopt.cold.93",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587962176,
      "name": "bpf_setsockopt",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```

```json
{
  "name": "bpf_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_setsockopt",
      "external": true,
      "loc": "net/core/filter.c:4093",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588148200,
      "name": "bpf_setsockopt.cold.100",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588112320,
      "name": "bpf_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```

```json
{
  "name": "bpf_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_setsockopt",
      "external": true,
      "loc": "net/core/filter.c:4230",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588469170,
      "name": "bpf_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588429808,
      "name": "bpf_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```

```json
{
  "name": "bpf_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_setsockopt",
      "external": true,
      "loc": "net/core/filter.c:4237",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588674738,
      "name": "bpf_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588635392,
      "name": "bpf_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```

```json
{
  "name": "bpf_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502205568,
      "name": "bpf_setsockopt",
      "external": true,
      "loc": "net/core/filter.c:4237",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502205568,
      "name": "bpf_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```

```json
{
  "name": "bpf_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234941804,
      "name": "bpf_setsockopt",
      "external": true,
      "loc": "net/core/filter.c:4237",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234941804,
      "name": "bpf_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1116
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
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```

```json
{
  "name": "bpf_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295656800,
      "name": "bpf_setsockopt",
      "external": true,
      "loc": "net/core/filter.c:4237",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295656800,
      "name": "bpf_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1312
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
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```

```json
{
  "name": "bpf_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278436494,
      "name": "bpf_setsockopt",
      "external": true,
      "loc": "net/core/filter.c:4237",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278436494,
      "name": "bpf_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```

```json
{
  "name": "bpf_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_setsockopt",
      "external": true,
      "loc": "net/core/filter.c:4237",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588281474,
      "name": "bpf_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588242128,
      "name": "bpf_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```

```json
{
  "name": "bpf_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_setsockopt",
      "external": true,
      "loc": "net/core/filter.c:4237",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587994290,
      "name": "bpf_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587954944,
      "name": "bpf_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```

```json
{
  "name": "bpf_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_setsockopt",
      "external": true,
      "loc": "net/core/filter.c:4237",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588613298,
      "name": "bpf_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588573952,
      "name": "bpf_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```

```json
{
  "name": "bpf_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_setsockopt",
      "external": true,
      "loc": "net/core/filter.c:4237",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588750978,
      "name": "bpf_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588711440,
      "name": "bpf_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen)
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
