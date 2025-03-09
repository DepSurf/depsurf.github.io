# Function: <code>mr_mfc_find_parent</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563776,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:63",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563776,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588761488,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588761488,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589194512,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589194512,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589419968,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589419968,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590405824,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590405824,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590463664,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590463664,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590389424,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590389424,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591183904,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591183904,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592843328,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592843328,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594720432,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594720432,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595112512,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595112512,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595925232,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595925232,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503072616,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503072616,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235755584,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv6/ip6mr.c:ip6mr_cache_find_parent",
        "net/ipv6/ip6mr.c:ip6mr_cache_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235755584,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296776560,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296776560,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279129302,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:ip6mr_cache_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279129302,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589024336,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589024336,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588747392,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588747392,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589460720,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589460720,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```

```json
{
  "name": "mr_mfc_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589507056,
      "name": "mr_mfc_find_parent",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:64",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589507056,
      "name": "mr_mfc_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void * mr_mfc_find_parent(struct mr_table * mrt, void * hasharg, int parent)
```
</details>
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
