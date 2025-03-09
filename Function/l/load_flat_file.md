# Function: <code>load_flat_file</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int load_flat_file(struct linux_binprm * bprm, struct lib_info * libinfo, int id, long unsigned int * extra_stack)
```

```json
{
  "name": "load_flat_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227436948,
      "name": "load_flat_file",
      "external": false,
      "loc": "fs/binfmt_flat.c:425",
      "file": "fs/binfmt_flat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_flat.c:load_flat_binary",
        "fs/binfmt_flat.c:load_flat_shared_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227436948,
      "name": "load_flat_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3228
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int load_flat_file(struct linux_binprm * bprm, struct lib_info * libinfo, int id, long unsigned int * extra_stack)
```

```json
{
  "name": "load_flat_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273493100,
      "name": "load_flat_file",
      "external": false,
      "loc": "fs/binfmt_flat.c:425",
      "file": "fs/binfmt_flat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_flat.c:load_flat_binary",
        "fs/binfmt_flat.c:load_flat_shared_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273493100,
      "name": "load_flat_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2932
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int load_flat_file(struct linux_binprm * bprm, struct lib_info * libinfo, int id, long unsigned int * extra_stack)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int load_flat_file(struct linux_binprm * bprm, struct lib_info * libinfo, int id, long unsigned int * extra_stack)
```
</details>
</li>
</ul>
