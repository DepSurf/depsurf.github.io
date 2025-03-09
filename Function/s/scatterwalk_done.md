# Function: <code>scatterwalk_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void scatterwalk_done(struct scatter_walk * walk, int out, int more)
```

```json
{
  "name": "scatterwalk_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582640320,
      "name": "scatterwalk_done",
      "external": true,
      "loc": "crypto/scatterwalk.c:73",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scatterwalk.c:scatterwalk_map_and_copy",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582640320,
      "name": "scatterwalk_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582894829,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582898686,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582991309,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995118,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582998872,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583046300,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:pre_crypt",
        "crypto/xts.c:post_crypt"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583041309,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583045084,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583049096,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583100485,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:pre_crypt",
        "crypto/xts.c:post_crypt"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583206685,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583210476,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583217177,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583267093,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:pre_crypt",
        "crypto/xts.c:post_crypt"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583415133,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583417670,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583425317,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583474268,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:114",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:pre_crypt",
        "crypto/xts.c:post_crypt"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:101",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583536221,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:101",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583539686,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:101",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583546341,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:101",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583724829,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583727862,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583735686,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583834509,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583837526,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583845494,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584234246,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584352854,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584387254,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:91",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584782486,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:91",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:92",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585467638,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:92",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:86",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586227430,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:86",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:86",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586463030,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:86",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:86",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586734358,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:86",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495641168,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495646176,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495650056,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495658792,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228996920,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229001424,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 3229004460,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 3229013060,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289772452,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289779532,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289783848,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289795768,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274800240,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274803716,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274811034,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583803245,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583806262,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583814230,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583740301,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583743318,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583751286,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583787005,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583790022,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797990,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_done",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583888029,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583891078,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583899014,
      "name": "scatterwalk_done",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:96",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
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
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void scatterwalk_done(struct scatter_walk * walk, int out, int more)
```
</details>
</li>
</ul>
