marslo.vim
==========
The vim color configurate by Marslo, including 256 and 16

## Usage:
### By manual:
- Download the **marslo16.vim** and **marslo256.vim**
- Put the file into colors folder, for example:
    - <pre><code>C:\Program Files (x86)\Vim\vim74\colors</code></pre>
    - <pre><code>C:\Program Files (x86)\Vim\vimfiles\colors</code></pre> | **Recommend**

### By Vundle:
- Copy the setting into **_vimrc**(windows) or **.vimrc**(Linux):
<pre><code>Bundle 'Marslo/marslo.vim'</code></pre>
- Add execute the command as below in vim/gvim:
<pre><code>:BundleInstall</code></pre>

## Screenshot:
- Windows:
![windows](https://github.com/Marslo/marslo.vim/blob/master/Screenshots/my256colors.png?raw=true)
- Linux:

## Documents about vim color:
- [rgb.txt](http://fugal.net/vim/rgbtxt.html) | [name with RGB hexadecimal number](https://github.com/Marslo/MarsloVimOthers/blob/master/AboutGvimColors/rgb/myrgb.txt)
- [vim wiki: View all colors available to gvim](http://vim.wikia.com/wiki/View_all_colors_available_to_gvim)
- [vim wiki: Xterm256 color names for console Vim](http://vim.wikia.com/wiki/Xterm256_color_names_for_console_Vim)

## ChangeLog:
### 256color:
<pre><code>
v1.0: Modified at 2012.05.29
      File Name: desert_Marslo_ForLinux
v1.1: Modified at 18/10/2012 16:49:12.92
      File Name: desert_Marslo_ForLinux_2
v1.2: Modified at 08/11/2012 16:05:59.95
      File Name: desert_Marslo_ForLinux_3
      Modified: g:colors_name
                Normal        guibg
                NonText       guibg
                StatusLine    guibg
                StatusLineNC  guibg
                Folded        guibg
                FoldColumn    guibg
v1.3: Modified at 17/12/12 19:36:21
      File Name: desert_Marslo_ForLinux_v3
      Modifed:
               Pmenu        guibg ctermbg
               PmenuSel     guifg guibg ctermbg
               PmenuSbar    guifg guibg
v1.4: Modified at 31/10/13 15:47:08
      File Name: marslo.vim
      Added:
              MatchParen      guibg ctermbg gui cterm term
              LineNr          guifg guibg ctermfg ctermbg
              CursorLineNr    guifg guibg gui ctermbg ctermfg
v1.5: Modified at 07/11/13 17:52:47
      File Name: marslo.vim
      Added:
              MBEVisibleActive    guifg guibg
              MBEVisibleNormal    guifg guibg
v1.6: Modified at 12/11/13 14:08:10
      File Name: marslo265.vim
      Add:
              HTML tags
              NERDTree
      Modifiy:
              Identifier          cterm
              Visual              ctermfg
              Change name from marslo.vim to marslo256.vim
v.1.7: Modified at 12/11/13 15:58:50
      File Name: marslo256.vim
      Modified:
              Update the format
v1.8: Modified at 18/11/13  20:03:20
      File Name: marslo256.vim
      Modified:
              String              guifg
              Entity              guifg
              Support             guifg
              Type                guifg
              FoldColumn          guifg
              Directory           guifg
v1.9: Modified at 30/12/13 19:51:11
      Modified:
              spearate the change log
</code></pre>

### 16colors
<pre><code>
v1.0: Modified at 2012.05.29
      File Name: desert_Marslo_ForLinux
v1.1: Modified at 18/10/2012 16:49:12.92
      File Name: desert_Marslo_ForLinux_2
v1.2: Modified at 08/11/2012 16:05:59.95
      File Name: desert_Marslo_ForLinux_3
      Modified: g:colors_name
                Normal        guibg
                NonText       guibg
                StatusLine    guibg
                StatusLineNC  guibg
                Folded        guibg
                FoldColumn    guibg
v1.3: Modified at 17/12/12 19:36:21
      File Name: desert_Marslo_ForLinux_v3
      Modifed:
               Pmenu        guibg ctermbg
               PmenuSel     guifg guibg ctermbg
               PmenuSbar    guifg guibg
v1.4: Modified at 31/10/13 15:47:08
      File Name: marslo.vim
      Added:
              MatchParen      guibg ctermbg gui cterm term
              LineNr          guifg guibg ctermfg ctermbg
              CursorLineNr    guifg guibg gui ctermbg ctermfg
v1.5: Modified at 07/11/13 17:52:47
      File Name: marslo.vim
      Added:
              MBEVisibleActive    guifg guibg
              MBEVisibleNormal    guifg guibg
V1.6: Modified at 12/11/13 14:20:13
      File Name: marslo16.vim
      Modified:
              Change name from marslo.vim to marslo16.vim
v1.7: Modified at 13/11/13 18:20:09
      File Name: marslo16.vim
      Modified:
              Update the format
v1.8: Modified at 18/11/13  20:03:20
      File Name: marslo16.vim
      Modified:
              String              guifg
              Entity              guifg
              Support             guifg
              Type                guifg
              FoldColumn          guifg
              Directory           guifg
v1.9: Modified at 30/12/13 19:51:11
      Modified:
              spearate the change log
</code></pre>

## Thanks for 
- Hans Fugal <hans@fugal.net> (http://hans.fugal.net/vim/colors/desert.vim)
