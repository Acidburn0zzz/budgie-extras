#gnome = import('gnome')

PLUGIN = 'hcorners'

install_data(
    'BudgieHotCorners.plugin',
    'budgie_hcorners.py',
    'bhcorners',
    'bhctools.py',
    install_dir: join_paths(PLUGINS_INSTALL_DIR, 'budgie-' + PLUGIN)
)

install_data(
    'bhcorners-bpanel.svg',
    'bhcpanel.svg',
    install_dir: PIXMAPS_DIR
)
