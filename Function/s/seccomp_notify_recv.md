# Function: <code>seccomp_notify_recv</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580385079,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1006",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580437762,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1011",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580486574,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1022",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int seccomp_notify_recv(struct seccomp_filter * filter, void * buf)
```

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580571312,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1038",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571312,
      "name": "seccomp_notify_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
long int seccomp_notify_recv(struct seccomp_filter * filter, void * buf)
```

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580558944,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1416",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580558944,
      "name": "seccomp_notify_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
long int seccomp_notify_recv(struct seccomp_filter * filter, void * buf)
```

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580562048,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1446",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580562048,
      "name": "seccomp_notify_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
long int seccomp_notify_recv(struct seccomp_filter * filter, void * buf)
```

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580731744,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1428",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580731744,
      "name": "seccomp_notify_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
long int seccomp_notify_recv(struct seccomp_filter * filter, void * buf)
```

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1454",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945488,
      "name": "seccomp_notify_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
    },
    {
      "addr": 18446744071593938477,
      "name": "seccomp_notify_recv.cold",
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
long int seccomp_notify_recv(struct seccomp_filter * filter, void * buf)
```

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1454",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581239696,
      "name": "seccomp_notify_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
    },
    {
      "addr": 18446744071596001596,
      "name": "seccomp_notify_recv.cold",
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
long int seccomp_notify_recv(struct seccomp_filter * filter, void * buf)
```

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1454",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581334912,
      "name": "seccomp_notify_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
    },
    {
      "addr": 18446744071596520162,
      "name": "seccomp_notify_recv.cold",
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
long int seccomp_notify_recv(struct seccomp_filter * filter, void * buf)
```

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1497",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581441744,
      "name": "seccomp_notify_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
    },
    {
      "addr": 18446744071597420547,
      "name": "seccomp_notify_recv.cold",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491765464,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1022",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225713520,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1022",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284805248,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1022",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272082726,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1022",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580455374,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1022",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580402446,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1022",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580446622,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1022",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_notify_recv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580502254,
      "name": "seccomp_notify_recv",
      "external": false,
      "loc": "kernel/seccomp.c:1022",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int seccomp_notify_recv(struct seccomp_filter * filter, void * buf)
```
</details>
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
