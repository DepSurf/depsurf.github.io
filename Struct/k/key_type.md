# Struct: <code>key_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
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
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
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
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct key_type {
    const char * name;
    size_t def_datalen;
    unsigned int flags;
    int (*)(const char *) vet_description;
    int (*)(struct key_preparsed_payload *) preparse;
    void (*)(struct key_preparsed_payload *) free_preparse;
    int (*)(struct key *, struct key_preparsed_payload *) instantiate;
    int (*)(struct key *, struct key_preparsed_payload *) update;
    int (*)(struct key_match_data *) match_preparse;
    void (*)(struct key_match_data *) match_free;
    void (*)(struct key *) revoke;
    void (*)(struct key *) destroy;
    void (*)(const struct key *, struct seq_file *) describe;
    long int (*)(const struct key *, char *, size_t) read;
    request_key_actor_t request_key;
    struct key_restriction * (*)(const char *) lookup_restriction;
    int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query;
    int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op;
    int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature;
    struct list_head link;
    struct lock_class_key lock_class;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct key_restriction * (*)(const char *) lookup_restriction</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(const struct kernel_pkey_params *, struct kernel_pkey_query *) asym_query</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kernel_pkey_params *, const void *, void *) asym_eds_op</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kernel_pkey_params *, const void *, const void *) asym_verify_signature</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
