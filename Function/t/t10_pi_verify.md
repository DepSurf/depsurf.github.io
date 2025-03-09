# Function: <code>t10_pi_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, unsigned int type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943280,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:73",
      "file": "block/t10-pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type1_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type3_verify_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943280,
      "name": "t10_pi_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, unsigned int type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583230896,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:73",
      "file": "block/t10-pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583230896,
      "name": "t10_pi_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, unsigned int type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583336752,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:73",
      "file": "block/t10-pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583336752,
      "name": "t10_pi_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, unsigned int type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583395280,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:70",
      "file": "block/t10-pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583395280,
      "name": "t10_pi_verify",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, unsigned int type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583574560,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:70",
      "file": "block/t10-pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583574560,
      "name": "t10_pi_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, unsigned int type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:70",
      "file": "block/t10-pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583790720,
      "name": "t10_pi_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071583791056,
      "name": "t10_pi_verify.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, unsigned int type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:70",
      "file": "block/t10-pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583870560,
      "name": "t10_pi_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071583871849,
      "name": "t10_pi_verify.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, unsigned int type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:53",
      "file": "block/t10-pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584061296,
      "name": "t10_pi_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071584062681,
      "name": "t10_pi_verify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584184725,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:53",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584184416,
      "name": "t10_pi_verify.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071584185262,
      "name": "t10_pi_verify.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, enum t10_dif_type type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584578789,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:54",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584578784,
      "name": "t10_pi_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071584580630,
      "name": "t10_pi_verify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, enum t10_dif_type type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584696277,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:54",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584696272,
      "name": "t10_pi_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071591378308,
      "name": "t10_pi_verify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, enum t10_dif_type type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584724405,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:54",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584724400,
      "name": "t10_pi_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071591320550,
      "name": "t10_pi_verify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585152805,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:54",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151472,
      "name": "t10_pi_verify.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071592321634,
      "name": "t10_pi_verify.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585887621,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:56",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585884336,
      "name": "t10_pi_verify.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071594106166,
      "name": "t10_pi_verify.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586674181,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:56",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670592,
      "name": "t10_pi_verify.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586935429,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:56",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586931664,
      "name": "t10_pi_verify.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587216533,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:56",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587212768,
      "name": "t10_pi_verify.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, enum t10_dif_type type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496049488,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:53",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496049488,
      "name": "t10_pi_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, enum t10_dif_type type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229378428,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:53",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229378428,
      "name": "t10_pi_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, enum t10_dif_type type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290281424,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:53",
      "file": "block/t10-pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290281424,
      "name": "t10_pi_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, enum t10_dif_type type)
```

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275125866,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:53",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275125866,
      "name": "t10_pi_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584153461,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:53",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153152,
      "name": "t10_pi_verify.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071584153998,
      "name": "t10_pi_verify.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584088725,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:53",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584088416,
      "name": "t10_pi_verify.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071584089262,
      "name": "t10_pi_verify.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584137221,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:53",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136912,
      "name": "t10_pi_verify.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071584137758,
      "name": "t10_pi_verify.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "t10_pi_verify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584241349,
      "name": "t10_pi_verify",
      "external": false,
      "loc": "block/t10-pi.c:53",
      "file": "block/t10-pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ],
      "caller_func": [
        "block/t10-pi.c:t10_pi_type3_verify_ip",
        "block/t10-pi.c:t10_pi_type3_verify_crc",
        "block/t10-pi.c:t10_pi_type1_verify_ip",
        "block/t10-pi.c:t10_pi_type1_verify_crc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584241040,
      "name": "t10_pi_verify.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071584241916,
      "name": "t10_pi_verify.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, unsigned int type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, enum t10_dif_type type)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, enum t10_dif_type type)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, enum t10_dif_type type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, enum t10_dif_type type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, enum t10_dif_type type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter * iter, csum_fn * fn, enum t10_dif_type type)
```
</details>
</li>
</ul>
