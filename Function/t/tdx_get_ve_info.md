# Function: <code>tdx_get_ve_info</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void tdx_get_ve_info(struct ve_info * ve)
```

```json
{
  "name": "tdx_get_ve_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tdx_get_ve_info",
      "external": true,
      "loc": "arch/x86/coco/tdx/tdx.c:542",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_early_handle_ve",
        "arch/x86/kernel/traps.c:exc_virtualization_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593803258,
      "name": "tdx_get_ve_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071578859664,
      "name": "tdx_get_ve_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void tdx_get_ve_info(struct ve_info * ve)
```

```json
{
  "name": "tdx_get_ve_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578861792,
      "name": "tdx_get_ve_info",
      "external": true,
      "loc": "arch/x86/coco/tdx/tdx.c:584",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_early_handle_ve",
        "arch/x86/kernel/traps.c:exc_virtualization_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578861792,
      "name": "tdx_get_ve_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void tdx_get_ve_info(struct ve_info * ve)
```

```json
{
  "name": "tdx_get_ve_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578859632,
      "name": "tdx_get_ve_info",
      "external": true,
      "loc": "arch/x86/coco/tdx/tdx.c:578",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_early_handle_ve",
        "arch/x86/kernel/traps.c:exc_virtualization_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578859632,
      "name": "tdx_get_ve_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void tdx_get_ve_info(struct ve_info * ve)
```

```json
{
  "name": "tdx_get_ve_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578860576,
      "name": "tdx_get_ve_info",
      "external": true,
      "loc": "arch/x86/coco/tdx/tdx.c:603",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_early_handle_ve",
        "arch/x86/kernel/traps.c:exc_virtualization_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578860576,
      "name": "tdx_get_ve_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void tdx_get_ve_info(struct ve_info * ve)
```
</details>
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
