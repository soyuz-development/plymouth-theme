saturn_bgrt_plymouth = configure_file(
  input: 'saturn-bgrt.plymouth.desktop',
  output: 'saturn-bgrt.plymouth',
  configuration: {
    'PLYMOUTH_THEME_PATH': plymouth_theme_path,
  },
)

install_data(
  saturn_bgrt_plymouth,
  install_dir: plymouth_theme_path / 'saturn-bgrt',
)

install_subdir('bgrt_assets',
  install_dir: plymouth_theme_path / 'saturn-bgrt',
  strip_directory: true,
)

