# Function: <code>inet_pton_with_scope</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587132592,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:373",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587132592,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587636208,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:373",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587636208,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587946608,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:373",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587946608,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588094688,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:373",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094688,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588410983,
      "name": "inet_pton_with_scope.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588410736,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588616359,
      "name": "inet_pton_with_scope.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588616112,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589472023,
      "name": "inet_pton_with_scope.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589471776,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591630640,
      "name": "inet_pton_with_scope.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589472672,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591574073,
      "name": "inet_pton_with_scope.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589371088,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592701816,
      "name": "inet_pton_with_scope.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590101456,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594588360,
      "name": "inet_pton_with_scope.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591652400,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593436000,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593436000,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593900880,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593900880,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594684176,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594684176,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502162488,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502162488,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234905284,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234905284,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295632576,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295632576,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278416740,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278416740,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588223095,
      "name": "inet_pton_with_scope.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588222848,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587935927,
      "name": "inet_pton_with_scope.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587935680,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588554919,
      "name": "inet_pton_with_scope.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588554672,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
```

```json
{
  "name": "inet_pton_with_scope",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_pton_with_scope",
      "external": true,
      "loc": "net/core/utils.c:369",
      "file": "net/core/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588692391,
      "name": "inet_pton_with_scope.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588692144,
      "name": "inet_pton_with_scope",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int inet_pton_with_scope(struct net * net, __kernel_sa_family_t af, const char * src, const char * port, struct __kernel_sockaddr_storage * addr)
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
