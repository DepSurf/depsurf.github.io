# Function: <code>udp_lib_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
void udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586735696,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:180",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586753472,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:180",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587109600,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:180",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587122880,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:180",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735696,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071586753472,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071587109600,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071587122880,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587185456,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587201808,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587560992,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587574176,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587185456,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071587201808,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071587560992,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071587574176,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587386368,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587402176,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587765280,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587778224,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587386368,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071587402176,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071587765280,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071587778224,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587521328,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587537920,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587921408,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587934864,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587521328,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071587537920,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071587921408,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071587934864,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588044128,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588061344,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588456624,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588470304,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:192",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588044128,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071588061344,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071588456624,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071588470304,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588393264,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:195",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588413776,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:195",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588817888,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:195",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588833936,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:195",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588393264,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071588413776,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071588817888,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071588833936,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588582672,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:195",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588605360,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:195",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589040400,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:195",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589057424,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:195",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588582672,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071588605360,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071589040400,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071589057424,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588993888,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589016992,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589493792,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589510704,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588993888,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589016992,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589493792,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589510704,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589218416,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589241552,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589717632,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589734800,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589218416,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589241552,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589717632,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589734800,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590191904,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590215136,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590736976,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590752848,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590191904,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071590215136,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071590736976,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071590752848,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590241360,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:198",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590265872,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:198",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590795632,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:198",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590812272,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:198",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590241360,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071590265872,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071590795632,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071590812272,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590155104,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590180688,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590722592,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590739328,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590155104,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071590180688,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071590722592,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071590739328,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590935504,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590961520,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591539008,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591555888,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590935504,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071590961520,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071591539008,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071591555888,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592578480,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:177",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592604432,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:177",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593228144,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:177",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593246416,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:177",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592578480,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071592604432,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071593228144,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071593246416,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594439472,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:187",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594468448,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:187",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595128160,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:187",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595147328,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:187",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594439472,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071594468448,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071595128160,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071595147328,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594829824,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:188",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594859616,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:188",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595522544,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:188",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595542464,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:188",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594829824,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071594859616,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071595522544,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071595542464,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595641680,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:188",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595670960,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:188",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596366304,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:188",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596385232,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:188",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595641680,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071595670960,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071596366304,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071596385232,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502840728,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502869520,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503408272,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503425760,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502840728,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 18446603336502869520,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 18446603336503408272,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 18446603336503425760,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235543748,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235565044,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236069464,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236087212,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235543748,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 3235565044,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 3236069464,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 3236087212,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296497760,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296526320,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297185456,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297206912,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296497760,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 13835058055296526320,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 13835058055297185456,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 13835058055297206912,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278950412,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278971832,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279400148,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279417750,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278950412,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446743936278971832,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446743936279400148,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446743936279417750,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588824800,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588847936,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589322000,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589339168,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588824800,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071588847936,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589322000,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589339168,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588536736,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588559872,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589046992,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589064160,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588536736,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071588559872,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589046992,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589064160,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589260976,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589284112,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589758864,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589776032,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589260976,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589284112,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589758864,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589776032,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate ❓</summary>

```c
int udp_lib_hash(struct sock * sk)
```

```json
{
  "name": "udp_lib_hash",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589303968,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589325520,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589809536,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589826784,
      "name": "udp_lib_hash",
      "external": false,
      "loc": "include/net/udp.h:191",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589303968,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589325520,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589809536,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    },
    {
      "addr": 18446744071589826784,
      "name": "udp_lib_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
