# Function: <code>collect_domain_accesses</code>

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
bool collect_domain_accesses(const const struct landlock_ruleset * domain, const const struct dentry * mnt_root, struct dentry * dir, const layer_mask_t[14] * layer_masks_dom)
```

```json
{
  "name": "collect_domain_accesses",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "collect_domain_accesses",
      "external": false,
      "loc": "security/landlock/fs.c:715",
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
      "addr": 18446744071585371888,
      "name": "collect_domain_accesses",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 965
    },
    {
      "addr": 18446744071594089167,
      "name": "collect_domain_accesses.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
bool collect_domain_accesses(const const struct landlock_ruleset * domain, const const struct dentry * mnt_root, struct dentry * dir, const layer_mask_t[15] * layer_masks_dom)
```

```json
{
  "name": "collect_domain_accesses",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "collect_domain_accesses",
      "external": false,
      "loc": "security/landlock/fs.c:717",
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
      "addr": 18446744071586123168,
      "name": "collect_domain_accesses",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
    },
    {
      "addr": 18446744071596101394,
      "name": "collect_domain_accesses.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
bool collect_domain_accesses(const const struct landlock_ruleset * domain, const const struct dentry * mnt_root, struct dentry * dir, const layer_mask_t[15] * layer_masks_dom)
```

```json
{
  "name": "collect_domain_accesses",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "collect_domain_accesses",
      "external": false,
      "loc": "security/landlock/fs.c:717",
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
      "addr": 18446744071586361920,
      "name": "collect_domain_accesses",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 941
    },
    {
      "addr": 18446744071596624608,
      "name": "collect_domain_accesses.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
bool collect_domain_accesses(const const struct landlock_ruleset * domain, const const struct dentry * mnt_root, struct dentry * dir, const layer_mask_t[15] * layer_masks_dom)
```

```json
{
  "name": "collect_domain_accesses",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586634256,
      "name": "collect_domain_accesses",
      "external": false,
      "loc": "security/landlock/fs.c:633",
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
      "addr": 18446744071586634256,
      "name": "collect_domain_accesses",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
bool collect_domain_accesses(const const struct landlock_ruleset * domain, const const struct dentry * mnt_root, struct dentry * dir, const layer_mask_t[14] * layer_masks_dom)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const layer_mask_t[14] * layer_masks_dom</code> ➡️ <code>const layer_mask_t[15] * layer_masks_dom</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
