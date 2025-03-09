# Function: <code>aa_put_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582470974,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:269",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582478203,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:269",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582492425,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:269",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:aa_change_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582511455,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:269",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__list_remove_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:policy_admin_capable",
        "security/apparmor/policy.c:aa_may_open_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_remove_profiles"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582525318,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:269",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582526826,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:269",
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
      "addr": 18446744071582542896,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:269",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582553829,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:269",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582599280,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:269",
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582694291,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
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
      "addr": 18446744071582710241,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582745633,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582757673,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:__list_remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582764387,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582765057,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
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
      "addr": 18446744071582782914,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582811914,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582824014,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595378125,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582787536,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
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
      "addr": 18446744071582804833,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582840847,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582852862,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:__list_remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582859666,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582860337,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
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
      "addr": 18446744071582878306,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582907681,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582919886,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595626500,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:286",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void aa_put_profile(struct aa_profile * p)
```

```json
{
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582883637,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
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
      "addr": 18446744071582894680,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582921854,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582929686,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582936942,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582937858,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
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
      "addr": 18446744071582947580,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582959144,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
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
      "addr": 18446744071582970760,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582978784,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582957104,
      "name": "aa_put_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583043076,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
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
      "addr": 18446744071583052989,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583081076,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583089906,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583097198,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098139,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
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
      "addr": 18446744071583111393,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602885860,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583134117,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583142667,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:290",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583238619,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
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
      "addr": 18446744071583254040,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583269158,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583292978,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583301104,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583301875,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
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
      "addr": 18446744071583316786,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603058752,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583339012,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583356651,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
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
      "addr": 18446744071583371628,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583387031,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583411346,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583419594,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583420379,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
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
      "addr": 18446744071583433802,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604859544,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583457674,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:298",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583544251,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446744071583558689,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583573480,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583597245,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583605116,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583606153,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446744071583617847,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604964608,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583643355,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583649931,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446744071583664417,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583679736,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583703405,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583711292,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583712329,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446744071583724023,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605000172,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583749643,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584007067,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
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
      "addr": 18446744071584025539,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584043438,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584072601,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:update_to_newest_parent",
        "security/apparmor/policy.c:update_to_newest_parent",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:__aa_profile_list_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584083898,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584084688,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
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
      "addr": 18446744071584107769,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584120952,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584137877,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584147704,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584127931,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
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
      "addr": 18446744071584144963,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584180120,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192009,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:__aa_profile_list_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584203290,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584204048,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
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
      "addr": 18446744071584226201,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584239736,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584257723,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584266088,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584155099,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
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
      "addr": 18446744071584172020,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584207074,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584218897,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:__aa_profile_list_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584229761,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584230628,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
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
      "addr": 18446744071584251756,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584264744,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_remove_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584281265,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584291475,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584539099,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
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
      "addr": 18446744071584556746,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584592386,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584604337,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:__aa_profile_list_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584615392,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584616276,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
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
      "addr": 18446744071584637436,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584650696,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_remove_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584667345,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584677606,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:296",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585191543,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:363",
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
      "addr": 18446744071585199799,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:363",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585240432,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:363",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585253411,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:363",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:__aa_profile_list_release",
        "security/apparmor/policy.c:__aa_profile_list_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585266684,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:363",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585267953,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:363",
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
      "addr": 18446744071585308200,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:363",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585327636,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:363",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:363",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585920503,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:369",
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
      "addr": 18446744071585931445,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:369",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585973353,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:369",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585987267,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:369",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__aa_profile_list_release",
        "security/apparmor/policy.c:__aa_profile_list_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586000973,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:369",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586002428,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:369",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627947801,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:369",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586067924,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:369",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:369",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586094160,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:369",
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586152711,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:400",
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
      "addr": 18446744071586163916,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:400",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586205624,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:400",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586219747,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:400",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__aa_profile_list_release",
        "security/apparmor/policy.c:__aa_profile_list_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586234513,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:400",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586235596,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:400",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619711065,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:400",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586302719,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:400",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586312844,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:400",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586337347,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:400",
      "file": "security/apparmor/notify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:aa_free_listener_proxy",
        "security/apparmor/notify.c:aa_free_listener_proxy"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586401917,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:410",
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
      "addr": 18446744071586412764,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:410",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:audit_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586457732,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:410",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586472307,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:410",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__aa_profile_list_release",
        "security/apparmor/policy.c:__aa_profile_list_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586487764,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:410",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586488847,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:410",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586522053,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:410",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_userns_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622018153,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:410",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586559310,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:410",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586569404,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:410",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586603987,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:410",
      "file": "security/apparmor/notify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:aa_free_listener_proxy",
        "security/apparmor/notify.c:aa_free_listener_proxy"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void aa_put_profile(struct aa_profile * p)
```

```json
{
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495444176,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446603336495457664,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495487716,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495496412,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__remove_profile",
        "security/apparmor/policy.c:__remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495504948,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495505932,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446603336495522220,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495534120,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446603336495550140,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495557936,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495531496,
      "name": "aa_put_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void aa_put_profile(struct aa_profile * p)
```

```json
{
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228810340,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 3228824512,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 3228854688,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 3228864208,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__remove_profile",
        "security/apparmor/policy.c:__remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 3228872748,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3228873544,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 3228888512,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3228899936,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 3228914028,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 3228921200,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228897760,
      "name": "aa_put_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
void aa_put_profile(struct aa_profile * p)
```

```json
{
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289488756,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 13835058055289507948,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289526576,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289562124,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289574492,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289575324,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 13835058055289595080,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289616284,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 13835058055289636980,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289612688,
      "name": "aa_put_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274634914,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446743936274646220,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274671428,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274679668,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__list_remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274687176,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274688000,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446743936274698888,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274709832,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274722142,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274728590,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583618667,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446744071583633153,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583648472,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583672141,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583680028,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583681065,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446744071583692759,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604905632,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583718379,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583555723,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446744071583570209,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583585528,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583609197,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583617084,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583618121,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446744071583629815,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604874684,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583655435,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583602443,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446744071583616929,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583632248,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583655917,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583663804,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583664841,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446744071583676535,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604982804,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583702155,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
  "name": "aa_put_profile",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583699819,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446744071583714796,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583730717,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:find_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583754429,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:aa_fqlookupn_profile",
        "security/apparmor/policy.c:__remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583762444,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583763493,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
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
      "addr": 18446744071583775731,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605004342,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583802421,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "aa_put_profile",
      "external": false,
      "loc": "security/apparmor/include/policy.h:293",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void aa_put_profile(struct aa_profile * p)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void aa_put_profile(struct aa_profile * p)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void aa_put_profile(struct aa_profile * p)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void aa_put_profile(struct aa_profile * p)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void aa_put_profile(struct aa_profile * p)
```
</details>
</li>
</ul>
