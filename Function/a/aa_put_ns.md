# Function: <code>aa_put_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582470964,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:121",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582513453,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:121",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:policy_admin_capable",
        "security/apparmor/policy.c:aa_may_open_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582526808,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:121",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582542887,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:121",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582568921,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:121",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_printk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582599271,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:121",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns",
        "security/apparmor/policy_ns.c:aa_free_root_ns"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582694281,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:123",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_rmdir_op",
        "security/apparmor/apparmorfs.c:ns_rmdir_op",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582755071,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:123",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582765048,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:123",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582782905,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:123",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582811166,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:123",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595378116,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:123",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns",
        "security/apparmor/policy_ns.c:aa_free_ns"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582787526,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_rmdir_op",
        "security/apparmor/apparmorfs.c:ns_rmdir_op",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582852853,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582860328,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582878297,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582906878,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595626491,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns",
        "security/apparmor/policy_ns.c:aa_free_ns"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582883628,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_readlink",
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582929677,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582935294,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582937848,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947570,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596558402,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582970090,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583043067,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_readlink",
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583089897,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095428,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098130,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583111383,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602885856,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583133323,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583238609,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583292969,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583295284,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583301866,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583316776,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603058748,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583338976,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583356641,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583411337,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583413764,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583420370,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583433792,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604859540,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583457638,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:130",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583544241,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583597235,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583599444,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583606144,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583617838,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604964604,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583643346,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583649921,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583703395,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583705604,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583712320,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583724014,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605000168,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583749634,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void aa_put_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584007057,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584072673,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584076510,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584084679,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584107760,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584120948,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns"
      ]
    },
    {
      "addr": 18446744071584137868,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584118096,
      "name": "aa_put_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void aa_put_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584127921,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192081,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584195902,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584204039,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584226192,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584239732,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns"
      ]
    },
    {
      "addr": 18446744071584256316,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237040,
      "name": "aa_put_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void aa_put_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584155089,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584218969,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584222778,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584230619,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584251747,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584264740,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_remove_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns"
      ]
    },
    {
      "addr": 18446744071584281256,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584262080,
      "name": "aa_put_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void aa_put_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584539089,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584604409,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584608218,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584616267,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584637427,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584650692,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_remove_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns"
      ]
    },
    {
      "addr": 18446744071584667336,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584648032,
      "name": "aa_put_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void aa_put_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585191533,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:127",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585253485,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:127",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585256590,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:127",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585267943,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:127",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585308196,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:127",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns"
      ]
    },
    {
      "addr": 18446744071585326255,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:127",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585305168,
      "name": "aa_put_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void aa_put_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585920493,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:138",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585987341,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:138",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585990702,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:138",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586002418,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:138",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ]
    },
    {
      "addr": 18446744071627947797,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:138",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586066543,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:138",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586094151,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:138",
      "file": "security/apparmor/notify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:aa_free_listener_proxy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586001920,
      "name": "aa_put_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void aa_put_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586152701,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:138",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586219821,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:138",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586223790,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:138",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586235586,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:138",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ]
    },
    {
      "addr": 18446744071619711061,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:138",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586301407,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:138",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586337338,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:138",
      "file": "security/apparmor/notify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:aa_free_listener_proxy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235088,
      "name": "aa_put_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void aa_put_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586401907,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:135",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586472381,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:135",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586476494,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:135",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586488837,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:135",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ]
    },
    {
      "addr": 18446744071622018149,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:135",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586557999,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:135",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586603978,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:135",
      "file": "security/apparmor/notify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:aa_free_listener_proxy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586488336,
      "name": "aa_put_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495444168,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495496404,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495498948,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495505924,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495522212,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511044112,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495549084,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228810328,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 3228864196,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 3228866888,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3228873536,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 3228888500,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3243525756,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 3228912804,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289488704,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289562116,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289566568,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289575316,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289595072,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302718860,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289636924,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
void aa_put_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274634906,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274679664,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274680286,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274687992,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274698880,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274709830,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns"
      ]
    },
    {
      "addr": 18446743936274721372,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274707818,
      "name": "aa_put_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583618657,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583672131,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583674340,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583681056,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583692750,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604905628,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583718370,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583555713,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583609187,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583611396,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583618112,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583629806,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604874680,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583655426,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583602433,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583655907,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583658116,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583664832,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583676526,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604982800,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583702146,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583699809,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:ns_revision_release",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_replace",
        "security/apparmor/apparmorfs.c:profile_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583754419,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583756628,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583763484,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583775722,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605004338,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583802412,
      "name": "aa_put_ns",
      "external": false,
      "loc": "security/apparmor/include/policy_ns.h:126",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void aa_put_ns(struct aa_ns * ns)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void aa_put_ns(struct aa_ns * ns)
```
</details>
</li>
</ul>
