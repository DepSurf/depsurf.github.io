# Function: <code>scatterwalk_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void scatterwalk_start(struct scatter_walk * walk, struct scatterlist * sg)
```

```json
{
  "name": "scatterwalk_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582640192,
      "name": "scatterwalk_start",
      "external": true,
      "loc": "crypto/scatterwalk.c:33",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_map_and_copy"
      ],
      "caller_func": [
        "crypto/scatterwalk.c:scatterwalk_map_and_copy",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582640192,
      "name": "scatterwalk_start.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582640208,
      "name": "scatterwalk_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582890488,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_map_and_copy",
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582896037,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582899337,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582986508,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582992501,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995769,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583001453,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583046343,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583036516,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583042501,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583045637,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583051581,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583100538,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583201817,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583207877,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583211029,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583217119,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583267146,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583410297,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583416197,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583419237,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583425254,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583474307,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:82",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583532009,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:69",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583537285,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:69",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583540213,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:69",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583546278,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:69",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583719983,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583725273,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583728661,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583735622,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583829695,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583834969,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583838341,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583845430,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584225123,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584234182,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_async",
        "crypto/skcipher.c:skcipher_walk_async",
        "crypto/skcipher.c:skcipher_walk_virt",
        "crypto/skcipher.c:skcipher_walk_virt",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584343507,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584352790,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_async",
        "crypto/skcipher.c:skcipher_walk_async",
        "crypto/skcipher.c:skcipher_walk_virt",
        "crypto/skcipher.c:skcipher_walk_virt",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584378008,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584387190,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_async",
        "crypto/skcipher.c:skcipher_walk_async",
        "crypto/skcipher.c:skcipher_walk_virt",
        "crypto/skcipher.c:skcipher_walk_virt",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584773240,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584782422,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_async",
        "crypto/skcipher.c:skcipher_walk_async",
        "crypto/skcipher.c:skcipher_walk_virt",
        "crypto/skcipher.c:skcipher_walk_virt",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585458372,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:65",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_map_and_copy",
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585467574,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:65",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_async",
        "crypto/skcipher.c:skcipher_walk_async",
        "crypto/skcipher.c:skcipher_walk_virt",
        "crypto/skcipher.c:skcipher_walk_virt",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586217268,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:59",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_map_and_copy",
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586227366,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:59",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_async",
        "crypto/skcipher.c:skcipher_walk_async",
        "crypto/skcipher.c:skcipher_walk_virt",
        "crypto/skcipher.c:skcipher_walk_virt",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586452564,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:59",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_map_and_copy",
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586462966,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:59",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_async",
        "crypto/skcipher.c:skcipher_walk_async",
        "crypto/skcipher.c:skcipher_walk_virt",
        "crypto/skcipher.c:skcipher_walk_virt",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586718452,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:59",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_map_and_copy",
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586734294,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:59",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495640904,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495647340,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495650704,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495658736,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228996668,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 3229002036,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 3229005352,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 3229013004,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289772120,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289780400,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289785200,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289795704,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274795582,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274801264,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274804152,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274810984,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583798431,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583803705,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583807077,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583814166,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583735487,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583740761,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583744133,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583751222,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583782191,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583787465,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583790837,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797926,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
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
  "name": "scatterwalk_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583883207,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583888473,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_phys",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583891925,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_first",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583898950,
      "name": "scatterwalk_start",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:64",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_skcipher",
        "crypto/skcipher.c:skcipher_walk_skcipher",
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
void scatterwalk_start(struct scatter_walk * walk, struct scatterlist * sg)
```
</details>
</li>
</ul>
