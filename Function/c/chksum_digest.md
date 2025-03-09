# Function: <code>chksum_digest</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582693328,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:120",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582693568,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:83",
      "file": "crypto/crct10dif_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582693328,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582693568,
      "name": "chksum_digest",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582953520,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:120",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582953760,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:83",
      "file": "crypto/crct10dif_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953520,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582953760,
      "name": "chksum_digest",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583057504,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:120",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583057744,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:83",
      "file": "crypto/crct10dif_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583057504,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583057744,
      "name": "chksum_digest",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583112608,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:120",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:83",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112608,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583112928,
      "name": "chksum_digest",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583286544,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:120",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:83",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286544,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583286864,
      "name": "chksum_digest",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583494992,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:121",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:83",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583494992,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583495312,
      "name": "chksum_digest",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583616256,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:121",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:83",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616256,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583616576,
      "name": "chksum_digest",
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583802352,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:116",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583802592,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583802352,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583802592,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583904192,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:116",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583904432,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583904192,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583904432,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584293952,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:114",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584294224,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293952,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584294224,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584412560,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:114",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584412832,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584412560,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584412832,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584447488,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:114",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584447760,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584447488,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584447760,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584845488,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:114",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584845760,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845488,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584845760,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585538656,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:114",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585538960,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585539168,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc64_rocksoft_generic.c:50",
      "file": "crypto/crc64_rocksoft_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585538656,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071585538960,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071585539168,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586300448,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:114",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586300848,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586301136,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc64_rocksoft_generic.c:50",
      "file": "crypto/crc64_rocksoft_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586300448,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071586300848,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071586301136,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586544064,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:114",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586544464,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586544752,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc64_rocksoft_generic.c:50",
      "file": "crypto/crc64_rocksoft_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586544064,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071586544464,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071586544752,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586814144,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:114",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586814544,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586814832,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc64_rocksoft_generic.c:50",
      "file": "crypto/crc64_rocksoft_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586814144,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071586814544,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071586814832,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495724528,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:116",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495725000,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495724528,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446603336495725000,
      "name": "chksum_digest",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229078780,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:116",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229079084,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229078780,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 3229079084,
      "name": "chksum_digest",
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289878544,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:116",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289879056,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289878544,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 13835058055289879056,
      "name": "chksum_digest",
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274876196,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:116",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274876666,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274876196,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446743936274876666,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872928,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:116",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583873168,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872928,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583873168,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583809984,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:116",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583810224,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583809984,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583810224,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583856688,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:116",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583856928,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583856688,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583856928,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int chksum_digest(struct shash_desc * desc, const u8 * data, unsigned int length, u8 * out)
```

```json
{
  "name": "chksum_digest",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583957760,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crc32c_generic.c:116",
      "file": "crypto/crc32c_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583958000,
      "name": "chksum_digest",
      "external": false,
      "loc": "crypto/crct10dif_generic.c:82",
      "file": "crypto/crct10dif_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957760,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583958000,
      "name": "chksum_digest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
