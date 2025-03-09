# Function: <code>devinet_sysctl_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586782755,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2259",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587232732,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2297",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587433276,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2297",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device * idev)
```

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587568864,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2352",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587568864,
      "name": "devinet_sysctl_unregister",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device * idev)
```

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588092624,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2361",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588092624,
      "name": "devinet_sysctl_unregister",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device * idev)
```

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588446160,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2371",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588446160,
      "name": "devinet_sysctl_unregister",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device * idev)
```

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588639280,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2531",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588639280,
      "name": "devinet_sysctl_unregister",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device * idev)
```

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589051504,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2621",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589051504,
      "name": "devinet_sysctl_unregister",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device * idev)
```

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589276016,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2616",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589276016,
      "name": "devinet_sysctl_unregister",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590255201,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2619",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590308097,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2618",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590223412,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2619",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591006068,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2624",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592652318,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2633",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594519258,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2634",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594911371,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2637",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595723106,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2667",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device * idev)
```

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502905936,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2616",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502905936,
      "name": "devinet_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void devinet_sysctl_unregister(struct in_device * idev)
```

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235599344,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2616",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235599344,
      "name": "devinet_sysctl_unregister",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device * idev)
```

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296572736,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2616",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296572736,
      "name": "devinet_sysctl_unregister",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device * idev)
```

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279001468,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2616",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279001468,
      "name": "devinet_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void devinet_sysctl_unregister(struct in_device * idev)
```

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588882192,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2616",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588882192,
      "name": "devinet_sysctl_unregister",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device * idev)
```

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588594128,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2616",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588594128,
      "name": "devinet_sysctl_unregister",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device * idev)
```

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589318576,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2616",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589318576,
      "name": "devinet_sysctl_unregister",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device * idev)
```

```json
{
  "name": "devinet_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589360448,
      "name": "devinet_sysctl_unregister",
      "external": false,
      "loc": "net/ipv4/devinet.c:2616",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589360448,
      "name": "devinet_sysctl_unregister",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void devinet_sysctl_unregister(struct in_device * idev)
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
void devinet_sysctl_unregister(struct in_device * idev)
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
