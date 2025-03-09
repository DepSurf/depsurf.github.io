# Function: <code>cec_notifier_register</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void cec_notifier_register(struct cec_notifier * n, struct cec_adapter * adap, void (*)(struct cec_adapter *, u16) callback)
```

```json
{
  "name": "cec_notifier_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587270144,
      "name": "cec_notifier_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:109",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_register_cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587270144,
      "name": "cec_notifier_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void cec_notifier_register(struct cec_notifier * n, struct cec_adapter * adap, void (*)(struct cec_adapter *, u16) callback)
```

```json
{
  "name": "cec_notifier_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587539568,
      "name": "cec_notifier_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:200",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_register_cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587539568,
      "name": "cec_notifier_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void cec_notifier_register(struct cec_notifier * n, struct cec_adapter * adap, void (*)(struct cec_adapter *, u16) callback)
```

```json
{
  "name": "cec_notifier_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587742352,
      "name": "cec_notifier_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:200",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_register_cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587742352,
      "name": "cec_notifier_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
void cec_notifier_register(struct cec_notifier * n, struct cec_adapter * adap, void (*)(struct cec_adapter *, u16) callback)
```

```json
{
  "name": "cec_notifier_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500917568,
      "name": "cec_notifier_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:200",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_register_cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500917568,
      "name": "cec_notifier_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void cec_notifier_register(struct cec_notifier * n, struct cec_adapter * adap, void (*)(struct cec_adapter *, u16) callback)
```

```json
{
  "name": "cec_notifier_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233435760,
      "name": "cec_notifier_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:200",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_register_cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233435760,
      "name": "cec_notifier_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void cec_notifier_register(struct cec_notifier * n, struct cec_adapter * adap, void (*)(struct cec_adapter *, u16) callback)
```

```json
{
  "name": "cec_notifier_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294377552,
      "name": "cec_notifier_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:200",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_register_cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294377552,
      "name": "cec_notifier_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void cec_notifier_register(struct cec_notifier * n, struct cec_adapter * adap, void (*)(struct cec_adapter *, u16) callback)
```

```json
{
  "name": "cec_notifier_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277692712,
      "name": "cec_notifier_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:200",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_register_cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277692712,
      "name": "cec_notifier_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void cec_notifier_register(struct cec_notifier * n, struct cec_adapter * adap, void (*)(struct cec_adapter *, u16) callback)
```

```json
{
  "name": "cec_notifier_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587383296,
      "name": "cec_notifier_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:200",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_register_cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587383296,
      "name": "cec_notifier_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void cec_notifier_register(struct cec_notifier * n, struct cec_adapter * adap, void (*)(struct cec_adapter *, u16) callback)
```

```json
{
  "name": "cec_notifier_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587151520,
      "name": "cec_notifier_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:200",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_register_cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587151520,
      "name": "cec_notifier_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void cec_notifier_register(struct cec_notifier * n, struct cec_adapter * adap, void (*)(struct cec_adapter *, u16) callback)
```

```json
{
  "name": "cec_notifier_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587698496,
      "name": "cec_notifier_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:200",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_register_cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587698496,
      "name": "cec_notifier_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void cec_notifier_register(struct cec_notifier * n, struct cec_adapter * adap, void (*)(struct cec_adapter *, u16) callback)
```

```json
{
  "name": "cec_notifier_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587804928,
      "name": "cec_notifier_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:200",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_register_cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587804928,
      "name": "cec_notifier_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void cec_notifier_register(struct cec_notifier * n, struct cec_adapter * adap, void (*)(struct cec_adapter *, u16) callback)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void cec_notifier_register(struct cec_notifier * n, struct cec_adapter * adap, void (*)(struct cec_adapter *, u16) callback)
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
