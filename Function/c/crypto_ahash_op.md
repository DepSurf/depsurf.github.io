# Function: <code>crypto_ahash_op</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582659152,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:349",
      "file": "crypto/ahash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_digest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659152,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582905424,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:332",
      "file": "crypto/ahash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582905424,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583005152,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:332",
      "file": "crypto/ahash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005152,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583053952,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:347",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583053952,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583219680,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:353",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583219680,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583427792,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:353",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427792,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583548992,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:364",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583548992,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583739824,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:359",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583739824,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583849584,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:359",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849584,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584236896,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:361",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236896,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584355376,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:328",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584355376,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584389728,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:328",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389728,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584784960,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:328",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784960,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585470096,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:328",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585470096,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586231152,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:328",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586231152,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op, bool has_state)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586467840,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:286",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586467840,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495663744,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:359",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495663744,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229017424,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:359",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229017424,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289802160,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:359",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289802160,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274815306,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:359",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274815306,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583818320,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:359",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583818320,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583755376,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:359",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583755376,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583802080,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:359",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583802080,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op)
```

```json
{
  "name": "crypto_ahash_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583903120,
      "name": "crypto_ahash_op",
      "external": false,
      "loc": "crypto/ahash.c:359",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903120,
      "name": "crypto_ahash_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool has_state</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int crypto_ahash_op(struct ahash_request * req, int (*)(struct ahash_request *) op, bool has_state)
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
