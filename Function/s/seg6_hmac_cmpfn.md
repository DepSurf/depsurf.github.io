# Function: <code>seg6_hmac_cmpfn</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587907648,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:50",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587907648,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588065376,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:50",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588065376,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588609536,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:51",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588609536,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588978808,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:51",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588975936,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589202859,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:52",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589199936,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589656682,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:47",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589653696,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589881082,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:47",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589878096,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590906240,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:46",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590906240,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590973143,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:45",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590969840,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590904019,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:45",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590900784,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591737731,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:45",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591734416,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593440098,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:45",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593436448,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595355986,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:45",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595351600,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595752356,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:45",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595748544,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596600532,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:45",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596596720,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503597648,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:47",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503597648,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236246172,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:47",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236242956,
      "name": "seg6_hmac_cmpfn",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297408320,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:47",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297408320,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279550884,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:47",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279550884,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589485450,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:47",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589482464,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589210442,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:47",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589207456,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589922314,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:47",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589919328,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
```

```json
{
  "name": "seg6_hmac_cmpfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589975936,
      "name": "seg6_hmac_cmpfn",
      "external": false,
      "loc": "net/ipv6/seg6_hmac.c:47",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_push_hmac",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589972032,
      "name": "seg6_hmac_cmpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int seg6_hmac_cmpfn(struct rhashtable_compare_arg * arg, const void * obj)
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
