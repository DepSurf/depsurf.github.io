# Function: <code>touch_atime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581110560,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1634",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/shmem.c:shmem_mmap",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:SyS_readlink",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_mmap",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110560,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276208,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1651",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:SyS_readlink",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_mmap",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276208,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581354496,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1701",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:SyS_readlink",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_mmap",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581354496,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581409840,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1701",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:SyS_readlink",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_mmap",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409840,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581551424,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1714",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:SyS_readlink",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_mmap",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581551424,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581707488,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1708",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_mmap",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581707488,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581794000,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1715",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_mmap",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794000,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581912592,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1728",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912592,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581985184,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1739",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581985184,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218816,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1823",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_do_get",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_mmap",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_mmap",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218816,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266240,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1824",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_do_get",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_mmap",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_mmap",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_mmap",
        "fs/fuse/dax.c:fuse_dax_mmap",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266240,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582291568,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1832",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:filemap_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_mmap",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_mmap",
        "fs/fuse/dax.c:fuse_dax_mmap",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291568,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582610368,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1837",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:filemap_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_mmap",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_mmap",
        "fs/fuse/dax.c:fuse_dax_mmap",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582610368,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583143264,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1918",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:filemap_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_mmap",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_mmap",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_mmap",
        "fs/fuse/dax.c:fuse_dax_mmap",
        "block/fops.c:blkdev_read_iter",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583143264,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583715232,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1920",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:filemap_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_mmap",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_mmap",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_mmap",
        "fs/fuse/dax.c:fuse_dax_mmap",
        "block/fops.c:blkdev_read_iter",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583715232,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932960,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1964",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:filemap_splice_read",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:filemap_read",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_mmap",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/ext4/file.c:ext4_file_mmap",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_mmap",
        "fs/fuse/dax.c:fuse_dax_mmap",
        "block/fops.c:blkdev_read_iter",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932960,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584139344,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1968",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:filemap_splice_read",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:filemap_read",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_mmap",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/ext4/file.c:ext4_file_mmap",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_mmap",
        "fs/fuse/dax.c:fuse_dax_mmap",
        "block/fops.c:blkdev_read_iter",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584139344,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493496496,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1739",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493496496,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227055764,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1739",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_mmap",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227055764,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287059584,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1739",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287059584,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273171202,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1739",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_mmap",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273171202,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581953920,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1739",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953920,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891488,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1739",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891488,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581945232,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1739",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945232,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void touch_atime(const struct path * path)
```

```json
{
  "name": "touch_atime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015264,
      "name": "touch_atime",
      "external": true,
      "loc": "fs/inode.c:1739",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/filemap.c:generic_file_readonly_mmap",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/stat.c:do_readlinkat",
        "fs/pipe.c:pipe_read",
        "fs/namei.c:trailing_symlink",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:splice_direct_to_actor",
        "fs/splice.c:generic_file_splice_read",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_file_mmap",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015264,
      "name": "touch_atime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
