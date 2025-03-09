# Function: <code>udp_lib_close</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586738608,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:188",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586753488,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:188",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587109616,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:188",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587122896,
      "name": "udp_lib_close",
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
      "addr": 18446744071586738608,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071586753488,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071587109616,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071587122896,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587185472,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587201824,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587561008,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587574192,
      "name": "udp_lib_close",
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
      "addr": 18446744071587185472,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071587201824,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071587561008,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071587574192,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587386384,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587402192,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587765296,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587778240,
      "name": "udp_lib_close",
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
      "addr": 18446744071587386384,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071587402192,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071587765296,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071587778240,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587521344,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587537968,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587921424,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587934912,
      "name": "udp_lib_close",
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
      "addr": 18446744071587521344,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071587537968,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071587921424,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071587934912,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588044144,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588061392,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588456640,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:201",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588470352,
      "name": "udp_lib_close",
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
      "addr": 18446744071588044144,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071588061392,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071588456640,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071588470352,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588393280,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:204",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588413824,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:204",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588817904,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:204",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588833984,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:204",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588393280,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071588413824,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071588817904,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071588833984,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588583104,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:204",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588605408,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:204",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589040608,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:204",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589057472,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:204",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588583104,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071588605408,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589040608,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589057472,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588994352,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589017040,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589494000,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589510752,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588994352,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589017040,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589494000,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589510752,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589218880,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589241600,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589717840,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589734848,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589218880,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589241600,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589717840,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589734848,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590192368,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590215184,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590737440,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590752896,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590192368,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071590215184,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071590737440,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071590752896,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590241760,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:207",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590265920,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:207",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590796128,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:207",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590812320,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:207",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590241760,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071590265920,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071590796128,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071590812320,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590155520,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:210",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590180736,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:210",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590722800,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:210",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590739376,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:210",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590155520,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071590180736,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071590722800,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071590739376,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590935920,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:210",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590961568,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:210",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591539216,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:210",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591555936,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:210",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590935920,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071590961568,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071591539216,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071591555936,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592578944,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:186",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592604496,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:186",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593228592,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:186",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593246480,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:186",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592578944,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071592604496,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071593228592,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071593246480,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594440384,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:196",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594468544,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:196",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595128688,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:196",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595147424,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:196",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594440384,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071594468544,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071595128688,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071595147424,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594830720,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:197",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594859648,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:197",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595523072,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:197",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595542496,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:197",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594830720,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071594859648,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071595523072,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071595542496,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595642592,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:197",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595670992,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:197",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596367072,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:197",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596385264,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:197",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595642592,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071595670992,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071596367072,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071596385264,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502841544,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502869576,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503408680,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503425816,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502841544,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336502869576,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336503408680,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336503425816,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235544372,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235565096,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236069676,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236087264,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235544372,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 3235565096,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 3236069676,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 3236087264,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296497776,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296526416,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297185920,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297207008,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296497776,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 13835058055296526416,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 13835058055297185920,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 13835058055297207008,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278950934,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278971878,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279400402,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279417796,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278950934,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446743936278971878,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446743936279400402,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446743936279417796,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588825264,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588847984,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589322208,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589339216,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588825264,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071588847984,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589322208,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589339216,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588537200,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588559920,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589047200,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589064208,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588537200,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071588559920,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589047200,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589064208,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589261440,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589284160,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589759072,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589776080,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589261440,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589284160,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589759072,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589776080,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void udp_lib_close(struct sock * sk, long int timeout)
```

```json
{
  "name": "udp_lib_close",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589304432,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589325568,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv4/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589809744,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589826832,
      "name": "udp_lib_close",
      "external": false,
      "loc": "include/net/udp.h:200",
      "file": "net/ipv6/udplite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589304432,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589325568,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589809744,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071589826832,
      "name": "udp_lib_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
