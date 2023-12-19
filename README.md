My pesonal build of st, which includes the following patches (also available in /patches):
alpha scrollback-ringbuffer-0.8.5 clipboard-0.8.5 xresources

The terminal gets its colors from .Xresources. You can disable that by running patch -R /patches/st-xresources-20200604-9ba7ecf.diff. If that doesn't work for some reason, run the normal patch command (with the -i flag) and spam y+enter key (it will assume you want to remove the patch).

Dependencies: Tamzen (font) picom (for the alpha patch to work)
