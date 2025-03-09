# Function: <code>klp_is_patch_compatible</code>

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
bool klp_is_patch_compatible(struct klp_patch * patch)
```

```json
{
  "name": "klp_is_patch_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580139744,
      "name": "klp_is_patch_compatible",
      "external": true,
      "loc": "kernel/livepatch/state.c:106",
      "file": "kernel/livepatch/state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580139744,
      "name": "klp_is_patch_compatible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
bool klp_is_patch_compatible(struct klp_patch * patch)
```

```json
{
  "name": "klp_is_patch_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580116976,
      "name": "klp_is_patch_compatible",
      "external": true,
      "loc": "kernel/livepatch/state.c:106",
      "file": "kernel/livepatch/state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580116976,
      "name": "klp_is_patch_compatible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
bool klp_is_patch_compatible(struct klp_patch * patch)
```

```json
{
  "name": "klp_is_patch_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580120544,
      "name": "klp_is_patch_compatible",
      "external": true,
      "loc": "kernel/livepatch/state.c:106",
      "file": "kernel/livepatch/state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120544,
      "name": "klp_is_patch_compatible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
bool klp_is_patch_compatible(struct klp_patch * patch)
```

```json
{
  "name": "klp_is_patch_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_is_patch_compatible",
      "external": true,
      "loc": "kernel/livepatch/state.c:106",
      "file": "kernel/livepatch/state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592148925,
      "name": "klp_is_patch_compatible.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580263088,
      "name": "klp_is_patch_compatible",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool klp_is_patch_compatible(struct klp_patch * patch)
```

```json
{
  "name": "klp_is_patch_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_is_patch_compatible",
      "external": true,
      "loc": "kernel/livepatch/state.c:106",
      "file": "kernel/livepatch/state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593921485,
      "name": "klp_is_patch_compatible.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580433040,
      "name": "klp_is_patch_compatible",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool klp_is_patch_compatible(struct klp_patch * patch)
```

```json
{
  "name": "klp_is_patch_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_is_patch_compatible",
      "external": true,
      "loc": "kernel/livepatch/state.c:106",
      "file": "kernel/livepatch/state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595992690,
      "name": "klp_is_patch_compatible.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580675216,
      "name": "klp_is_patch_compatible",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool klp_is_patch_compatible(struct klp_patch * patch)
```

```json
{
  "name": "klp_is_patch_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_is_patch_compatible",
      "external": true,
      "loc": "kernel/livepatch/state.c:106",
      "file": "kernel/livepatch/state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596510950,
      "name": "klp_is_patch_compatible.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580751552,
      "name": "klp_is_patch_compatible",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool klp_is_patch_compatible(struct klp_patch * patch)
```

```json
{
  "name": "klp_is_patch_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_is_patch_compatible",
      "external": true,
      "loc": "kernel/livepatch/state.c:106",
      "file": "kernel/livepatch/state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597409823,
      "name": "klp_is_patch_compatible.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580836672,
      "name": "klp_is_patch_compatible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
bool klp_is_patch_compatible(struct klp_patch * patch)
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
