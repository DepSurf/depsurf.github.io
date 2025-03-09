# Function: <code>user_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582210080,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:187",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071582328272,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1538",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582328272,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071582210080,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582426960,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:167",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071582549504,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1538",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582549504,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071582426960,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582519136,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:167",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071582641840,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1541",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641840,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071582519136,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582600528,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:175",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071582732320,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1538",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732320,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    },
    {
      "addr": 18446744071582600528,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582753936,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:175",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071582888096,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1538",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582888096,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    },
    {
      "addr": 18446744071582753936,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582954032,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:175",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071583086896,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1538",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583086896,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071582954032,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583063152,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:175",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071583203392,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1550",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583203392,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071583063152,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583247760,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071583391664,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1502",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391664,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071583247760,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583353600,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071583497552,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1504",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583497552,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071583353600,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583689408,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071583841504,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1490",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841504,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
    },
    {
      "addr": 18446744071583689408,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583810976,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071583962672,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1522",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583962672,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
    },
    {
      "addr": 18446744071583810976,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583835232,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071583988112,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1520",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583988112,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    },
    {
      "addr": 18446744071583835232,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584198224,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071584354848,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1520",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584354848,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    },
    {
      "addr": 18446744071584198224,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584800160,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071584978368,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1514",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584978368,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
    },
    {
      "addr": 18446744071584800160,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585498592,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071585694688,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1514",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585694688,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
    },
    {
      "addr": 18446744071585498592,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585730144,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071585928368,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1514",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585928368,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
    },
    {
      "addr": 18446744071585730144,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585977392,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071586176752,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1537",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586176752,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
    },
    {
      "addr": 18446744071585977392,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495098896,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446603336495261608,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1504",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495261608,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446603336495098896,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228491688,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 3228645320,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1504",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228645320,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 3228491688,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289001616,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 13835058055289240608,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1504",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289240608,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
    },
    {
      "addr": 13835058055289001616,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274359598,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446743936274483766,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1504",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274483766,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446743936274359598,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583322336,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071583466288,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1504",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583466288,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071583322336,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583259440,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071583403360,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1504",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583403360,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071583259440,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583306112,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071583450064,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1504",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583450064,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071583306112,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
long int user_read(const struct key * key, char * buffer, size_t buflen)
```

```json
{
  "name": "user_read",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583401104,
      "name": "user_read",
      "external": true,
      "loc": "security/keys/user_defined.c:171",
      "file": "security/keys/user_defined.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/dns_resolver/dns_key.c:dns_resolver_read"
      ]
    },
    {
      "addr": 18446744071583546320,
      "name": "user_read",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:1504",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583546320,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071583401104,
      "name": "user_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
