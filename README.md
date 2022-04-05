# Vim 插件列表


<!-- vim-markdown-toc GFM -->

- [颜色主题](#颜色主题)
- [按功能分类](#按功能分类)
  - [文本对齐](#文本对齐)
  - [语法检查](#语法检查)
  - [代码补全](#代码补全)
  - [Cycle](#cycle)
  - [代码注释](#代码注释)
  - [自动补全括号](#自动补全括号)
  - [模糊搜索](#模糊搜索)
  - [文本搜索](#文本搜索)
  - [代码对齐线](#代码对齐线)
  - [Navigation](#navigation)
  - [插件管理](#插件管理)
  - [代码片段](#代码片段)
  - [状态栏](#状态栏)
  - [Surround](#surround)
  - [Taking notes](#taking-notes)
  - [Testing](#testing)
  - [文本对象](#文本对象)
  - [Tmux](#tmux)
  - [编辑历史管理](#编辑历史管理)
  - [版本控制](#版本控制)
  - [Writing](#writing)
  - [Misc](#misc)
- [编程语言](#编程语言)
  - [C、C++](#cc)
  - [Clojure](#clojure)
  - [Elixir](#elixir)
  - [Go](#go)
  - [HTML](#html)
  - [Java](#java)
  - [Javascript](#javascript)
  - [Lua](#lua)
  - [PHP](#php)
  - [Python](#python)
  - [TeX](#tex)
  - [VimL](#viml)

<!-- vim-markdown-toc -->

### 颜色主题

以下为一些比较流行的颜色主题：

- [acme-colors](https://github.com/plan9-for-vimspace/acme-colors)
- [apprentice](https://github.com/romainl/Apprentice)
- [base16](https://github.com/chriskempson/base16-vim)
- [gotham](https://github.com/whatyouhide/vim-gotham)
- [gruvbox](https://github.com/morhetz/gruvbox)
- [janah](https://github.com/mhinz/vim-janah)
- [jellybeans](https://github.com/nanotech/jellybeans.vim)
- [lucius](https://github.com/jonathanfilip/vim-lucius)
- [molokai](https://github.com/tomasr/molokai)
- [nofrils](https://github.com/robertmeta/nofrils)
- [oceanic-next](https://github.com/mhartington/oceanic-next)
- [paramount](https://github.com/owickstrom/vim-colors-paramount)
- [railscasts](https://github.com/jpo/vim-railscasts-theme)
- [seoul256](https://github.com/junegunn/seoul256.vim)
- [solarized](https://github.com/altercation/vim-colors-solarized) (or [solarized8](https://github.com/lifepillar/vim-solarized8) or [flattened](https://github.com/romainl/flattened))
- [tomorrow](https://github.com/chriskempson/vim-tomorrow-theme)
- [vividchalk](https://github.com/tpope/vim-vividchalk)
- [yowish](https://github.com/kabbamine/yowish.vim)
- [zenburn](https://github.com/jnurmine/Zenburn)

Alternatively, generate your own colorscheme using [themer](https://github.com/mjswensen/themer)
or [Colortemplate](https://github.com/lifepillar/vim-colortemplate).

### 按功能分类

#### 文本对齐

- [tabular](https://github.com/godlygeek/tabular)
- [vim-easy-align](https://github.com/junegunn/vim-easy-align)
- [vim-lion](https://github.com/tommcdo/vim-lion)

#### 语法检查

- [ale](https://github.com/w0rp/ale)
- [neomake](https://github.com/neomake/neomake)
- [syntastic](https://github.com/vim-syntastic/syntastic)

#### 代码补全

- [VimCompletesMe](https://github.com/ajh17/VimCompletesMe)
- [YouCompleteMe](https://github.com/Valloric/YouCompleteMe)
- [asyncomplete.vim](https://github.com/prabirshrestha/asyncomplete.vim)
- [completion-nvim](https://github.com/nvim-lua/completion-nvim)
- [completor.vim](https://github.com/maralla/completor.vim)
- [deoplete.nvim](https://github.com/Shougo/deoplete.nvim)
- [neocomplete.vim](https://github.com/Shougo/neocomplete.vim)
- [nvim-compe](https://github.com/hrsh7th/nvim-compe)
- [nvim-completion-manager](https://github.com/roxma/nvim-completion-manager)
- [supertab](https://github.com/ervandew/supertab)
- [vim-mucomplete](https://github.com/lifepillar/vim-mucomplete)

#### Cycle

- [switch.vim](https://github.com/AndrewRadev/switch.vim)
- [vim-speeddating](https://github.com/tpope/vim-speeddating)

#### 代码注释

- [nerdcommenter](https://github.com/scrooloose/nerdcommenter)
- [tcomment_vim](https://github.com/tomtom/tcomment_vim)
- [vim-commentary](https://github.com/tpope/vim-commentary)

#### 自动补全括号

- [auto-pairs](https://github.com/jiangmiao/auto-pairs)
- [delimitMate](https://github.com/Raimondi/delimitMate)
- [vim-endwise](https://github.com/tpope/vim-endwise)

#### 模糊搜索

- [leaderf](https://github.com/Yggdroot/LeaderF) (_requires +python3 or +python_)
- [denite.nvim](https://github.com/Shougo/denite.nvim) (_requires +python3_)
- [vim-clap](https://github.com/liuchengxu/vim-clap/)
- [Command-T](https://github.com/wincent/Command-T) (_requires +ruby_)
- [ctrlp.vim](https://github.com/ctrlpvim/ctrlp.vim)
- [fzf](https://github.com/junegunn/fzf) (and [fzf.vim](https://github.com/junegunn/fzf.vim))
- [unite.vim](https://github.com/Shougo/unite.vim)
- [vim-fz](https://github.com/mattn/vim-fz)

#### 文本搜索

- [ctrlsf.vim](https://github.com/dyng/ctrlsf.vim)
- [ferret](https://github.com/wincent/ferret)
- [vim-grepper](https://github.com/mhinz/vim-grepper)
- [flygrep](https://github.com/wsdjeg/FlyGrep.vim)

#### 代码对齐线

- [indentLine](https://github.com/Yggdroot/indentLine)
- [vim-indent-guides](https://github.com/nathanaelkane/vim-indent-guides)

#### Navigation

- [nerdtree](https://github.com/scrooloose/nerdtree)
- [tagbar](https://github.com/majutsushi/tagbar)
- [vim-dirvish](https://github.com/justinmk/vim-dirvish)
- [vim-easymotion](https://github.com/easymotion/vim-easymotion)
- [vim-sneak](https://github.com/justinmk/vim-sneak)
- [vim-vinegar](https://github.com/tpope/vim-vinegar)
- [vimfiler.vim](https://github.com/Shougo/vimfiler.vim) (_depends on other plugins_)
- [defx.nvim](https://github.com/Shougo/defx.nvim) (_requires +python3_)

Also see [fuzzy finders](#fuzzy-finders).

#### 插件管理

- [apt-vim](https://github.com/egalpin/apt-vim)
- [dein.vim](https://github.com/Shougo/dein.vim)
- [minpac](https://github.com/k-takata/minpac)
- [vim-addon-manager](https://github.com/MarcWeber/vim-addon-manager)
- [vim-pathogen](https://github.com/tpope/vim-pathogen)
- [vim-plug](https://github.com/junegunn/vim-plug)
- [vundle.vim](https://github.com/VundleVim/Vundle.vim)

#### 代码片段

- [neosnippet.vim](https://github.com/Shougo/neosnippet.vim) (_depends on other plugins_)
- [ultisnips](https://github.com/SirVer/ultisnips)
- [vim-snipmate](https://github.com/garbas/vim-snipmate) (_depends on other plugins_)
- [xptemplate](https://github.com/drmingdrmer/xptemplate)

#### 状态栏

- [lightline.vim](https://github.com/itchyny/lightline.vim)
- [powerline](https://github.com/powerline/powerline)
- [vim-airline](https://github.com/vim-airline/vim-airline)
- [vim-flagship](https://github.com/tpope/vim-flagship)

#### Surround

- [vim-operator-surround](https://github.com/rhysd/vim-operator-surround)
- [vim-sandwich](https://github.com/machakann/vim-sandwich)
- [vim-surround](https://github.com/tpope/vim-surround)

#### Taking notes

- [vim-dotoo](https://github.com/dhruvasagar/vim-dotoo)
- [vim-journal](https://github.com/junegunn/vim-journal)
- [vim-notes](https://github.com/xolox/vim-notes)
- [vim-orgmode](https://github.com/jceb/vim-orgmode)
- [vim-pad](https://github.com/fmoralesc/vim-pad)
- [vimwiki](https://github.com/vimwiki/vimwiki)

#### Testing

- [vim-test](https://github.com/janko-m/vim-test)

#### 文本对象

- [targets.vim](https://github.com/wellle/targets.vim)
- [vim-exchange](https://github.com/tommcdo/vim-exchange)
- [vim-indent-object](https://github.com/michaeljsmith/vim-indent-object)
- [vim-matchup](https://github.com/andymass/vim-matchup)
- [vim-textobj-user](https://github.com/kana/vim-textobj-user)

#### Tmux

- [tmux-complete.vim](https://github.com/wellle/tmux-complete.vim)
- [vim-dispatch](https://github.com/tpope/vim-dispatch)
- [vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator)
- [vitality.vim](https://github.com/sjl/vitality.vim)

#### 编辑历史管理

- [vim-mundo](https://github.com/simnalamburt/vim-mundo)
- [gundo.vim](https://github.com/sjl/gundo.vim)
- [undotree](https://github.com/mbbill/undotree)

#### 版本控制

- [agit.vim](https://github.com/cohama/agit.vim)
- [committia.vim](https://github.com/rhysd/committia.vim)
- [gist-vim](https://github.com/mattn/gist-vim)
- [github-issues.vim](https://github.com/jaxbot/github-issues.vim)
- [gitv](https://github.com/gregsexton/gitv)
- [gv.vim](https://github.com/junegunn/gv.vim)
- [nerdtree-git-plugin](https://github.com/Xuyuanp/nerdtree-git-plugin)
- [vim-auto-programming](https://github.com/haya14busa/vim-auto-programming)
- [vim-fugitive](https://github.com/tpope/vim-fugitive)
- [vim-gitgutter](https://github.com/airblade/vim-gitgutter)
- [vim-github-dashboard](https://github.com/junegunn/vim-github-dashboard)
- [vim-lawrencium](https://bitbucket.org/ludovicchabant/vim-lawrencium)
- [vim-signify](https://github.com/mhinz/vim-signify)
- [vimagit](https://github.com/jreybert/vimagit)
- [git-messenger.vim](https://github.com/rhysd/git-messenger.vim/)

#### Writing

- [vim-grammarous](https://github.com/rhysd/vim-grammarous)
- [vim-online-thesaurus](https://github.com/beloglazov/vim-online-thesaurus)

#### Misc

- [calendar.vim](https://github.com/itchyny/calendar.vim)
- [CoVim](https://github.com/FredKSchott/CoVim)
- [FastFold](https://github.com/Konfekt/FastFold)
- [goyo.vim](https://github.com/junegunn/goyo.vim)
- [is.vim](https://github.com/haya14busa/is.vim)
- [NrrwRgn](https://github.com/chrisbra/NrrwRgn)
- [sideways.vim](https://github.com/AndrewRadev/sideways.vim)
- [splitjoin.vim](https://github.com/AndrewRadev/splitjoin.vim)
- [unicode.vim](https://github.com/chrisbra/unicode.vim)
- [vim-abolish](https://github.com/tpope/vim-abolish)
- [vim-bracketed-paste](https://github.com/ConradIrwin/vim-bracketed-paste)
- [vim-devicons](https://github.com/ryanoasis/vim-devicons)
- [vim-diff-enhanced](https://github.com/chrisbra/vim-diff-enhanced)
- [vim-diminactive](https://github.com/blueyed/vim-diminactive)
- [vim-fixkey](https://github.com/drmikehenry/vim-fixkey)
- [vim-gnupg](https://github.com/jamessan/vim-gnupg)
- [vim-gutentags](https://github.com/ludovicchabant/vim-gutentags)
- [vim-hackernews](https://github.com/ryanss/vim-hackernews)
- [vim-move](https://github.com/matze/vim-move)
- [vim-multiple-cursors](https://github.com/terryma/vim-multiple-cursors)
- [vim-projectionist](https://github.com/tpope/vim-projectionist)
- [vim-qf](https://github.com/romainl/vim-qf)
- [vim-rsi](https://github.com/tpope/vim-rsi)
- [vim-sleuth](https://github.com/tpope/vim-sleuth)
- [vim-startify](https://github.com/mhinz/vim-startify)
- [vim-unimpaired](https://github.com/tpope/vim-unimpaired)

### 编程语言

#### C、C++

- [a.vim](https://github.com/vim-scripts/a.vim)
- [clang_complete](https://github.com/Rip-Rip/clang_complete)
- [color_coded](https://github.com/jeaye/color_coded)
- [lh-cpp](https://github.com/LucHermitte/lh-cpp)
- [vim-cpp-enhanced-highlight](https://github.com/octol/vim-cpp-enhanced-highlight)

#### Clojure

- [paredit](https://github.com/kovisoft/paredit)
- [rainbow_parentheses.vim](https://github.com/junegunn/rainbow_parentheses.vim)
- [vim-clojure-highlight](https://github.com/guns/vim-clojure-highlight)
- [vim-fireplace](https://github.com/tpope/vim-fireplace)
- [vim-salve](https://github.com/tpope/vim-salve)
- [vim-sexp-mappings-for-regular-people](https://github.com/tpope/vim-sexp-mappings-for-regular-people)
- [vim-sexp](https://github.com/guns/vim-sexp)

#### Elixir

- [alchemist.vim](https://github.com/slashmili/alchemist.vim)
- [vim-elixir](https://github.com/elixir-editors/vim-elixir)
- [vim-mix-format](https://github.com/mhinz/vim-mix-format)

#### Go

- [gofmt.vim](https://github.com/tweekmonster/gofmt.vim)
- [hl-goimport.vim](https://github.com/tweekmonster/hl-goimport.vim)
- [vim-go](https://github.com/fatih/vim-go)
- [vim-godebug](https://github.com/jodosha/vim-godebug)

#### HTML

- [emmet-vim](https://github.com/mattn/emmet-vim)
- [html5.vim](https://github.com/othree/html5.vim)

#### Java

- [vim-javacomplete2](https://github.com/artur-shaik/vim-javacomplete2)

#### Javascript

- [es.next.syntax.vim](https://github.com/othree/es.next.syntax.vim)
- [javascript-libraries-syntax.vim](https://github.com/othree/javascript-libraries-syntax.vim)
- [node-vim-debugger](https://github.com/sidorares/node-vim-debugger)
- [tern_for_vim](https://github.com/ternjs/tern_for_vim)
- [vim-esformatter](https://github.com/millermedeiros/vim-esformatter)
- [vim-flow](https://github.com/flowtype/vim-flow)
- [vim-javascript-syntax](https://github.com/jelera/vim-javascript-syntax)
- [vim-javascript](https://github.com/pangloss/vim-javascript)
- [vim-node](https://github.com/moll/vim-node)
- [vim-prettier](https://github.com/prettier/vim-prettier)
- [yajs.vim](https://github.com/othree/yajs.vim)
- [yats.vim](https://github.com/HerringtonDarkholme/yats.vim)

#### Lua

- [vim-lua-ftplugin](https://github.com/xolox/vim-lua-ftplugin)
- [vim-lua-inspect](https://github.com/xolox/vim-lua-inspect)

#### PHP

- [php.vim](https://github.com/StanAngeloff/php.vim)
- [vim-php-cs-fixer](https://github.com/stephpy/vim-php-cs-fixer)
- [vim-php-namespace](https://github.com/arnaud-lb/vim-php-namespace)
- [vim-php-refactoring-toolbox](https://github.com/adoy/vim-php-refactoring-toolbox)

#### Python

- [braceless.vim](https://github.com/tweekmonster/braceless.vim)
- [impsort.vim](https://github.com/tweekmonster/impsort.vim)
- [jedi-vim](https://github.com/davidhalter/jedi-vim)
- [python-mode](https://github.com/klen/python-mode)
- [SimpylFold](https://github.com/tmhedberg/SimpylFold)
- [vim-flake8](https://github.com/nvie/vim-flake8)

#### TeX

- [vimtex](https://github.com/lervag/vimtex)

#### VimL

- [exception.vim](https://github.com/tweekmonster/exception.vim)
- [helpful.vim](https://github.com/tweekmonster/helpful.vim)
- [vader.vim](https://github.com/junegunn/vader.vim)
- [vim-lookup](https://github.com/mhinz/vim-lookup)
- [vim-scriptease](https://github.com/tpope/vim-scriptease)
- [vim-themis](https://github.com/thinca/vim-themis)
