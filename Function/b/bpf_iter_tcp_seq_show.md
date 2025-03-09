# Function: <code>bpf_iter_tcp_seq_show</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int bpf_iter_tcp_seq_show(struct seq_file * seq, void * v)
```

```json
{
  "name": "bpf_iter_tcp_seq_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590183872,
      "name": "bpf_iter_tcp_seq_show",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:2679",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590183872,
      "name": "bpf_iter_tcp_seq_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
int bpf_iter_tcp_seq_show(struct seq_file * seq, void * v)
```

```json
{
  "name": "bpf_iter_tcp_seq_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590098224,
      "name": "bpf_iter_tcp_seq_show",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:2697",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590098224,
      "name": "bpf_iter_tcp_seq_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
int bpf_iter_tcp_seq_show(struct seq_file * seq, void * v)
```

```json
{
  "name": "bpf_iter_tcp_seq_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_tcp_seq_show",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:2917",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590879440,
      "name": "bpf_iter_tcp_seq_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071592720170,
      "name": "bpf_iter_tcp_seq_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
int bpf_iter_tcp_seq_show(struct seq_file * seq, void * v)
```

```json
{
  "name": "bpf_iter_tcp_seq_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_tcp_seq_show",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:2882",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592518208,
      "name": "bpf_iter_tcp_seq_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071594606507,
      "name": "bpf_iter_tcp_seq_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
int bpf_iter_tcp_seq_show(struct seq_file * seq, void * v)
```

```json
{
  "name": "bpf_iter_tcp_seq_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_tcp_seq_show",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:2959",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594375872,
      "name": "bpf_iter_tcp_seq_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071596341844,
      "name": "bpf_iter_tcp_seq_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
int bpf_iter_tcp_seq_show(struct seq_file * seq, void * v)
```

```json
{
  "name": "bpf_iter_tcp_seq_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_tcp_seq_show",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:2967",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594764176,
      "name": "bpf_iter_tcp_seq_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071596871119,
      "name": "bpf_iter_tcp_seq_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int bpf_iter_tcp_seq_show(struct seq_file * seq, void * v)
```

```json
{
  "name": "bpf_iter_tcp_seq_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_iter_tcp_seq_show",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:3171",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595570672,
      "name": "bpf_iter_tcp_seq_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071597794777,
      "name": "bpf_iter_tcp_seq_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int bpf_iter_tcp_seq_show(struct seq_file * seq, void * v)
```
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
