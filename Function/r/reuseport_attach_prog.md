# Function: <code>reuseport_attach_prog</code>

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
struct bpf_prog * reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586840224,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:243",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__reuseport_attach_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586840224,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct bpf_prog * reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587031152,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:242",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__reuseport_attach_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587031152,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct bpf_prog * reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587159312,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:242",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__reuseport_attach_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587159312,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct bpf_prog * reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587667792,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:254",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__reuseport_attach_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587667792,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct bpf_prog * reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587994672,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:256",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__reuseport_attach_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587994672,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588154784,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:306",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588154784,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588476272,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:319",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588476272,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588681696,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:319",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588681696,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589547536,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:311",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589547536,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589556560,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:311",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589556560,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589454512,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:311",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589454512,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590192080,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:584",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590192080,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591755200,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:584",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591755200,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593545760,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:684",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593545760,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594014832,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:684",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594014832,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594801200,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:684",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594801200,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502235752,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:319",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502235752,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234981236,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:319",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234981236,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295726640,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:319",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295726640,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278477918,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:319",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278477918,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588288432,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:319",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588288432,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588001248,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:319",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588001248,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588620256,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:319",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588620256,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
```

```json
{
  "name": "reuseport_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588758096,
      "name": "reuseport_attach_prog",
      "external": true,
      "loc": "net/core/sock_reuseport.c:319",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_bpf",
        "net/core/filter.c:sk_reuseport_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588758096,
      "name": "reuseport_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct bpf_prog * reuseport_attach_prog(struct sock * sk, struct bpf_prog * prog)
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct bpf_prog *</code> ➡️ <code>int</code>
</li>
</ul>
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
