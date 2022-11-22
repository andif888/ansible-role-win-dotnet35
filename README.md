# ansible-role-win-dotnet35

Ansible Role to enable .Net 3.5 Feature in Windows Server

## Table of content

- [Default Variables](#default-variables)
  - [windows_server_extract_dir](#windows_server_extract_dir)
  - [windows_server_iso_file_path](#windows_server_iso_file_path)
  - [windows_server_iso_url](#windows_server_iso_url)
  - [windows_server_iso_url_validate_certs](#windows_server_iso_url_validate_certs)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### windows_server_extract_dir

Directory to extract ISO contents.

#### Default value

```YAML
windows_server_extract_dir: C:\windows\temp\windows_server_extract
```

### windows_server_iso_file_path

Resulting path of the download ISO.

#### Default value

```YAML
windows_server_iso_file_path: '{{ windows_server_extract_dir }}\windows_server.iso'
```

### windows_server_iso_url

Download-URL of the windows ISO

#### Default value

```YAML
windows_server_iso_url: https://localhost/en_windows_server_2012_r2_with_update_x64_dvd_6052708.iso
```

### windows_server_iso_url_validate_certs

Validate SSL certs when downloading ISO.

#### Default value

```YAML
windows_server_iso_url_validate_certs: yes
```



## Dependencies

None.

## License

license (GPLv2, CC-BY, etc)

## Author

andif888
