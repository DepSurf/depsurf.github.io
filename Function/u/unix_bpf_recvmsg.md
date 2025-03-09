# Function: <code>unix_bpf_recvmsg</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int unix_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "unix_bpf_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591343888,
      "name": "unix_bpf_recvmsg",
      "external": false,
      "loc": "net/unix/unix_bpf.c:50",
      "file": "net/unix/unix_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591343888,
      "name": "unix_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
int unix_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "unix_bpf_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593015488,
      "name": "unix_bpf_recvmsg",
      "external": false,
      "loc": "net/unix/unix_bpf.c:50",
      "file": "net/unix/unix_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593015488,
      "name": "unix_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1215
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
int unix_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "unix_bpf_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594905792,
      "name": "unix_bpf_recvmsg",
      "external": false,
      "loc": "net/unix/unix_bpf.c:50",
      "file": "net/unix/unix_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594905792,
      "name": "unix_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int unix_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "unix_bpf_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595297312,
      "name": "unix_bpf_recvmsg",
      "external": false,
      "loc": "net/unix/unix_bpf.c:50",
      "file": "net/unix/unix_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595297312,
      "name": "unix_bpf_recvmsg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1179
    },
    {
      "addr": 18446744071595298512,
      "name": "unix_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int unix_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "unix_bpf_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596138688,
      "name": "unix_bpf_recvmsg",
      "external": false,
      "loc": "net/unix/unix_bpf.c:50",
      "file": "net/unix/unix_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596138688,
      "name": "unix_bpf_recvmsg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1179
    },
    {
      "addr": 18446744071596139888,
      "name": "unix_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int unix_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nonblock</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, msg, len, nonblock, flags, addr_len</code> ➡️ <code>sk, msg, len, flags, addr_len</code>
</li>
</ul>
</details>
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
