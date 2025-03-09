# Function: <code>ecryptfs_to_hex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ecryptfs_to_hex(char * dst, char * src, size_t src_size)
```

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582012528,
      "name": "ecryptfs_to_hex",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:50",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582012528,
      "name": "ecryptfs_to_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void ecryptfs_to_hex(char * dst, char * src, size_t src_size)
```

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226192,
      "name": "ecryptfs_to_hex",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:51",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226192,
      "name": "ecryptfs_to_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void ecryptfs_to_hex(char * dst, char * src, size_t src_size)
```

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582315696,
      "name": "ecryptfs_to_hex",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:51",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582315696,
      "name": "ecryptfs_to_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void ecryptfs_to_hex(char * dst, char * src, size_t src_size)
```

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582400336,
      "name": "ecryptfs_to_hex",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:51",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582400336,
      "name": "ecryptfs_to_hex",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582569094,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:56",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582574954,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:56",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582760432,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:56",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582767523,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:56",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582864496,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:56",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582871523,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:56",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583038685,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583046051,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583144909,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583152275,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583469048,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583474515,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583580792,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583583683,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583603974,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583606899,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583962374,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583965299,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584544437,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584547529,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585220148,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585223113,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585449620,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585452633,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585684420,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585687433,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494855808,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494861564,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228273732,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 3228279648,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288709472,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288716832,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274177148,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274183094,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583113645,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121011,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583050797,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058163,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583102253,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583109619,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_to_hex",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583191453,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583198819,
      "name": "ecryptfs_to_hex",
      "external": false,
      "loc": "fs/ecryptfs/ecryptfs_kernel.h:42",
      "file": "fs/ecryptfs/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
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
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void ecryptfs_to_hex(char * dst, char * src, size_t src_size)
```
</details>
</li>
</ul>
