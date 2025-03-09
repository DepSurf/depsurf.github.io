# Function: <code>lwt_out_func_proto</code>

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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587968032,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:4986",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_xmit_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587968032,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588119360,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:5630",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_xmit_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588119360,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588438656,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:6297",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_xmit_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588438656,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588645136,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:6384",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_xmit_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588645136,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589533334,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:6595",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ],
      "caller_func": [
        "net/core/filter.c:lwt_xmit_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589505280,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589542358,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:7400",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ],
      "caller_func": [
        "net/core/filter.c:lwt_xmit_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589508784,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589439638,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:7522",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ],
      "caller_func": [
        "net/core/filter.c:lwt_xmit_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589407632,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590172038,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:7652",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ],
      "caller_func": [
        "net/core/filter.c:lwt_xmit_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590131504,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591734972,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:8036",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ],
      "caller_func": [
        "net/core/filter.c:lwt_xmit_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591683760,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593522796,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:8175",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ],
      "caller_func": [
        "net/core/filter.c:lwt_xmit_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593470512,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593991420,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:8327",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ],
      "caller_func": [
        "net/core/filter.c:lwt_xmit_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593937312,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594775628,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:8418",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ],
      "caller_func": [
        "net/core/filter.c:lwt_xmit_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594720080,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502189336,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:6384",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_xmit_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502189336,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234936596,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:6384",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_xmit_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234936596,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295670208,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:6384",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_xmit_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295670208,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278444644,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:6384",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_xmit_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278444644,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588251872,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:6384",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_xmit_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588251872,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587964688,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:6384",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_xmit_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587964688,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588583696,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:6384",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_xmit_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588583696,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "lwt_out_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588721184,
      "name": "lwt_out_func_proto",
      "external": false,
      "loc": "net/core/filter.c:6384",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_xmit_func_proto",
        "net/core/filter.c:lwt_in_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588721184,
      "name": "lwt_out_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
const struct bpf_func_proto * lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
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
