# Function: <code>ipmr_mfc_seq_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void * ipmr_mfc_seq_next(struct seq_file * seq, void * v, loff_t * pos)
```

```json
{
  "name": "ipmr_mfc_seq_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586872256,
      "name": "ipmr_mfc_seq_next",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2578",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587203488,
      "name": "ipmr_mfc_seq_next",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:502",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586872256,
      "name": "ipmr_mfc_seq_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071587203488,
      "name": "ipmr_mfc_seq_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void * ipmr_mfc_seq_next(struct seq_file * seq, void * v, loff_t * pos)
```

```json
{
  "name": "ipmr_mfc_seq_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587322016,
      "name": "ipmr_mfc_seq_next",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2633",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587660176,
      "name": "ipmr_mfc_seq_next",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:502",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587322016,
      "name": "ipmr_mfc_seq_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071587660176,
      "name": "ipmr_mfc_seq_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void * ipmr_mfc_seq_next(struct seq_file * seq, void * v, loff_t * pos)
```

```json
{
  "name": "ipmr_mfc_seq_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587524704,
      "name": "ipmr_mfc_seq_next",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2644",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587868656,
      "name": "ipmr_mfc_seq_next",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:502",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587524704,
      "name": "ipmr_mfc_seq_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    },
    {
      "addr": 18446744071587868656,
      "name": "ipmr_mfc_seq_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * ipmr_mfc_seq_next(struct seq_file * seq, void * v, loff_t * pos)
```

```json
{
  "name": "ipmr_mfc_seq_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587662512,
      "name": "ipmr_mfc_seq_next",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2937",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588024048,
      "name": "ipmr_mfc_seq_next",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:503",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587662512,
      "name": "ipmr_mfc_seq_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071588024048,
      "name": "ipmr_mfc_seq_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * ipmr_mfc_seq_next(struct seq_file * seq, void * v, loff_t * pos)
```

```json
{
  "name": "ipmr_mfc_seq_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588187792,
      "name": "ipmr_mfc_seq_next",
      "external": false,
      "loc": "net/ipv4/ipmr.c:3102",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588561168,
      "name": "ipmr_mfc_seq_next",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:503",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588187792,
      "name": "ipmr_mfc_seq_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071588561168,
      "name": "ipmr_mfc_seq_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void * ipmr_mfc_seq_next(struct seq_file * seq, void * v, loff_t * pos)
```
</details>
</li>
</ul>
