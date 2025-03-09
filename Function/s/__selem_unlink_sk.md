# Function: <code>__selem_unlink_sk</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool __selem_unlink_sk(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_elem * selem, bool uncharge_omem)
```

```json
{
  "name": "__selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588621088,
      "name": "__selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:144",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_unlink_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588621088,
      "name": "__selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
bool __selem_unlink_sk(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_elem * selem, bool uncharge_omem)
```

```json
{
  "name": "__selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588843120,
      "name": "__selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:147",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_unlink_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588843120,
      "name": "__selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
bool __selem_unlink_sk(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_elem * selem, bool uncharge_omem)
```

```json
{
  "name": "__selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589726992,
      "name": "__selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:148",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_unlink_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589726992,
      "name": "__selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool __selem_unlink_sk(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_elem * selem, bool uncharge_omem)
```

```json
{
  "name": "__selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502416800,
      "name": "__selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:147",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_unlink_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502416800,
      "name": "__selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
bool __selem_unlink_sk(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_elem * selem, bool uncharge_omem)
```

```json
{
  "name": "__selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235151688,
      "name": "__selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:147",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_unlink_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235151688,
      "name": "__selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
bool __selem_unlink_sk(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_elem * selem, bool uncharge_omem)
```

```json
{
  "name": "__selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295967472,
      "name": "__selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:147",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_unlink_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295967472,
      "name": "__selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
bool __selem_unlink_sk(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_elem * selem, bool uncharge_omem)
```

```json
{
  "name": "__selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278622100,
      "name": "__selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:147",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_unlink_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278622100,
      "name": "__selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
bool __selem_unlink_sk(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_elem * selem, bool uncharge_omem)
```

```json
{
  "name": "__selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588449504,
      "name": "__selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:147",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_unlink_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588449504,
      "name": "__selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
bool __selem_unlink_sk(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_elem * selem, bool uncharge_omem)
```

```json
{
  "name": "__selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588162192,
      "name": "__selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:147",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_unlink_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588162192,
      "name": "__selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
bool __selem_unlink_sk(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_elem * selem, bool uncharge_omem)
```

```json
{
  "name": "__selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588781680,
      "name": "__selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:147",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_unlink_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588781680,
      "name": "__selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
bool __selem_unlink_sk(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_elem * selem, bool uncharge_omem)
```

```json
{
  "name": "__selem_unlink_sk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588922272,
      "name": "__selem_unlink_sk",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:147",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_unlink_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588922272,
      "name": "__selem_unlink_sk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool __selem_unlink_sk(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_elem * selem, bool uncharge_omem)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
bool __selem_unlink_sk(struct bpf_sk_storage * sk_storage, struct bpf_sk_storage_elem * selem, bool uncharge_omem)
```
</details>
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
