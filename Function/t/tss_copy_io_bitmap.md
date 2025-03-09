# Function: <code>tss_copy_io_bitmap</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tss_copy_io_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579108402,
      "name": "tss_copy_io_bitmap",
      "external": false,
      "loc": "arch/x86/kernel/process.c:339",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tss_copy_io_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579108226,
      "name": "tss_copy_io_bitmap",
      "external": false,
      "loc": "arch/x86/kernel/process.c:341",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tss_copy_io_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579114839,
      "name": "tss_copy_io_bitmap",
      "external": false,
      "loc": "arch/x86/kernel/process.c:353",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tss_copy_io_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579140135,
      "name": "tss_copy_io_bitmap",
      "external": false,
      "loc": "arch/x86/kernel/process.c:370",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tss_copy_io_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579177671,
      "name": "tss_copy_io_bitmap",
      "external": false,
      "loc": "arch/x86/kernel/process.c:386",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void tss_copy_io_bitmap(struct tss_struct * tss, struct io_bitmap * iobm)
```

```json
{
  "name": "tss_copy_io_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tss_copy_io_bitmap",
      "external": false,
      "loc": "arch/x86/kernel/process.c:386",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230032,
      "name": "tss_copy_io_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071595959794,
      "name": "tss_copy_io_bitmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void tss_copy_io_bitmap(struct tss_struct * tss, struct io_bitmap * iobm)
```

```json
{
  "name": "tss_copy_io_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tss_copy_io_bitmap",
      "external": false,
      "loc": "arch/x86/kernel/process.c:414",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235840,
      "name": "tss_copy_io_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071596477129,
      "name": "tss_copy_io_bitmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void tss_copy_io_bitmap(struct tss_struct * tss, struct io_bitmap * iobm)
```

```json
{
  "name": "tss_copy_io_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tss_copy_io_bitmap",
      "external": false,
      "loc": "arch/x86/kernel/process.c:426",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264688,
      "name": "tss_copy_io_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071597372914,
      "name": "tss_copy_io_bitmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void tss_copy_io_bitmap(struct tss_struct * tss, struct io_bitmap * iobm)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
