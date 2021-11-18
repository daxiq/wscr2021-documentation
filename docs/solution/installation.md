---
sidebar_position: 1
---

# 00. Installing Laravel

Once XAMPP and Composer are installed in the machine, run the next command:

```shell
composer create-project laravel/laravel designpro
```

This command will download the latest version of Laravel (8.x at Nov 2021). In order to donwload a different version of laravel, the command must contain the flags indicating the files to donwload are from another version.
Ex:

```shell
composer create-project --prefer-dist laravel/laravel:^7.0 old-version-project
```

More inforamtion at the official **[Laravel documentation](https://laravel.com/docs/master/installation)**.