# Function: <code>bpf_run_sk_reuseport</code>

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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588148064,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:7790",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588148064,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588468944,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:8612",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588468944,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588674512,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:8699",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588674512,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589540080,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:9009",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589540080,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589549232,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:9877",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589549232,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589447184,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:10018",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589447184,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, struct sock * migrating_sk, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590182352,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:10196",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_migrate_sock",
        "net/core/sock_reuseport.c:reuseport_migrate_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590182352,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, struct sock * migrating_sk, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591744864,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:10702",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_migrate_sock",
        "net/core/sock_reuseport.c:reuseport_migrate_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591744864,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, struct sock * migrating_sk, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593534576,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:10908",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_migrate_sock",
        "net/core/sock_reuseport.c:reuseport_migrate_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593534576,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, struct sock * migrating_sk, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594002464,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:11057",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_migrate_sock",
        "net/core/sock_reuseport.c:reuseport_migrate_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594002464,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, struct sock * migrating_sk, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594786784,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:11148",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_migrate_sock",
        "net/core/sock_reuseport.c:reuseport_migrate_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594786784,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502227464,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:8699",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502227464,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234973456,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:8699",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234973456,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295715696,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:8699",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295715696,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278471722,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:8699",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278471722,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588281248,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:8699",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588281248,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587994064,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:8699",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587994064,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588613072,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:8699",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588613072,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
```

```json
{
  "name": "bpf_run_sk_reuseport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588750752,
      "name": "bpf_run_sk_reuseport",
      "external": true,
      "loc": "net/core/filter.c:8699",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588750752,
      "name": "bpf_run_sk_reuseport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct sock * bpf_run_sk_reuseport(struct sock_reuseport * reuse, struct sock * sk, struct bpf_prog * prog, struct sk_buff * skb, u32 hash)
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sock * migrating_sk</code>
</li>
<li>
<b>Param reordered. </b>
<code>reuse, sk, prog, skb, hash</code> ➡️ <code>reuse, sk, prog, skb, migrating_sk, hash</code>
</li>
</ul>
</details>
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
