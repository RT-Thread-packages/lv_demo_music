import rtconfig

from building import *

cwd = GetCurrentDir()
src = Glob('*.c')
src += Glob('assets/*.c')

path =  [cwd]

group = DefineGroup('LVGL-demo', src, depend = ['PKG_USING_LV_MUSIC_DEMO'], CPPPATH = path)

Return('group')
