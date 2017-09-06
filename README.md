# sublime-init
Sublime 编辑器初始化，常用插件，主题，字体等设置.

## 插件
- BracketHighlighter
- phpfmt
```
{
	"version": 1,
    "php_bin": "/usr/local/Cellar/php70/7.0.22_14/bin/php", // Path for PHP executable, e.g. "/usr/lib/php" or "C:/Program Files/PHP/php.exe". If empty, uses command "php" from system environments
    "indent_with_space": true,
    "smart_linebreak_after_curly": true,
    "psr1": true, // Activate PSR1 style
    "psr1_naming": true, // Activate PSR1 style - Section 3 and 4.3 - Class and method names case
    "psr2": true, // Activate PSR2 style
    "format_on_save": false, // Format on save. Either a boolean (true/false) or a string regexp tested on filename. Example : "^((?!.min.|vendor).)*$"
    "enable_auto_align": true, // Enable auto align of = and =>
    "indent_with_space": 4, // Use spaces instead of tabs for indentation
    "visibility_order": true, // Fixes visibility order for method in classes - PSR-2 4.2
    "smart_linebreak_after_curly": true, // Convert multistatement blocks into multiline blocks

    // "syntaxes": "php", // Syntax names which must process PHP formatter


    // Enable specific transformations. Example: ["ConvertOpenTagWithEcho", "PrettyPrintDocBlocks"]
    // You can list all available transformations from command palette: CodeFormatter: Show PHP Transformations
    // You can also see examples of many transformations at https://github.com/akalongman/sublimetext-codeformatter/blob/master/PHP-Transformations.md
    "passes": [
        "AlignDoubleSlashComments", "AlignEquals", "AlignGroupDoubleArrow",
        "AlignTypehint", "DoubleToSingleQuote",
        "GeneratePHPDoc", "IndentTernaryConditions", "NoSpaceAfterPHPDocBlocks",
        "ReindentAndAlignObjOps", "ReindentSwitchBlocks", "ShortArray", 
        "SpaceBetweenMethods", 
        "StripNewlineAfterClassOpen",
    ],

    // Disable specific transformations
    "excludes": []
}
```
- php-cs-fixer
- jsFormat
- Docblockr

## Sublime Setting
```
{
	"color_scheme": "Packages/Color Scheme - Default/Solarized (Dark).tmTheme",
	"font_size": 15,
	"ignored_packages":
	[
		"Vintage"
	],
	"translate_tabs_to_spaces": true,
}
```
