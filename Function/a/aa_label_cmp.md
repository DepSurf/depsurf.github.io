# Function: <code>aa_label_cmp</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int aa_label_cmp(struct aa_label * a, struct aa_label * b)
```

```json
{
  "name": "aa_label_cmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586052718,
      "name": "aa_label_cmp",
      "external": true,
      "loc": "security/apparmor/label.c:466",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586055248,
      "name": "aa_label_cmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int aa_label_cmp(struct aa_label * a, struct aa_label * b)
```

```json
{
  "name": "aa_label_cmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586287801,
      "name": "aa_label_cmp",
      "external": true,
      "loc": "security/apparmor/label.c:466",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586290272,
      "name": "aa_label_cmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int aa_label_cmp(struct aa_label * a, struct aa_label * b)
```

```json
{
  "name": "aa_label_cmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586544457,
      "name": "aa_label_cmp",
      "external": true,
      "loc": "security/apparmor/label.c:472",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586546944,
      "name": "aa_label_cmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int aa_label_cmp(struct aa_label * a, struct aa_label * b)
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
