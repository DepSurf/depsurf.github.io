# Function: <code>ahash_restore_req</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582657514,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:286",
      "file": "crypto/ahash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:ahash_def_finup_finish2"
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
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582903706,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:269",
      "file": "crypto/ahash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:ahash_def_finup_finish2"
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
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583003434,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:269",
      "file": "crypto/ahash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:ahash_def_finup_finish2"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583053840,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:273",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583053840,
      "name": "ahash_restore_req",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583219568,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:281",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583219568,
      "name": "ahash_restore_req",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583427680,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:281",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427680,
      "name": "ahash_restore_req",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583548880,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:292",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583548880,
      "name": "ahash_restore_req",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583737664,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:287",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737664,
      "name": "ahash_restore_req",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583847424,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:287",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583847424,
      "name": "ahash_restore_req",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584236784,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:289",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup",
        "crypto/ahash.c:ahash_def_finup_done1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236784,
      "name": "ahash_restore_req",
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
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584355264,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:256",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup",
        "crypto/ahash.c:ahash_def_finup_done1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584355264,
      "name": "ahash_restore_req",
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
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584389616,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:256",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup",
        "crypto/ahash.c:ahash_def_finup_done1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389616,
      "name": "ahash_restore_req",
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
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584784848,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:256",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup",
        "crypto/ahash.c:ahash_def_finup_done1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784848,
      "name": "ahash_restore_req",
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
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585469968,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:256",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup",
        "crypto/ahash.c:ahash_def_finup_done1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585469968,
      "name": "ahash_restore_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586231008,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:256",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup",
        "crypto/ahash.c:ahash_def_finup_done1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586231008,
      "name": "ahash_restore_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586466160,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:239",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup",
        "crypto/ahash.c:ahash_def_finup_done1",
        "crypto/ahash.c:ahash_def_finup_done1",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586466160,
      "name": "ahash_restore_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586737952,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:331",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586737952,
      "name": "ahash_restore_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495661112,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:287",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495661112,
      "name": "ahash_restore_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229015040,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:287",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229015040,
      "name": "ahash_restore_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289798624,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:287",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289798624,
      "name": "ahash_restore_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274813000,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:287",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274813000,
      "name": "ahash_restore_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583816160,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:287",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583816160,
      "name": "ahash_restore_req",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583753216,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:287",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583753216,
      "name": "ahash_restore_req",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583799920,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:287",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583799920,
      "name": "ahash_restore_req",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request * req, int err)
```

```json
{
  "name": "ahash_restore_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583900960,
      "name": "ahash_restore_req",
      "external": false,
      "loc": "crypto/ahash.c:287",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ahash.c:ahash_def_finup_finish1",
        "crypto/ahash.c:ahash_def_finup_done2",
        "crypto/ahash.c:crypto_ahash_op",
        "crypto/ahash.c:ahash_op_unaligned_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900960,
      "name": "ahash_restore_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void ahash_restore_req(struct ahash_request * req, int err)
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
