# Function: <code>aa_label_destroy</code>

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
void aa_label_destroy(struct aa_label * label)
```

```json
{
  "name": "aa_label_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584124432,
      "name": "aa_label_destroy",
      "external": true,
      "loc": "security/apparmor/label.c:312",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124432,
      "name": "aa_label_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void aa_label_destroy(struct aa_label * label)
```

```json
{
  "name": "aa_label_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584243152,
      "name": "aa_label_destroy",
      "external": true,
      "loc": "security/apparmor/label.c:312",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584243152,
      "name": "aa_label_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void aa_label_destroy(struct aa_label * label)
```

```json
{
  "name": "aa_label_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584266080,
      "name": "aa_label_destroy",
      "external": true,
      "loc": "security/apparmor/label.c:312",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584266080,
      "name": "aa_label_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void aa_label_destroy(struct aa_label * label)
```

```json
{
  "name": "aa_label_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584652096,
      "name": "aa_label_destroy",
      "external": true,
      "loc": "security/apparmor/label.c:312",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584652096,
      "name": "aa_label_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void aa_label_destroy(struct aa_label * label)
```

```json
{
  "name": "aa_label_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585311920,
      "name": "aa_label_destroy",
      "external": true,
      "loc": "security/apparmor/label.c:315",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311920,
      "name": "aa_label_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void aa_label_destroy(struct aa_label * label)
```

```json
{
  "name": "aa_label_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586051312,
      "name": "aa_label_destroy",
      "external": true,
      "loc": "security/apparmor/label.c:315",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586051312,
      "name": "aa_label_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void aa_label_destroy(struct aa_label * label)
```

```json
{
  "name": "aa_label_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586286400,
      "name": "aa_label_destroy",
      "external": true,
      "loc": "security/apparmor/label.c:315",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586286400,
      "name": "aa_label_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void aa_label_destroy(struct aa_label * label)
```

```json
{
  "name": "aa_label_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586543056,
      "name": "aa_label_destroy",
      "external": true,
      "loc": "security/apparmor/label.c:321",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586543056,
      "name": "aa_label_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void aa_label_destroy(struct aa_label * label)
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
