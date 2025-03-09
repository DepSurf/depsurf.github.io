# Function: <code>pefile_digest_pe_contents</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582709181,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:245",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
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
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582987781,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:245",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
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
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583092341,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:245",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583147588,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:245",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583324026,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:245",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583532513,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:245",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583655954,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:245",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583841520,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841520,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583943632,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583943632,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584336288,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336288,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584453888,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584453888,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584489008,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584489008,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584887360,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584887360,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585585136,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585585136,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586351296,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586351296,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586597872,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:245",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586597872,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586867216,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:245",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586867216,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495763776,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495763776,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229115992,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229115992,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289933600,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289933600,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274911206,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583912368,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912368,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583849424,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849424,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583896128,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583896128,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```

```json
{
  "name": "pefile_digest_pe_contents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583997168,
      "name": "pefile_digest_pe_contents",
      "external": false,
      "loc": "crypto/asymmetric_keys/verify_pefile.c:241",
      "file": "crypto/asymmetric_keys/verify_pefile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583997168,
      "name": "pefile_digest_pe_contents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pefile_digest_pe_contents(const void * pebuf, unsigned int pelen, struct pefile_context * ctx, struct shash_desc * desc)
```
</details>
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
