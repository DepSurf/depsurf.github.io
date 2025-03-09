# Function: <code>is_eacces</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_eacces",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585373854,
      "name": "is_eacces",
      "external": false,
      "loc": "security/landlock/fs.c:408",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:check_access_path_dual",
        "security/landlock/fs.c:check_access_path_dual"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_eacces",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586130820,
      "name": "is_eacces",
      "external": false,
      "loc": "security/landlock/fs.c:428",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:current_check_refer_path",
        "security/landlock/fs.c:current_check_refer_path"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_eacces",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586369625,
      "name": "is_eacces",
      "external": false,
      "loc": "security/landlock/fs.c:428",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:current_check_refer_path",
        "security/landlock/fs.c:current_check_refer_path"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool is_eacces(const const layer_mask_t[15] * layer_masks, const access_mask_t access_request)
```

```json
{
  "name": "is_eacces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586634048,
      "name": "is_eacces",
      "external": false,
      "loc": "security/landlock/fs.c:339",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:current_check_refer_path",
        "security/landlock/fs.c:current_check_refer_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586634048,
      "name": "is_eacces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
bool is_eacces(const const layer_mask_t[15] * layer_masks, const access_mask_t access_request)
```
</details>
</li>
</ul>
