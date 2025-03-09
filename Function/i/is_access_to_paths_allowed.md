# Function: <code>is_access_to_paths_allowed</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool is_access_to_paths_allowed(const const struct landlock_ruleset * domain, const const struct path * path, const access_mask_t access_request_parent1, const layer_mask_t[15] * layer_masks_parent1, const const struct dentry * dentry_child1, const access_mask_t access_request_parent2, const layer_mask_t[15] * layer_masks_parent2, const const struct dentry * dentry_child2)
```

```json
{
  "name": "is_access_to_paths_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "is_access_to_paths_allowed",
      "external": false,
      "loc": "security/landlock/fs.c:485",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:hook_file_open",
        "security/landlock/fs.c:hook_path_truncate",
        "security/landlock/fs.c:hook_path_rmdir",
        "security/landlock/fs.c:hook_path_unlink",
        "security/landlock/fs.c:hook_path_symlink",
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:hook_path_mkdir",
        "security/landlock/fs.c:current_check_refer_path",
        "security/landlock/fs.c:current_check_refer_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586124176,
      "name": "is_access_to_paths_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4526
    },
    {
      "addr": 18446744071596101529,
      "name": "is_access_to_paths_allowed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
bool is_access_to_paths_allowed(const const struct landlock_ruleset * domain, const const struct path * path, const access_mask_t access_request_parent1, const layer_mask_t[15] * layer_masks_parent1, const const struct dentry * dentry_child1, const access_mask_t access_request_parent2, const layer_mask_t[15] * layer_masks_parent2, const const struct dentry * dentry_child2)
```

```json
{
  "name": "is_access_to_paths_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "is_access_to_paths_allowed",
      "external": false,
      "loc": "security/landlock/fs.c:485",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:hook_file_open",
        "security/landlock/fs.c:hook_path_truncate",
        "security/landlock/fs.c:hook_path_rmdir",
        "security/landlock/fs.c:hook_path_unlink",
        "security/landlock/fs.c:hook_path_symlink",
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:hook_path_mkdir",
        "security/landlock/fs.c:current_check_refer_path",
        "security/landlock/fs.c:current_check_refer_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586362880,
      "name": "is_access_to_paths_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4487
    },
    {
      "addr": 18446744071596624739,
      "name": "is_access_to_paths_allowed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
bool is_access_to_paths_allowed(const const struct landlock_ruleset * domain, const const struct path * path, const access_mask_t access_request_parent1, const layer_mask_t[15] * layer_masks_parent1, const const struct dentry * dentry_child1, const access_mask_t access_request_parent2, const layer_mask_t[15] * layer_masks_parent2, const const struct dentry * dentry_child2)
```

```json
{
  "name": "is_access_to_paths_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586631088,
      "name": "is_access_to_paths_allowed",
      "external": false,
      "loc": "security/landlock/fs.c:396",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:hook_file_open",
        "security/landlock/fs.c:hook_file_open",
        "security/landlock/fs.c:current_check_refer_path",
        "security/landlock/fs.c:current_check_refer_path",
        "security/landlock/fs.c:check_access_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586631088,
      "name": "is_access_to_paths_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1819
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
bool is_access_to_paths_allowed(const const struct landlock_ruleset * domain, const const struct path * path, const access_mask_t access_request_parent1, const layer_mask_t[15] * layer_masks_parent1, const const struct dentry * dentry_child1, const access_mask_t access_request_parent2, const layer_mask_t[15] * layer_masks_parent2, const const struct dentry * dentry_child2)
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
