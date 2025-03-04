from building import *
import os

cwd = GetCurrentDir()
path = [os.path.join(cwd, 'inc')]
src_path = os.path.join(cwd, 'src')

CPPDEFINES = ['USE_STDPERIPH_DRIVER']

src = [
os.path.join(src_path, 'at32f425_acc.c'),
os.path.join(src_path, 'at32f425_adc.c'),
os.path.join(src_path, 'at32f425_can.c'),
os.path.join(src_path, 'at32f425_crc.c'),
os.path.join(src_path, 'at32f425_crm.c'),
os.path.join(src_path, 'at32f425_debug.c'),
os.path.join(src_path, 'at32f425_dma.c'),
os.path.join(src_path, 'at32f425_ertc.c'),
os.path.join(src_path, 'at32f425_exint.c'),
os.path.join(src_path, 'at32f425_flash.c'),
os.path.join(src_path, 'at32f425_gpio.c'),
os.path.join(src_path, 'at32f425_i2c.c'),
os.path.join(src_path, 'at32f425_misc.c'),
os.path.join(src_path, 'at32f425_pwc.c'),
os.path.join(src_path, 'at32f425_scfg.c'),
os.path.join(src_path, 'at32f425_spi.c'),
os.path.join(src_path, 'at32f425_tmr.c'),
os.path.join(src_path, 'at32f425_usart.c'),
os.path.join(src_path, 'at32f425_wdt.c'),
os.path.join(src_path, 'at32f425_wwdt.c'),
]

group = DefineGroup('libraries', src, depend = ['PKG_USING_AT32F425_HAL_DRIVER'], CPPPATH = path, CPPDEFINES = CPPDEFINES)

Return('group')
