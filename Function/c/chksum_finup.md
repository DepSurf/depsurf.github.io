# Function: <code>chksum_finup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582693376,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:112",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582693376,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582693648,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582953568,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:112",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:75",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953568,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582953840,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583057552,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:112",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:75",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583057552,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583057824,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583112656,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:112",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583112848,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:75",
      "file": "crypto/crct10dif_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112656,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583112848,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583286592,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:112",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583286784,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:75",
      "file": "crypto/crct10dif_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286592,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583286784,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583495040,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:113",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583495232,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:75",
      "file": "crypto/crct10dif_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583495040,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583495232,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583616304,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:113",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583616496,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:75",
      "file": "crypto/crct10dif_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616304,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583616496,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583802400,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:108",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583802624,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583802400,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583802624,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583904240,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:108",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583904464,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583904240,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583904464,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584294000,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:106",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584294272,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584294000,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584294272,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584412608,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:106",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584412880,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584412608,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584412880,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584447536,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:106",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584447808,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584447536,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584447808,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584845536,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:106",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584845808,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845536,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584845808,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585538720,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:106",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585539008,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585539216,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc64_rocksoft_generic.c:42",
      "file": "crypto/crc64_rocksoft_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585538720,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585539008,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585539216,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586300528,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:106",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586300912,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586301200,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc64_rocksoft_generic.c:42",
      "file": "crypto/crc64_rocksoft_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586300528,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586300912,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586301200,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586544144,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:106",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586544528,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586544816,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc64_rocksoft_generic.c:42",
      "file": "crypto/crc64_rocksoft_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586544144,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586544528,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586544816,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586814224,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:106",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586814608,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586814896,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc64_rocksoft_generic.c:42",
      "file": "crypto/crc64_rocksoft_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586814224,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586814608,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586814896,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495724616,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:108",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495725080,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495724616,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446603336495725080,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229078832,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:108",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229079132,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229078832,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3229079132,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289878640,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:108",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289879136,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289878640,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 13835058055289879136,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274876304,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:108",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274876734,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274876304,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446743936274876734,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872976,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:108",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583873200,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872976,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583873200,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583810032,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:108",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583810256,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583810032,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583810256,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583856736,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:108",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583856960,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583856736,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583856960,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
int chksum_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "chksum_finup",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583957808,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crc32c_generic.c:108",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583958032,
      "name": "chksum_finup",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:74",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957808,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583958032,
      "name": "chksum_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
