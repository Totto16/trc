inc_dirs += include_directories('.')

include_dir = get_option('prefix') / get_option('includedir')

install_headers(
    files('trc.h'),
    install_dir: include_dir / 'trc',
    preserve_path: true,
)

