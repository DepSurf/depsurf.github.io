# Function: <code>sg_copy_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583016160,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:649",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_copy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_pcopy_to_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016160,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583307104,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:649",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583307104,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583426432,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:649",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583426432,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583447440,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:649",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447440,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583627568,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:690",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583627568,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583843856,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:805",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583843856,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583927552,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:805",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927552,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584107440,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:840",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584107440,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584230640,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:840",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230640,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584636720,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:840",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584636720,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584755728,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:921",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584755728,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584785360,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:921",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584785360,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585215792,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:951",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215792,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586053472,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:948",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586053472,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587037472,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:958",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587037472,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587292528,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:960",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587292528,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587578352,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:962",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587578352,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496105624,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:840",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496105624,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229430520,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:840",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229430520,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290352736,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:840",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290352736,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275171906,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:840",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275171906,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584199376,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:840",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584199376,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584134592,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:840",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584134592,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584183136,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:840",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584183136,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
size_t sg_copy_buffer(struct scatterlist * sgl, unsigned int nents, void * buf, size_t buflen, off_t skip, bool to_buffer)
```

```json
{
  "name": "sg_copy_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584287488,
      "name": "sg_copy_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:840",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_pcopy_to_buffer",
        "lib/scatterlist.c:sg_pcopy_from_buffer",
        "lib/scatterlist.c:sg_copy_to_buffer",
        "lib/scatterlist.c:sg_copy_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584287488,
      "name": "sg_copy_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
