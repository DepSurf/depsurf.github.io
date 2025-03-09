# Function: <code>copy_group_source_from_sockptr</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int copy_group_source_from_sockptr(struct group_source_req * greqs, sockptr_t optval, int optlen)
```

```json
{
  "name": "copy_group_source_from_sockptr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590030848,
      "name": "copy_group_source_from_sockptr",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:698",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_mcast_group_source"
      ]
    },
    {
      "addr": 18446744071590770480,
      "name": "copy_group_source_from_sockptr",
      "external": false,
      "loc": "net/ipv6/ipv6_sockglue.c:139",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590030848,
      "name": "copy_group_source_from_sockptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 18446744071590770480,
      "name": "copy_group_source_from_sockptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int copy_group_source_from_sockptr(struct group_source_req * greqs, sockptr_t optval, int optlen)
```

```json
{
  "name": "copy_group_source_from_sockptr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589942640,
      "name": "copy_group_source_from_sockptr",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:698",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_mcast_group_source"
      ]
    },
    {
      "addr": 18446744071590693920,
      "name": "copy_group_source_from_sockptr",
      "external": false,
      "loc": "net/ipv6/ipv6_sockglue.c:139",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589942640,
      "name": "copy_group_source_from_sockptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 18446744071590693920,
      "name": "copy_group_source_from_sockptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int copy_group_source_from_sockptr(struct group_source_req * greqs, sockptr_t optval, int optlen)
```

```json
{
  "name": "copy_group_source_from_sockptr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590709712,
      "name": "copy_group_source_from_sockptr",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:697",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_mcast_group_source"
      ]
    },
    {
      "addr": 18446744071591509808,
      "name": "copy_group_source_from_sockptr",
      "external": false,
      "loc": "net/ipv6/ipv6_sockglue.c:139",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590709712,
      "name": "copy_group_source_from_sockptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 18446744071591509808,
      "name": "copy_group_source_from_sockptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int copy_group_source_from_sockptr(struct group_source_req * greqs, sockptr_t optval, int optlen)
```

```json
{
  "name": "copy_group_source_from_sockptr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592341504,
      "name": "copy_group_source_from_sockptr",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:699",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_mcast_group_source"
      ]
    },
    {
      "addr": 18446744071593195216,
      "name": "copy_group_source_from_sockptr",
      "external": false,
      "loc": "net/ipv6/ipv6_sockglue.c:141",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592341504,
      "name": "copy_group_source_from_sockptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
    },
    {
      "addr": 18446744071593195216,
      "name": "copy_group_source_from_sockptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 745
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int copy_group_source_from_sockptr(struct group_source_req * greqs, sockptr_t optval, int optlen)
```

```json
{
  "name": "copy_group_source_from_sockptr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594177712,
      "name": "copy_group_source_from_sockptr",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:700",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_mcast_group_source"
      ]
    },
    {
      "addr": 18446744071595093760,
      "name": "copy_group_source_from_sockptr",
      "external": false,
      "loc": "net/ipv6/ipv6_sockglue.c:141",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594177712,
      "name": "copy_group_source_from_sockptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
    },
    {
      "addr": 18446744071595093760,
      "name": "copy_group_source_from_sockptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 745
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
int copy_group_source_from_sockptr(struct group_source_req * greqs, sockptr_t optval, int optlen)
```

```json
{
  "name": "copy_group_source_from_sockptr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594564752,
      "name": "copy_group_source_from_sockptr",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:707",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_mcast_group_source"
      ]
    },
    {
      "addr": 18446744071595487552,
      "name": "copy_group_source_from_sockptr",
      "external": false,
      "loc": "net/ipv6/ipv6_sockglue.c:141",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594564752,
      "name": "copy_group_source_from_sockptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
    },
    {
      "addr": 18446744071595487552,
      "name": "copy_group_source_from_sockptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 745
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
int copy_group_source_from_sockptr(struct group_source_req * greqs, sockptr_t optval, int optlen)
```

```json
{
  "name": "copy_group_source_from_sockptr",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595368048,
      "name": "copy_group_source_from_sockptr",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:698",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_mcast_group_source"
      ]
    },
    {
      "addr": 18446744071596330832,
      "name": "copy_group_source_from_sockptr",
      "external": false,
      "loc": "net/ipv6/ipv6_sockglue.c:141",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595368048,
      "name": "copy_group_source_from_sockptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
    },
    {
      "addr": 18446744071596330832,
      "name": "copy_group_source_from_sockptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 745
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
int copy_group_source_from_sockptr(struct group_source_req * greqs, sockptr_t optval, int optlen)
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
