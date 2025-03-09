# Function: <code>badblocks_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585725376,
      "name": "badblocks_store",
      "external": false,
      "loc": "drivers/md/md.c:8954",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585725376,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583117440,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:500",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583117440,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583229360,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:525",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229360,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583283392,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:525",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583283392,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583463632,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:525",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463632,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583676224,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:525",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583676224,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583783504,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:525",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583783504,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583973280,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:517",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583973280,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584076640,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:517",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076640,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584466880,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:517",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584466880,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581904,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:517",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581904,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584613984,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:517",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584613984,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585028480,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:517",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585028480,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585745520,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:515",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585745520,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586527952,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:515",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586527952,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586774144,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:515",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586774144,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587052064,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:1547",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052064,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495918016,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:517",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495918016,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229262180,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:517",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229262180,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290129856,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:517",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290129856,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275031278,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:517",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275031278,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584045376,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:517",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584045376,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583981136,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:517",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583981136,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584029136,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:517",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584029136,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
ssize_t badblocks_store(struct badblocks * bb, const char * page, size_t len, int unack)
```

```json
{
  "name": "badblocks_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584131632,
      "name": "badblocks_store",
      "external": true,
      "loc": "block/badblocks.c:517",
      "file": "block/badblocks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_badblocks_store",
        "drivers/md/md.c:ubb_store",
        "drivers/md/md.c:bb_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584131632,
      "name": "badblocks_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
