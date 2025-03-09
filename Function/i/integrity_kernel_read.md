# Function: <code>integrity_kernel_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int integrity_kernel_read(struct file * file, loff_t offset, char * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582606400,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:182",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/iint.c:integrity_read_file",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606400,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int integrity_kernel_read(struct file * file, loff_t offset, char * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582851520,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:184",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/iint.c:integrity_read_file",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582851520,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int integrity_kernel_read(struct file * file, loff_t offset, char * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582947552,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:184",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/iint.c:integrity_read_file",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582947552,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582997728,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:184",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/iint.c:integrity_read_file",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582997728,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583161808,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:184",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583161808,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583367296,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:188",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583367296,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583486048,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:192",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583486048,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672144,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:188",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672144,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583779152,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:188",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779152,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584169696,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:188",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584169696,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584288832,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:196",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584288832,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584322672,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:196",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322672,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584709808,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:196",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584709808,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585383568,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:196",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585383568,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586135248,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:196",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586135248,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586373120,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:192",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586373120,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586637664,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:218",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586637664,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495581600,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:188",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495581600,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228943144,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:188",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228943144,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289679520,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:188",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289679520,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274747702,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:188",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274747702,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583747888,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:188",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583747888,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583684944,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:188",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583684944,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583731664,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:188",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731664,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int integrity_kernel_read(struct file * file, loff_t offset, void * addr, long unsigned int count)
```

```json
{
  "name": "integrity_kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583832544,
      "name": "integrity_kernel_read",
      "external": true,
      "loc": "security/integrity/iint.c:188",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583832544,
      "name": "integrity_kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
<b>Param type changed. </b>
<code>char * addr</code> ➡️ <code>void * addr</code>
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
