# Function: <code>__bio_crypt_advance</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __bio_crypt_advance(struct bio * bio, unsigned int bytes)
```

```json
{
  "name": "__bio_crypt_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584618944,
      "name": "__bio_crypt_advance",
      "external": true,
      "loc": "block/blk-crypto.c:124",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618944,
      "name": "__bio_crypt_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void __bio_crypt_advance(struct bio * bio, unsigned int bytes)
```

```json
{
  "name": "__bio_crypt_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584737712,
      "name": "__bio_crypt_advance",
      "external": true,
      "loc": "block/blk-crypto.c:135",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737712,
      "name": "__bio_crypt_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void __bio_crypt_advance(struct bio * bio, unsigned int bytes)
```

```json
{
  "name": "__bio_crypt_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584765824,
      "name": "__bio_crypt_advance",
      "external": true,
      "loc": "block/blk-crypto.c:135",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765824,
      "name": "__bio_crypt_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __bio_crypt_advance(struct bio * bio, unsigned int bytes)
```

```json
{
  "name": "__bio_crypt_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bio_crypt_advance",
      "external": true,
      "loc": "block/blk-crypto.c:135",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592322658,
      "name": "__bio_crypt_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071585194576,
      "name": "__bio_crypt_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __bio_crypt_advance(struct bio * bio, unsigned int bytes)
```

```json
{
  "name": "__bio_crypt_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bio_crypt_advance",
      "external": true,
      "loc": "block/blk-crypto.c:137",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594107286,
      "name": "__bio_crypt_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071585929344,
      "name": "__bio_crypt_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __bio_crypt_advance(struct bio * bio, unsigned int bytes)
```

```json
{
  "name": "__bio_crypt_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bio_crypt_advance",
      "external": true,
      "loc": "block/blk-crypto.c:143",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596110793,
      "name": "__bio_crypt_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586720272,
      "name": "__bio_crypt_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __bio_crypt_advance(struct bio * bio, unsigned int bytes)
```

```json
{
  "name": "__bio_crypt_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bio_crypt_advance",
      "external": true,
      "loc": "block/blk-crypto.c:144",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596635150,
      "name": "__bio_crypt_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586982800,
      "name": "__bio_crypt_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __bio_crypt_advance(struct bio * bio, unsigned int bytes)
```

```json
{
  "name": "__bio_crypt_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bio_crypt_advance",
      "external": true,
      "loc": "block/blk-crypto.c:144",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597542966,
      "name": "__bio_crypt_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587264544,
      "name": "__bio_crypt_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __bio_crypt_advance(struct bio * bio, unsigned int bytes)
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
