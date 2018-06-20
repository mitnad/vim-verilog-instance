verilog-instance.vim
====================

Create SystemVerilog port instantiation from port declaration.

Work on modules, tasks, functions and all other similar structures.

![](https://raw.githubusercontent.com/antoinemadec/gif/master/veriloginstance.gif)

Installation
------------

Use your favorite plugin manager.

Using [vim-plug](https://github.com/junegunn/vim-plug):

```vim
Plug 'antoinemadec/vim-verilog-instance'
```

Quick start guide
-----------------

try these commands:

- `gbi(`
    - Start VerilogInstance command (`gb`) for `i`nner `(`parenthesis
- `vjjgb`
    - `v`isual-select `j` down twice
    - Start VerilogInstance command (`gb`) on the 3 selected lines

Options
-------
- let g:verilog_instance_skip_last_coma = {0/1}
    When the variable is 1, last printed line will skip the coma.
    The default value is 0.

Other vim plugins for Verilog/SystemVerilog
---------------------------------------

### verilog_systemverilog

[verilog_systemverilog](https://github.com/vhda/verilog_systemverilog.vim) is a syntax plugin for Verilog and SystemVerilog

Author
------

[Antoine Madec](https://github.com/antoinemadec)

License
------

Copyright (c) Antoine Madec. Distributed under the same terms as Vim itself. See :help license.
