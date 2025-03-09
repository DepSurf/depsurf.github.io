# Struct: <code>policydb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    struct flex_array *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct flex_array * type_val_to_struct_array;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[7] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct flex_array * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    struct flex_array *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct flex_array * type_val_to_struct_array;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[7] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct flex_array * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    struct flex_array *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct flex_array * type_val_to_struct_array;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[7] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct flex_array * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    struct flex_array *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct flex_array * type_val_to_struct_array;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct flex_array * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    struct flex_array *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct flex_array * type_val_to_struct_array;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct flex_array * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    struct flex_array *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct flex_array * type_val_to_struct_array;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct flex_array * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    struct flex_array *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct flex_array * type_val_to_struct_array;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct flex_array * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct_array;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct hashtab role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab filename_trans;
    u32 compat_filename_trans_count;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    u32 cond_list_len;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct hashtab role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab filename_trans;
    u32 compat_filename_trans_count;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    u32 cond_list_len;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct hashtab role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab filename_trans;
    u32 compat_filename_trans_count;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    u32 cond_list_len;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct hashtab role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab filename_trans;
    u32 compat_filename_trans_count;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    u32 cond_list_len;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct hashtab role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab filename_trans;
    u32 compat_filename_trans_count;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    u32 cond_list_len;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct hashtab role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab filename_trans;
    u32 compat_filename_trans_count;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    u32 cond_list_len;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct hashtab role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab filename_trans;
    u32 compat_filename_trans_count;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    u32 cond_list_len;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct hashtab role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab filename_trans;
    u32 compat_filename_trans_count;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    u32 cond_list_len;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
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
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
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
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct policydb {
    int mls_enabled;
    struct symtab[8] symtab;
    char * *[8] sym_val_to_name;
    struct class_datum * * class_val_to_struct;
    struct role_datum * * role_val_to_struct;
    struct user_datum * * user_val_to_struct;
    struct type_datum * * type_val_to_struct;
    struct avtab te_avtab;
    struct role_trans * role_tr;
    struct ebitmap filename_trans_ttypes;
    struct hashtab * filename_trans;
    struct cond_bool_datum * * bool_val_to_struct;
    struct avtab te_cond_avtab;
    struct cond_node * cond_list;
    struct role_allow * role_allow;
    struct ocontext *[9] ocontexts;
    struct genfs * genfs;
    struct hashtab * range_tr;
    struct ebitmap * type_attr_map_array;
    struct ebitmap policycaps;
    struct ebitmap permissive_map;
    size_t len;
    unsigned int policyvers;
    unsigned int reject_unknown;
    unsigned int allow_unknown;
    u16 process_class;
    u32 process_trans_perms;
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
<b>Field type changed. </b>
<code>struct ocontext *[7] ocontexts</code> ➡️ <code>struct ocontext *[9] ocontexts</code>
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct flex_array *[8] sym_val_to_name</code> ➡️ <code>char * *[8] sym_val_to_name</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct flex_array * type_val_to_struct_array</code> ➡️ <code>struct type_datum * * type_val_to_struct_array</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct flex_array * type_attr_map_array</code> ➡️ <code>struct ebitmap * type_attr_map_array</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct type_datum * * type_val_to_struct</code>
</li>
<li>
<b>Field removed. </b>
<code>struct type_datum * * type_val_to_struct_array</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 compat_filename_trans_count</code>
</li>
<li>
<b>Field added. </b>
<code>u32 cond_list_len</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct role_trans * role_tr</code> ➡️ <code>struct hashtab role_tr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct hashtab * filename_trans</code> ➡️ <code>struct hashtab filename_trans</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct hashtab * range_tr</code> ➡️ <code>struct hashtab range_tr</code>
</li>
</ul>
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
