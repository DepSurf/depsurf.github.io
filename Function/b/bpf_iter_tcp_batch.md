# Function: <code>bpf_iter_tcp_batch</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct sock * bpf_iter_tcp_batch(struct seq_file * seq)
```

```json
{
  "name": "bpf_iter_tcp_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_tcp_batch",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:2818",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590885504,
      "name": "bpf_iter_tcp_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 905
    },
    {
      "addr": 18446744071592720406,
      "name": "bpf_iter_tcp_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
struct sock * bpf_iter_tcp_batch(struct seq_file * seq)
```

```json
{
  "name": "bpf_iter_tcp_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_tcp_batch",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:2783",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592520384,
      "name": "bpf_iter_tcp_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 951
    },
    {
      "addr": 18446744071594606615,
      "name": "bpf_iter_tcp_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct sock * bpf_iter_tcp_batch(struct seq_file * seq)
```

```json
{
  "name": "bpf_iter_tcp_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_tcp_batch",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:2859",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594378112,
      "name": "bpf_iter_tcp_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
    },
    {
      "addr": 18446744071596341952,
      "name": "bpf_iter_tcp_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct sock * bpf_iter_tcp_batch(struct seq_file * seq)
```

```json
{
  "name": "bpf_iter_tcp_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_tcp_batch",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:2867",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594766384,
      "name": "bpf_iter_tcp_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1043
    },
    {
      "addr": 18446744071596871200,
      "name": "bpf_iter_tcp_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct sock * bpf_iter_tcp_batch(struct seq_file * seq)
```

```json
{
  "name": "bpf_iter_tcp_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_tcp_batch",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:3071",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next",
        "net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595574656,
      "name": "bpf_iter_tcp_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1043
    },
    {
      "addr": 18446744071597794971,
      "name": "bpf_iter_tcp_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct sock * bpf_iter_tcp_batch(struct seq_file * seq)
```
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
