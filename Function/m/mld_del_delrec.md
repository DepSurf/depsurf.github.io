# Function: <code>mld_del_delrec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587151320,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:744",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_dev_mc_inc"
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
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587603984,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:744",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_dev_mc_inc"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587806464,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:749",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587806464,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587963824,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:749",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587963824,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588499008,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:749",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588499008,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588863088,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:769",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588863088,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589086048,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:769",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589086048,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589540800,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:765",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589540800,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589764880,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:765",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589764880,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590780368,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:762",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590780368,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590839536,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:762",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590839536,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590765760,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:765",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590765760,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591582816,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:770",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591582816,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593275792,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:770",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593275792,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595178992,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:770",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595178992,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595574656,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:770",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595574656,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596417360,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:770",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596417360,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503454640,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:765",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503454640,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236119916,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:765",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236119916,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297251216,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:765",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297251216,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279435804,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:765",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279435804,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589369248,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:765",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589369248,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589094240,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:765",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589094240,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589806112,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:765",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589806112,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```

```json
{
  "name": "mld_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589856928,
      "name": "mld_del_delrec",
      "external": false,
      "loc": "net/ipv6/mcast.c:765",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589856928,
      "name": "mld_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void mld_del_delrec(struct inet6_dev * idev, struct ifmcaddr6 * im)
```
</details>
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
