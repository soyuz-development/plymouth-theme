soyuz_bgrt_plymouth = configure_file(
  input: 'soyuz-bgrt.plymouth.desktop',
  output: 'soyuz-bgrt.plymouth',
  configuration: {
    'PLYMOUTH_THEME_PATH': plymouth_theme_path,
  },
)

install_data(
  soyuz_bgrt_plymouth,
  install_dir: plymouth_theme_path / 'soyuz-bgrt',
)

install_subdir('bgrt_assets',
  install_dir: plymouth_theme_path / 'soyuz-bgrt',
  strip_directory: true,
)

