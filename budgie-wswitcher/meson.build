#gnome = import('gnome')

PLUGIN = 'wswitcher'

install_data(
    'BudgieWSwitcher.plugin',
    'budgie_wswitcher.py',
    'wswitcher_run',
    'wswitcher_panelrunner',
    install_dir: join_paths(PLUGINS_INSTALL_DIR, 'budgie-' + PLUGIN)
)

install_data(
    'wsw-bpanel.svg',
    'wsw-panel.svg',
    install_dir: PIXMAPS_DIR
)
