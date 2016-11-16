# Laravel 5 Snippets for Sublime Text

[![Latest Version][ico-latest-version]][link-latest-version]
![Laravel Version][ico-laravel-version]
[![Package Control][ico-package-control]][link-package-control]

### 安装
**使用Package Control的方式** :
安装 **Laravel 5 Snippets** 最简单的方式就是使用Sublime的 Package Control,  [http://wbond.net/sublime_packages/package_control](http://wbond.net/sublime_packages/package_control).

```
首选项 -> Package Control -> 输入'Install Package' 回车, 查找 "Laravel 5 Snippets"
```

**用Git的方式** :
Clone the repository in your Sublime Text "Packages"目录:

```
git clone https://github.com/Lykegenes/laravel-5-snippets.git "Laravel 5 Snippets"
```

**其他的方式** :
从github上下载最新版本的源码并把"Laravel 5 Sippets"文件夹整个复制到X:\sublime text\Data\Packages下.

## Usage
The included snippets are organized in categories following Laravel's Facades and their documentation; such as `Auth::`, `Config::` and `Session::`.
This way, you can quickly search for what you'd like to accomplish thanks to Sublime Text fuzzy search.

All the snippets in this package follow the following naming convention : `{category}::{function name}`. For example : `Auth::check` will produce this snippet in your code : `Auth::check()`.

### Included snippets
Here are the available snippet categories and prefixes :

Prefix      | Notes
----------- | -------------
Auth  |
Blade  | Add `, text.html` to the default value of `"auto_complete_selector"` in your Sublime Text settings to allow Snippets autocomplete in Blade files.
Cache  |
Config  |
Console  |
Cookie  |
Crypt  |
DB  | To create raw database queries and transactions.
Event  |
Hash  |
Helper  | Contains sub-categories : `Helper::array`, `Helper::misc`, `Helper::path`, `Helper::strings`, and `Helper::url`; just like in [Laravel's documentation](http://laravel.com/docs/5.1/helpers#available-methods).
Input  |
Log  |
Mail |
Redirect  |
Relation | To create model relationships.
Response  |
Route  |
Schema  | Contains two sub-categories : `Schema::` for snippets related to the database table itself; and `Column::` for snippets related to the columns.
Session  |
Storage  |
View  |


## Credits

- [Patrick Samson][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-package-control]: https://img.shields.io/packagecontrol/dt/Laravel%205%20Snippets.svg
[ico-latest-version]: https://img.shields.io/github/release/lykegenes/laravel-5-snippets.svg
[ico-laravel-version]: https://img.shields.io/badge/Laravel-5.1|5.2-orange.svg

[link-package-control]: https://packagecontrol.io/packages/Laravel%205%20Snippets
[link-latest-version]: https://github.com/Lykegenes/laravel-5-snippets/releases
[link-author]: https://github.com/lykegenes
[link-contributors]: ../../contributors
